## Create a background

This project contains code to draw the sky as a blue rectangle.

➡️ Remove the black border from the background.

### Step 1
The border of a shape is called the **stroke**.

Click the run button, and you should see a blue rectangle with a black border. 

### Step 2
Add `no_stroke()`{:.language-python} to the `setup`{:.language-python} function to turn the stroke off for all shapes. 

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 13
line_highlights: 16
---
def setup():
# Set up your game here
    size(400, 400)  # width and height of screen
    no_stroke()

--- /code ---

</div>

### Now run your code

Did you notice that the border (stroke) has now disappeared?

![image of a blue rectangle](images/sky.png)


<div class="c-project-output">
<iframe src="https://editor.raspberrypi.org/en/embed/viewer/editor-turtle-snowflakes-complete" width="600" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>


> ### Tip
> 
> Coordinates start from (x=0, y=0) in the top left-hand corner. This might be different to other coordinate systems you have used.
>
>If you see an alert "Execution interrupted" when you click stop on your program, don't be concerned. This just means the normal flow of the program was stopped.
{: .c-project-callout .c-project-callout--tip}
