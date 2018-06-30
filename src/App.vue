<template>
    <div id="app">
        <h1 v-text="msg"></h1>
        <markdown-task>
            
        </markdown-task>
    </div>
</template>
<script>
import MarkdownTask from './components/MarkdownTask.vue';
export default {
    components: { MarkdownTask },
    data() {
        return {
            msg: 'Hello Vue from Parcel!'
        }
    }
}
</script>
