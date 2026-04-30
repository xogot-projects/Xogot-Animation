# Animations in Xogot (Xogot 3D Tutorial)

This project contains the example scenes and assets used in the  
**Xogot 3D Modular Series - Animations** tutorial by **Erin Uptegrove**.

It demonstrates how to create and control animations in **Xogot** - the iPad and iPhone port
of the Godot Engine - using AnimationPlayer, animation tracks, keyframes, imported model
animations, and simple script-driven playback.

The project includes practical examples of animating a moving platform directly in Xogot and
using imported character animations such as idle, walk, and jump.

---

## Features

* Create an **AnimationPlayer** directly in Xogot
* Add and name new animations
* Use the Animation panel and timeline
* Add animation tracks for 3D transforms
* Keyframe position changes for a moving platform
* Use the Inspector to set animation keys
* Configure looping animations
* Enable autoplay for an animation
* Work with animations imported from an FBX model
* Use **Editable Children** to access an imported model’s AnimationPlayer
* Switch between imported animation actions
* Play idle, walk, and jump animations from script

---

## Notes

This project focuses on **introductory 3D animation workflows** in Xogot, not advanced animation
systems or character controllers.

Key ideas demonstrated include:

* Animations can be created directly in Xogot or imported as part of a model
* AnimationPlayer controls the playback of animations in a scene
* Tracks define what an animation changes over time
* 3D transform tracks can animate position, rotation, or scale
* Looping and autoplay are useful for repeated environmental motion
* Imported model animations can be accessed and controlled through the model’s AnimationPlayer
* Scripts can switch between animations using `AnimationPlayer.play()`

---

## Video Tutorial

Watch the full walkthrough on the [Xogot YouTube Channel](https://youtube.com/@xogot):

**Introduction to Animation in Xogot - Game Development in Godot on iPad**  
https://youtu.be/BM93PgWJmKk

---

## How to Use

1. Download or clone this repository:

   ```bash
   git clone https://github.com/xogot-projects/Xogot-Animation.git

2. Open the project in [Xogot](https://apps.apple.com/us/app/xogot-make-games-anywhere/id6469385251) on iPad or iPhone.

3. Explore the example scenes

4. Preview the project and test the Area3D trigger behavior

5. Review the AnimationPlayer setup, animation tracks, and scripts used to control playback

## Learn More

[Xogot](https://xogot.com)
[Documentation:](https://docs.xogot.com/documentation/xogot/)
[Tutorials](https://docs.xogot.com/tutorials/xogot-tutorials/)

Built with Xogot on iPad