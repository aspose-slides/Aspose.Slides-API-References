---
title: SlideShowTransition
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/slideshowtransition/
---

## SlideShowTransition class

 Represents slide show transition.
 

## Methods

| Name | Description |
| --- | --- |
| [equals](equals)(Object) | Determines whether the two SlideShowTransition instances are equal. Read/write boolean. |
| [getAdvanceAfterTime](getadvanceaftertime)() | Specifies the time, in milliseconds, after which the transition should start. This setting may be used in conjunction with the advClick attribute. If this attribute is not specified then it is assumed that no auto-advance will occur. Read/write long. |
| [getAdvanceOnClick](getadvanceonclick)() | Specifies whether a mouse click will advance the slide or not. If this attribute is not specified then a value of true is assumed. Read/write boolean. |
| [getSound](getsound)() | Returns or sets the embedded audio data. Read/write IAudio. |
| [getSoundIsBuiltIn](getsoundisbuiltin)() | Specifies whether or not this sound is a built-in sound. If this attribute is set to true then the generating application is alerted to check the name attribute specified for this sound in it's list of built-in sounds and can then surface a custom name or UI as needed. Read-write boolean. |
| [getSoundLoop](getsoundloop)() | This attribute specifies if the sound will loop until the next sound event occurs in slideshow. Read/write boolean. |
| [getSoundMode](getsoundmode)() | Set or returns sound mode for slide transition. Read/write TransitionSoundMode. |
| [getSoundName](getsoundname)() | Specifies a human readable name for the sound of the transition. The ( #getSound/ #setSound(IAudio)) property must be assigned to get or set the sound name. Read-write String. |
| [getSpeed](getspeed)() | Specifies the transition speed that is to be used when transitioning from the current slide to the next. Read/write TransitionSpeed. |
| [getType](gettype)() | Type of transition. Read/write TransitionType. |
| [getValue](getvalue)() | Slide show transition value. Read-only ITransitionValueBase. |
| [hashCode](hashcode)() | Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table. |
| [setAdvanceAfterTime](setadvanceaftertime)(long) | Specifies the time, in milliseconds, after which the transition should start. This setting may be used in conjunction with the advClick attribute. If this attribute is not specified then it is assumed that no auto-advance will occur. Read/write long. |
| [setAdvanceOnClick](setadvanceonclick)(boolean) | Specifies whether a mouse click will advance the slide or not. If this attribute is not specified then a value of true is assumed. Read/write boolean. |
| [setSound](setsound)(IAudio) | Returns or sets the embedded audio data. Read/write IAudio. |
| [setSoundIsBuiltIn](setsoundisbuiltin)(boolean) | Specifies whether or not this sound is a built-in sound. If this attribute is set to true then the generating application is alerted to check the name attribute specified for this sound in it's list of built-in sounds and can then surface a custom name or UI as needed. Read-write boolean. |
| [setSoundLoop](setsoundloop)(boolean) | This attribute specifies if the sound will loop until the next sound event occurs in slideshow. Read/write boolean. |
| [setSoundMode](setsoundmode)(int) | Set or returns sound mode for slide transition. Read/write TransitionSoundMode. |
| [setSoundName](setsoundname)(String) | Specifies a human readable name for the sound of the transition. The ( #getSound/ #setSound(IAudio)) property must be assigned to get or set the sound name. Read-write String. |
| [setSpeed](setspeed)(int) | Specifies the transition speed that is to be used when transitioning from the current slide to the next. Read/write TransitionSpeed. |
| [setType](settype)(int) | Type of transition. Read/write TransitionType. |
