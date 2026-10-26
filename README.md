# MG4
## Devlog
Firstly, the Start() method set the _timer to _switchSpeed when the game starts. Then, the Update() method runs every frame and checks whether _up is true or false to decide whether the food moves up and down along the y-axis by _moveSpeed * Time.deltaTime or -_moveSpeed * Time.deltaTime.
And _timer -= Time.deltaTime lets the _timer count down. When the _time reaches zero, it resets to _switchSpeed and changes _up to the opposite value by using _up = !_up. It makes the food switch between up and down.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)