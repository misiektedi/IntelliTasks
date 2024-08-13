<script>
    let tasks = ['element1', 'element2', 'element3'];
</script>

<main>
    <ul>
        {#each tasks as task}
            <li>{task}</li>
        {/each}
    </ul>
</main>