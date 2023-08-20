# Corne Snap&Rest

Corne Snap&Rest is a 3D-printed case and magnetic wristrest for the [Corne
keyboard (crkbd)](https://github.com/foostan/crkbd).

![](images/cover_photo.png)

You can see the case in a [video on YouTube](https://youtu.be/yxpXOWdBqow)

## Models

All 3D printed models are in the `models` directory. The filename is in the
format `<part>_<side>_x<count>.stl` where count defines how many times you need
to print this part.

**Full assembly of the Corne Snap&Rest**

![Corne Snap&Rest (Full Assembly)](images/assembly.png)

## Print

All models were printed from **PLA** except `wristrest_pad_left_x1.stl`,
`wristrest_pad_right_x1.stl` and `rubber_x16.stl`. These were printed from the
**TPE** material with hardness of **88A** (I was using
[FilamentPM RubberJet](https://shop.filament-pm.com/tpe-88-rubberjet-flex-black-1-75-mm-0-5-kg/p97))

There is nothing special about print settings for these models except for
`wristrest_pad_left_x1.stl` and `wristrest_pad_right_x1.stl`. These were printed
with following settings:
 - Infill: **10%**
 - Infill pattern: **Gyroid**
 - Perimetr: **2**
 - Top layers: **5**
 - Bottom layers: **5**

 You can change the infill percentage and number of top/bottom layers to make
 pads softer or harder to your taste.

## Assembly and BOM

To assembly this case you will need only:
 - printed parts
 - glue for plastics
 - **20x** 6x3mm round neodymium magnet (5 pcs on each part)

All printed parts from TPE are glued on. The orientation of `rubber_x16.stl`
doesn't matter, but `wristrest_pad_left_x1.stl` and `wristrest_pad_right_x1.stl`
have one side more rounded for hand comfort. This side has to be up.

Magnets are also glued on. It is a little bit tricky to glue magnets from the
bottom hole of the wristrest. You can use a skewer or some thin stick to apply
glue to holes for magnets.

**Make sure twice that the magnets are correctly oriented! Wristrest and Case
should attract each other with magnets.**

## Photos

![Full keyboard](images/full_keyboard.jpg)
![Keyboard in case](images/keyboard_in_case.jpg)
![Magnets in wristres](images/wristrest_bottom.jpg)
![Left case with wristrest](images/left_case_with_wristrest.jpg)
![Bottom left case with wristrest](images/bottom_left_case_with_wristrest.jpg)
