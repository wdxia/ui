<template>
    <button class="x-button"> 按钮 </button>
</template>
<script>
    export default {
        name: 'Buttons',
        data() {
            return {

            }
        },
        methods: {

        }
    }
</script>
<style lang="scss">
    .x-button {
        font-size: var(--font-size);
        height: var(--button-height);
        padding: 0 1em;
        border-radius: var(--border-radius);
        border: 1px solid var(--border-color);
        background: var(--button-bg);
        &:hover {
            background-color: var(--border-color);
        }
    }

</style>