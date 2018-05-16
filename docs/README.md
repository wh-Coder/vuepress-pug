# pug

<style lang="stylus" scoped>
.hello
    color red
</style>

<template lang="pug">
p.hello {{ msg }}
</template>

<script>
export default {
    data() {
        return {
            msg: 'hello'
        }

    },
}
</script>