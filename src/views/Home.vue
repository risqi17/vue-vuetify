<template>
  <v-app :style="{background: $vuetify.theme.themes.light.background}">
    <v-container>
      <v-row>
        <v-col cols="12" md="4">
          <v-text-field label="Search items" prepend-icon="search" color="green"></v-text-field>
        </v-col>
        <v-spacer></v-spacer>
        <span class="green--text mt-9">29 items</span>
        <v-btn text class="mt-7">
          <v-icon color="green" class="mr-n10">menu</v-icon>
        </v-btn>
        <v-btn text class="mt-7">
          <v-icon color="green" class="mr-n10">dashboard</v-icon>
        </v-btn>
      </v-row>
      <v-row>
        <v-col cols="12" md="3" class="mb-4">
          <v-hover v-slot:default="{ hover }">
            <v-card max-width="250" max-height="250" align="center">
              <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn icon><v-icon>edit</v-icon></v-btn>
              </v-card-actions>
              <v-img src="11.PNG" width="150" height="150"></v-img>
              <v-card-text class="blue-grey--text">Color Mixed 2019</v-card-text>
              <v-expand-transition>
                <div v-if="hover" class="d-flex transition-fast-in-fast-out green v-card-reveal display-3 white--text" style="height: 100%">
                  <v-btn outlined="" color="white">Detail</v-btn>
                </div>

              </v-expand-transition>
              <v-btn absolute="" color="green" class="white--text" fab large left top>
                <h1>12</h1>
              </v-btn>
            </v-card>
          </v-hover>
        </v-col>

        <v-col cols="12" md="3" class="mb-4">
          <v-hover v-slot:default="{ hover }">
            <v-card max-width="250" max-height="250" align="center">
              <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn icon><v-icon>edit</v-icon></v-btn>
              </v-card-actions>
              <v-img src="22.PNG" width="150" height="150"></v-img>
              <v-card-text class="blue-grey--text">Color Mixed 2018</v-card-text>
              <v-expand-transition>
                <div v-if="hover" class="d-flex transition-fast-in-fast-out green v-card-reveal display-3 white--text" style="height: 100%">
                  <v-btn outlined="" color="white">Detail</v-btn>
                </div>

              </v-expand-transition>
              <v-btn absolute="" color="green" class="white--text" fab large left top>
                <h1>7</h1>
              </v-btn>
            </v-card>
          </v-hover>
        </v-col>

        <v-col cols="12" md="3" class="mb-4">
          <v-hover v-slot:default="{ hover }">
            <v-card max-width="250" max-height="250" align="center">
              <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn icon><v-icon>edit</v-icon></v-btn>
              </v-card-actions>
              <v-img src="33.PNG" width="150" height="150"></v-img>
              <v-card-text class="blue-grey--text">Color Combination 2017</v-card-text>
              <v-expand-transition>
                <div v-if="hover" class="d-flex transition-fast-in-fast-out green v-card-reveal display-3 white--text" style="height: 100%">
                  <v-btn outlined="" color="white">Detail</v-btn>
                </div>

              </v-expand-transition>
              <v-btn absolute="" color="green" class="white--text" fab large left top>
                <h1>10</h1>
              </v-btn>
            </v-card>
          </v-hover>
        </v-col>

        <v-col cols="12" md="3" class="mb-4">
          <v-hover v-slot:default="{ hover }">
            <v-card max-width="250" max-height="250" align="center">
              <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn icon><v-icon>edit</v-icon></v-btn>
              </v-card-actions>
              <v-img src="11.PNG" width="150" height="150"></v-img>
              <v-card-text class="blue-grey--text">Color Mixed 2019</v-card-text>
              <v-expand-transition>
                <div v-if="hover" class="d-flex transition-fast-in-fast-out green v-card-reveal display-3 white--text" style="height: 100%">
                  <v-btn outlined="" color="white">Detail</v-btn>
                </div>

              </v-expand-transition>
              <v-btn absolute="" color="green" class="white--text" fab large left top>
                <h1>22</h1>
              </v-btn>
            </v-card>
          </v-hover>
        </v-col>

        <v-col cols="12" md="3" class="mb-4">
          <v-hover v-slot:default="{ hover }">
            <v-card max-width="250" max-height="250" align="center">
              <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn icon><v-icon>edit</v-icon></v-btn>
              </v-card-actions>
              <v-img src="11.PNG" width="150" height="150"></v-img>
              <v-card-text class="blue-grey--text">Color Mixed 2019</v-card-text>
              <v-expand-transition>
                <div v-if="hover" class="d-flex transition-fast-in-fast-out green v-card-reveal display-3 white--text" style="height: 100%">
                  <v-btn outlined="" color="white">Detail</v-btn>
                </div>

              </v-expand-transition>
              <v-btn absolute="" color="green" class="white--text" fab large left top>
                <h1>18</h1>
              </v-btn>
            </v-card>
          </v-hover>
        </v-col>

        <v-col cols="12" md="3" class="mb-4">
          <v-hover v-slot:default="{ hover }">
            <v-card max-width="250" max-height="250" align="center">
              <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn icon><v-icon>edit</v-icon></v-btn>
              </v-card-actions>
              <v-img src="11.PNG" width="150" height="150"></v-img>
              <v-card-text class="blue-grey--text">Color Mixed 2019</v-card-text>
              <v-expand-transition>
                <div v-if="hover" class="d-flex transition-fast-in-fast-out green v-card-reveal display-3 white--text" style="height: 100%">
                  <v-btn outlined="" color="white">Detail</v-btn>
                </div>

              </v-expand-transition>
              <v-btn absolute="" color="green" class="white--text" fab large left top>
                <h1>14</h1>
              </v-btn>
            </v-card>
          </v-hover>
        </v-col>

        <v-col cols="12" md="3" class="mb-4">
          <v-hover v-slot:default="{ hover }">
            <v-card max-width="250" max-height="250" align="center">
              <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn icon><v-icon>edit</v-icon></v-btn>
              </v-card-actions>
              <v-img src="11.PNG" width="150" height="150"></v-img>
              <v-card-text class="blue-grey--text">Color Mixed 2019</v-card-text>
              <v-expand-transition>
                <div v-if="hover" class="d-flex transition-fast-in-fast-out green v-card-reveal display-3 white--text" style="height: 100%">
                  <v-btn outlined="" color="white">Detail</v-btn>
                </div>

              </v-expand-transition>
              <v-btn absolute="" color="green" class="white--text" fab large left top>
                <h1>20</h1>
              </v-btn>
            </v-card>
          </v-hover>
        </v-col>

        <v-col cols="12" md="3" class="mb-4">
          <v-hover v-slot:default="{ hover }">
            <v-card max-width="250" max-height="250" align="center">
              <v-card-actions>
                <v-spacer></v-spacer>
                <v-btn icon><v-icon>edit</v-icon></v-btn>
              </v-card-actions>
              <v-img src="11.PNG" width="150" height="150"></v-img>
              <v-card-text class="blue-grey--text">Color Mixed 2019</v-card-text>
              <v-expand-transition>
                <div v-if="hover" class="d-flex transition-fast-in-fast-out green v-card-reveal display-3 white--text" style="height: 100%">
                  <v-btn outlined="" color="white">Detail</v-btn>
                </div>

              </v-expand-transition>
              <v-btn absolute="" color="green" class="white--text" fab large left top>
                <h1>2</h1>
              </v-btn>
            </v-card>
          </v-hover>
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>

<script>

export default {
  name: 'home',
  components: {

  },
  computed:{
    theme(){
      return (this.$vuetify.theme.theme.dark) ? 'dark' : 'light'
    }
  }
}
</script>
<style scoped>
.v-card-reveal{
  align-items: center;
  bottom: 0;
  justify-content: center;
  opacity: .5;
  position: absolute;
  width: 100%;
}
</style>
