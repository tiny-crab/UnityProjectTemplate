# UnityProjectTemplate
My template for starting a new game. Steps:

## Create package to import into a new project
1. Clone this repo
2. Open repo in Unity
3. Select Assets -> Export Package
4. Select all Assets except for Scenes
5. Follow export process, and keep an eye on where your .unitypackage is exported.

## Import package assets into new project
1. Create a new Unity project
2. Select Assets -> Import Package
3. Select .unitypackage file generated from last step
4. Follow import process, making sure the Scenes folder is not included.


# What's included

### [UniRx](https://github.com/neuecc/UniRx)
Reactive programming paradigm.

### [LINQ to GameObject](https://github.com/neuecc/LINQ-to-GameObject-for-Unity#:~:text=LINQ%20to%20GameObject%20is%20GameObject,LINQ%20and%20performance%20of%20iteration.)
Helper function library to navigate GameObject hierarchy much more easily.

### [DOTween](http://dotween.demigiant.com/)
Tweener library for mapping values to change curves over time.

### SolarizedSprites
A small 32x32 sprite pack that I put together using the [Solarized Dark](https://ethanschoonover.com/solarized/) palette. Includes a txt file with HEX codes (and other values) for the colors in question.
