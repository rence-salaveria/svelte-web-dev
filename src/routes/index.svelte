<script lang="ts">
    import TodoItem from '$lib/components/TodoItem.svelte';

    const title: String = 'Todos'
</script>

<svelte:head>
    {title}
</svelte:head>

<h1>{title}</h1>

<!-- Create a Todo form -->
<form action="">
    <input type="text" aria-label="Add a Todo" placeholder="+ tap to add a Todo"/>
</form>

<TodoItem/>
<TodoItem/>
<TodoItem/>