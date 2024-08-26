<template>
    <img
        :src="logoUrl"
        alt="Logo Jepara"
        v-bind="$attrs"
    />
</template>

<script>
export default {
    data() {
        return {
            logoUrl: "https://sippn.menpan.go.id/images/article/large/logo-jepara-11.png"
        };
    }
};
</script>
