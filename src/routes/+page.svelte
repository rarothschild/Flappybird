<script lang="ts">
    import { GameController } from "../components/game"
    const game = new GameController();
    let frame = game.newGame();
</script>

<style>
main {
    position: relative;
    border: solid black 1px;
    overflow: hidden;
    background-color: lightblue;
}
</style>

<pre>
{JSON.stringify(frame,null,2)}
</pre>
<main style="width: {frame.width}px; height: {frame.height}px;" class="game">

</main>