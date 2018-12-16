<template>
  <div>
    <md-card>
      <md-card-header>
        <div class="md-title">lets get begun</div>
      </md-card-header>

      <md-card-content>blah content meh</md-card-content>

      <md-card-actions>
        <md-button class='md-raised md-primary'>do thing</md-button>
        <md-button class='md-raised'>another thing</md-button>
      </md-card-actions>
    </md-card>
  </div>
</template>

<script>
export default {
  name: "RegularCards"
};
</script>

<style lang="scss" scoped>
  .md-card {
    width: 320px;
    margin: 4px;
    display: inline-block;
    vertical-align: top;
  }

</style>