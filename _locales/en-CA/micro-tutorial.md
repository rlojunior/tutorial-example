# Micro Tutorial

## Step 1
Click the *Input* section below and then drag the block *on button A pressed*.     
Drop it on the main area (it is the big light blue area).

```blocks
input.onButtonPressed(Button.A, function () {
    
})
```

## Step 2
Click the *Led* section and then drag the block *toggle*.      
Drop it inside the block *on button A pressed*    
If the computer speaker is on you will hear a click sound !

```blocks
input.onButtonPressed(Button.A, function () {
    led.toggle(0, 0)
})
```

## Step 3
On *toggle* block change the value of x and y to 1 and 3 respectively.

```blocks
input.onButtonPressed(Button.A, function () {
    led.toggle(1, 3)
})
```

## Step 4
Press the button A on the Micro:bit board.    
You should see a led turning on.    
If you press the button A again, the led shuld turn off.  
