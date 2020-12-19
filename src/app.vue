<template>
    <div id="app">
        <h1>{{title}}</h1>
        <p>{{message}}</p>
    </div>
</template>

<script>
export default {
    name: 'App',
    data () {
        return {
            title: 'Parcel Vue Example',
            message: 'Hello!'
        }
    }
}
</script>
