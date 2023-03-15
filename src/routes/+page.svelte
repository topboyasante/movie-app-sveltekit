<script>
    let count = 0

    function increaseNumber(){
        count +=1
    }
    function decreaseNumber(){
        count -=1
    }
</script>


<h1>Number : {count}</h1>

<button on:click={increaseNumber}>Increment</button>
<button on:click={decreaseNumber}>Decrement</button>
<!-- Writing -->
<a href="/about">Go To The About Page</a>