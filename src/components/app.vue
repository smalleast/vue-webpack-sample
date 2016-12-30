<script>
    export default {
        el: "#app",
        data() {
            return {
                name: "guowenfh",
                age: "2000055555555555555555555000006"
            }
        }
    }
</script>
<template>
    <div>
        <h1>姓名10：{{name}}</h1>
        <h2>{{age}}</h2>
        <h3>3333</h3>
    </div>
</template>
<style>
    $qwe:#098;
    body {
        background-color: $qwe;
        h1{
            background-color: #00f;
            color: yellow;
            transform: translate(10%, 10%);
        }

        h1:hover {
            height: 100px;
        }

        h2 {
            background-color: #888;
        }
    }
</style>
