<script>
    import '$lib/fonts/proximanova.css';
</script>

<div id='big-container'>
    <p>Coming soon!</p>
    <h1>Bowls that<br>don't get<br>hot in the<br>microwave</h1>
    <p>Be part of the revolution.</p>
    <p id='mind'>From the mind of Emma Harvey</p>
</div>

<style>
    h1 {
        background-color: #eebbc3;
        padding: 60px;
        border-color: #121629;
        border-radius: 3px;
        border-width: 1px;
        color: #232946;
        font-family: Proxima Nova;
        text-transform: uppercase;
        letter-spacing: -5px;
        line-height: 0.75em;
        width: fit-content;
        text-align: center;
        font-size: 115px;
        font-family: Proxima Nova Bl;
        text-wrap: balance;
        margin: 0;
    }
    p {
        color: #fffffe;
        font-size: 30px;
        font-family: Proxima Nova;
    }
    #mind {
        color: #b8c1ec;
        font-size: 20px;
    }
    @media (width < 740px) {
        h1 {
            font-size: 58px;
            line-height: 0.7em;
            margin: 0 10px;
            padding: 20px;
            max-width: 100vw;
        }
        p {
            font-size: 24px;
        }
    }
    #big-container {
        height: 100vh;
        width: 100vw;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        gap: 10px;
    }
    :global(body, html) {
        margin: 0;
        background-color: #232946;
    }
</style>
