<script>
    export default { 
        data() {
            return {
                width: '200',
                height: '200',
                myImg: '/assets/me.png'
            }
        },
    }
</script>

<template>

    <!-- add code here -->
    <img v-bind:src="myImg" v-bind:width="width" v-bind:height="height"/>
    <!--- alternatvely, can use :src="myImg" as well since : is a shorthand notation for v-bind-->
</template>
