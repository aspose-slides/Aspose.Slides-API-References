---
title: SlideShowTransition
type: docs
weight: 0
url: /php-java/slideshowtransition/
---

# SlideShowTransition class

 Represents slide show transition.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [equals](/php-java/slideshowtransition/equals/)(Object) | boolean | Determines whether the two SlideShowTransition instances are equal. Read/write boolean. |
| [getAdvanceAfterTime](/php-java/slideshowtransition/getadvanceaftertime/)() | long | Specifies the time, in milliseconds, after which the transition should start. This setting may be used in conjunction with the advClick attribute. If this attribute is not specified then it is assumed that no auto-advance will occur. Read/write long. |
| [getAdvanceOnClick](/php-java/slideshowtransition/getadvanceonclick/)() | boolean | Specifies whether a mouse click will advance the slide or not. If this attribute is not specified then a value of true is assumed. Read/write boolean. |
| [getSound](/php-java/slideshowtransition/getsound/)() | IAudio | Returns or sets the embedded audio data. Read/write IAudio. |
| [getSoundIsBuiltIn](/php-java/slideshowtransition/getsoundisbuiltin/)() | boolean | Specifies whether or not this sound is a built-in sound. If this attribute is set to true then the generating application is alerted to check the name attribute specified for this sound in it's list of built-in sounds and can then surface a custom name or UI as needed. Read-write boolean. |
| [getSoundLoop](/php-java/slideshowtransition/getsoundloop/)() | boolean | This attribute specifies if the sound will loop until the next sound event occurs in slideshow. Read/write boolean. |
| [getSoundMode](/php-java/slideshowtransition/getsoundmode/)() | int | Set or returns sound mode for slide transition. Read/write TransitionSoundMode. |
| [getSoundName](/php-java/slideshowtransition/getsoundname/)() | String | Specifies a human readable name for the sound of the transition. The ( #getSound/ #setSound(IAudio)) property must be assigned to get or set the sound name. Read-write String. |
| [getSpeed](/php-java/slideshowtransition/getspeed/)() | int | Specifies the transition speed that is to be used when transitioning from the current slide to the next. Read/write TransitionSpeed. |
| [getType](/php-java/slideshowtransition/gettype/)() | int | Type of transition. Read/write TransitionType. |
| [getValue](/php-java/slideshowtransition/getvalue/)() | ITransitionValueBase | Slide show transition value. Read-only ITransitionValueBase. |
| [hashCode](/php-java/slideshowtransition/hashcode/)() | int | Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table. |
| [setAdvanceAfterTime](/php-java/slideshowtransition/setadvanceaftertime/)(long) | void | Specifies the time, in milliseconds, after which the transition should start. This setting may be used in conjunction with the advClick attribute. If this attribute is not specified then it is assumed that no auto-advance will occur. Read/write long. |
| [setAdvanceOnClick](/php-java/slideshowtransition/setadvanceonclick/)(boolean) | void | Specifies whether a mouse click will advance the slide or not. If this attribute is not specified then a value of true is assumed. Read/write boolean. |
| [setSound](/php-java/slideshowtransition/setsound/)(IAudio) | void | Returns or sets the embedded audio data. Read/write IAudio. |
| [setSoundIsBuiltIn](/php-java/slideshowtransition/setsoundisbuiltin/)(boolean) | void | Specifies whether or not this sound is a built-in sound. If this attribute is set to true then the generating application is alerted to check the name attribute specified for this sound in it's list of built-in sounds and can then surface a custom name or UI as needed. Read-write boolean. |
| [setSoundLoop](/php-java/slideshowtransition/setsoundloop/)(boolean) | void | This attribute specifies if the sound will loop until the next sound event occurs in slideshow. Read/write boolean. |
| [setSoundMode](/php-java/slideshowtransition/setsoundmode/)(int) | void | Set or returns sound mode for slide transition. Read/write TransitionSoundMode. |
| [setSoundName](/php-java/slideshowtransition/setsoundname/)(String) | void | Specifies a human readable name for the sound of the transition. The ( #getSound/ #setSound(IAudio)) property must be assigned to get or set the sound name. Read-write String. |
| [setSpeed](/php-java/slideshowtransition/setspeed/)(int) | void | Specifies the transition speed that is to be used when transitioning from the current slide to the next. Read/write TransitionSpeed. |
| [setType](/php-java/slideshowtransition/settype/)(int) | void | Type of transition. Read/write TransitionType. |
