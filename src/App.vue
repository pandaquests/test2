<template style="overflow: hidden;">
  <v-app id="inspire">
    <v-bottom-navigation
        scroll-target="#scroll-area-2"
        v-model="bottomNav"
        shift
        hide-on-scroll
        absolute
        horizontal
        style="margin-bottom: 5px;"
    >
      <v-btn>
        <span>Video</span>
        <v-icon>mdi-television-play</v-icon>
      </v-btn>

      <v-btn>
        <span>Music</span>
        <v-icon>mdi-panda</v-icon>
      </v-btn>

      <v-btn>
        <span>Book</span>
        <v-icon>mdi-book</v-icon>
      </v-btn>

      <v-btn>
        <span>Image</span>
        <v-icon>mdi-image</v-icon>
      </v-btn>
    </v-bottom-navigation>
    <v-sheet
        id="scroll-area-2"
        class="overflow-y-auto"
        max-height="600"
    >
      <v-container style="height: auto;">
        <v-card
            class="mx-auto"
            max-width="344"
        >
          <v-img
              src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
              height="200px"
          ></v-img>

          <v-card-title>
            <div>Top western road trips</div>
            <span class="grey--text subtitle-1">1,000 miles of wonder</span>
          </v-card-title>

          <v-card-actions>
            <v-btn text>Share</v-btn>

            <v-btn
                text
                color="purple"
            >
              Explore
            </v-btn>

            <div class="flex-grow-1"></div>

            <v-btn
                icon
                @click="show = !show"
            >
              <v-icon>{{ show ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-expand-transition>
            <div v-show="show">
              <v-card-text>
                I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
              </v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
        <v-card
            class="mx-auto"
            max-width="344"
        >
          <v-img
              src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
              height="200px"
          ></v-img>

          <v-card-title>
            <div>Top western road trips</div>
            <span class="grey--text subtitle-1">1,000 miles of wonder</span>
          </v-card-title>

          <v-card-actions>
            <v-btn text>Share</v-btn>

            <v-btn
                text
                color="purple"
            >
              Explore
            </v-btn>

            <div class="flex-grow-1"></div>

            <v-btn
                icon
                @click="show = !show"
            >
              <v-icon>{{ show ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-expand-transition>
            <div v-show="show">
              <v-card-text>
                I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
              </v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
        <v-card
            class="mx-auto"
            max-width="344"
        >
          <v-img
              src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
              height="200px"
          ></v-img>

          <v-card-title>
            <div>Top western road trips</div>
            <span class="grey--text subtitle-1">1,000 miles of wonder</span>
          </v-card-title>

          <v-card-actions>
            <v-btn text>Share</v-btn>

            <v-btn
                text
                color="purple"
            >
              Explore
            </v-btn>

            <div class="flex-grow-1"></div>

            <v-btn
                icon
                @click="show = !show"
            >
              <v-icon>{{ show ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-expand-transition>
            <div v-show="show">
              <v-card-text>
                I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
              </v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
        <v-card
            class="mx-auto"
            max-width="344"
        >
          <v-img
              src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
              height="200px"
          ></v-img>

          <v-card-title>
            <div>Top western road trips</div>
            <span class="grey--text subtitle-1">1,000 miles of wonder</span>
          </v-card-title>

          <v-card-actions>
            <v-btn text>Share</v-btn>

            <v-btn
                text
                color="purple"
            >
              Explore
            </v-btn>

            <div class="flex-grow-1"></div>

            <v-btn
                icon
                @click="show = !show"
            >
              <v-icon>{{ show ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-expand-transition>
            <div v-show="show">
              <v-card-text>
                I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
              </v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
        <v-card
            class="mx-auto"
            max-width="344"
        >
          <v-img
              src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
              height="200px"
          ></v-img>

          <v-card-title>
            <div>Top western road trips</div>
            <span class="grey--text subtitle-1">1,000 miles of wonder</span>
          </v-card-title>

          <v-card-actions>
            <v-btn text>Share</v-btn>

            <v-btn
                text
                color="purple"
            >
              Explore
            </v-btn>

            <div class="flex-grow-1"></div>

            <v-btn
                icon
                @click="show = !show"
            >
              <v-icon>{{ show ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-expand-transition>
            <div v-show="show">
              <v-card-text>
                I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
              </v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
        <v-card
            class="mx-auto"
            max-width="344"
        >
          <v-img
              src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
              height="200px"
          ></v-img>

          <v-card-title>
            <div>Top western road trips</div>
            <span class="grey--text subtitle-1">1,000 miles of wonder</span>
          </v-card-title>

          <v-card-actions>
            <v-btn text>Share</v-btn>

            <v-btn
                text
                color="purple"
            >
              Explore
            </v-btn>

            <div class="flex-grow-1"></div>

            <v-btn
                icon
                @click="show = !show"
            >
              <v-icon>{{ show ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-expand-transition>
            <div v-show="show">
              <v-card-text>
                I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
              </v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
        <v-card
            class="mx-auto"
            max-width="344"
        >
          <v-img
              src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
              height="200px"
          ></v-img>

          <v-card-title>
            <div>Top western road trips</div>
            <span class="grey--text subtitle-1">1,000 miles of wonder</span>
          </v-card-title>

          <v-card-actions>
            <v-btn text>Share</v-btn>

            <v-btn
                text
                color="purple"
            >
              Explore
            </v-btn>

            <div class="flex-grow-1"></div>

            <v-btn
                icon
                @click="show = !show"
            >
              <v-icon>{{ show ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-expand-transition>
            <div v-show="show">
              <v-card-text>
                I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
              </v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
      </v-container>
    </v-sheet>
  </v-app>
</template>

<script>
  export default {
    props: {
      source: String,
    },
    data: () => ({
      bottomNav: 3,
      show: false,
    }),
    created () {
      this.$vuetify.theme.dark = true
    },
  }
</script>
