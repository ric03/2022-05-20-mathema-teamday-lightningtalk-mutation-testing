<template>
  <div class="slidev-layout">
    <div>
        <slot name="top" />
    </div>
    <div class="two-columns w-full grid grid-cols-2">
      <div class="col-left" :class="two-cols">
        <slot name="left" />
      </div>
      <div class="col-right" :class="two-cols" style="margin-left:1rem;">
        <slot name="right" />
      </div>
    </div>
    <div>
        <slot name="bottom" />
    </div>
  </div>
</template>