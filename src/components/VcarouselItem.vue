<template>
    <div class="v-carousel-item">
        <img :src='require("../assets/images" + carousel_data.image)'>
    </div>
</template>


<script>
    export default {
        name: 'VcarouselItem',
        props: {
            item_data: {
                type: Object,
                default: () => {}
            }
        },
        data() {
            return {}
        },
        computed: {}
    }
</script>