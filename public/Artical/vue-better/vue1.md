```html
<template functional>
	<div>
        <div v-if="value" class="on"></div>
        <section v-else class="off"></section>
    </div>
</template>

<script>
	export default {
        props: ['value']
    }
</script>
```

