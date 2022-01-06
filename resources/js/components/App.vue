<template>
<div>
    <h1 style="margin-top: 200px; text-align: center">Todo list</h1>
    <div class="todoListContainer">
        <add-Item-form />
        <list-view/>
    </div>
</div>

</template>

<script>
import addItemForm from './addItemForm';
import listView from './listView';

    export default {
        components: {
            addItemForm,
            listView
        }
      
      
    }
</script>
<style scoped>
    .todoListContainer{
        width: 400px;
        margin: auto;
        margin-top: 50px;

    }

</style>

