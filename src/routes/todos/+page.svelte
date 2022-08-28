<script>
    import TodoItem from "../components/todo-item.svelte";
</script>

<svelte:head>
    <title>Web App - Todos</title>
</svelte:head>

<h1>Todos App</h1>

<form method="post">
    <input type="text" name="todo" aria-label="Add a todo" placeholder="Add Todo ...">
    <input type="submit" value="Add New Todo">
</form>

<TodoItem />