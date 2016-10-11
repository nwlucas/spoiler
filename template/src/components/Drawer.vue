<template>
  <div class="mdl-layout__drawer">
    <span class="mdl-layout__title">{{name}}</span>
    <nav class="mdl-navigation">
      <slot></slot>
    </nav>
  </div>
</template>

<script>
export default {};
</script>
