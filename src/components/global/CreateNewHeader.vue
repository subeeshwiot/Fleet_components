<template>
  <v-app>
    <v-banner single-line>
      <v-icon slot="icon" color="warning" size="36">
        mdi-wifi-strength-alert-outline
      </v-icon>
      <span class="font-weight-bold">{{ head }}</span>
      <template v-slot:actions>
        <v-btn depressed> Cancel </v-btn>
        <v-btn depressed color="primary"> Next </v-btn>
      </template>
    </v-banner>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      head: "Create New Driver",
    };
  },
};
</script>
