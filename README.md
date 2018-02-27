<!DOCTYPE html>
<html>
<head>
  <title>Intro to JavaScript</title>
  <style>
  #operations code{
    font-size: 18px;
    font-weight: bold;
  }

  img{

    max-width: 100%;
  }
</style>
</head>

<body>
  <h1>Artist</h1>

  <section>
    <h2>Introduction</h2>
    <p>You can also use code instructions to make art!</p>


    <p>Edit the <code>picasso() function</code> in the <code>artist.js</code> file to add your own instructions. </p>

    <p> Below are a few operations that have been given to you. You can use them to draw lines and move around the canvas below. The position starts at the center of the canvas.</p>

    <p>In the example below, we drew the letter 'A'. How would you draw other alphabets? Try drawing your own initials!</p>

    <div id="canvas"></div>
    <p>*You will see a black dot appear on your drawing above. This indicates where the last position you moved or drew to.</p>
  </section>

  <section id='operations'>
    <h2>Operations</h2>
    <p>
      <code>drawLineDown(length)</code><br/>
      Draw a vertical line starting from the current position and going straight down for
      the given number of cells. The current position is changed to be at the bottom end
    of the line.</p>
    <p><code>drawLineUp(length)</code><br/>
      Draw a vertical line starting from the current position and going straight up for the
      given number of cells. The current position is changed to be at the top end of the
      line.
    </p><p><code>drawLineRight(length)</code><br/>
      Draw a horizontal line starting from the current position and going straight to the
      right for the given number of cells. The current position is changed to be at the right
      end of the line.
    </p><p><code>drawLineLeft(length)</code><br/>
      Draw a horizontal line starting from the current position and going straight to the
      left for the given number of cells. The current position is changed to be at the left
      end of the line.
    </p>
    <p><code>moveRight(d)</code>
      Move the current position d cells to the right.
    </p>
    <p><code>moveLeft(d)</code>
      Move the current position d cells to the left.
    </p>
    <p><code>moveUp(d)</code>
      Move the current position d cells up.
    </p>
    <p><code>moveDown(d)</code>
      Move the current position d cells down.
    </p>
  </section>

   <section>
    <h2>Drawing ideas</h2>
    <p>Try drawing these patterns below!</p>
    <img src="examples.png"/>
  </section>

  <!-- include p5.js library -->
  <script src="./p5.js"></script>

  <!-- include our own scripts library -->
  <script src="./artist.js"></script>
  <script src="./script.js"></script>

</body>
</html>
