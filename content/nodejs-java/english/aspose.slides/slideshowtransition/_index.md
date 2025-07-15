---
title: SlideShowTransition
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/slideshowtransition/
---

## SlideShowTransition class

 Represents slide show transition.
 
### equals {#equals}

| Name | Description |
| --- | --- |
| equals (Object) | Determines whether the two SlideShowTransition instances are equal. Read/write boolean. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| obj | Object | The SlideShowTransition to compare with the current SlideShowTransition. |

 **Returns:**
boolean


---


### getAdvanceAfter {#getAdvanceAfter}

| Name | Description |
| --- | --- |
| getAdvanceAfter () | This attribute specifies if the slideshow will move to the next slide after a certain time. Read/write boolean. |

 **Returns:**
boolean


---


### getAdvanceAfterTime {#getAdvanceAfterTime}

| Name | Description |
| --- | --- |
| getAdvanceAfterTime () | Specifies the time, in milliseconds, after which the transition should start. This setting may be used in conjunction with the advClick attribute. If this attribute is not specified then it is assumed that no auto-advance will occur. Read/write long. |

 **Returns:**
long


---


### getAdvanceOnClick {#getAdvanceOnClick}

| Name | Description |
| --- | --- |
| getAdvanceOnClick () | Specifies whether a mouse click will advance the slide or not. If this attribute is not specified then a value of true is assumed. Read/write boolean. |

 **Returns:**
boolean


---


### getSound {#getSound}

| Name | Description |
| --- | --- |
| getSound () | Returns or sets the embedded audio data. Read/write IAudio. |

 **Returns:**
[Audio](../audio)


---


### getSoundIsBuiltIn {#getSoundIsBuiltIn}

| Name | Description |
| --- | --- |
| getSoundIsBuiltIn () | Specifies whether or not this sound is a built-in sound. If this attribute is set to true then the generating application is alerted to check the name attribute specified for this sound in it's list of built-in sounds and can then surface a custom name or UI as needed. Read-write boolean. |

 **Returns:**
boolean


---


### getSoundLoop {#getSoundLoop}

| Name | Description |
| --- | --- |
| getSoundLoop () | This attribute specifies if the sound will loop until the next sound event occurs in slideshow. Read/write boolean. |

 **Returns:**
boolean


---


### getSoundMode {#getSoundMode}

| Name | Description |
| --- | --- |
| getSoundMode () | Set or returns sound mode for slide transition. Read/write TransitionSoundMode. |

 **Returns:**
int


---


### getSoundName {#getSoundName}

| Name | Description |
| --- | --- |
| getSoundName () | Specifies a human readable name for the sound of the transition. The Sound( #getSound/ #setSound(IAudio)) property must be assigned to get or set the sound name. Read-write String. |

 **Returns:**
String

 **Error**

| Error | Condition |
| --- | --- |
 | PptxException | When {@code Sound}( #getSound/ #setSound(IAudio)) property is not assigned. This name appears in the PowerPoint user interface when configuring the transition sound manually. |


---


### getSpeed {#getSpeed}

| Name | Description |
| --- | --- |
| getSpeed () | Specifies the transition speed that is to be used when transitioning from the current slide to the next. Read/write TransitionSpeed. |

 **Returns:**
int


---


### getType {#getType}

| Name | Description |
| --- | --- |
| getType () | Type of transition. Read/write TransitionType. |

 **Returns:**
int


---


### getValue {#getValue}

| Name | Description |
| --- | --- |
| getValue () | Slide show transition value. Read-only ITransitionValueBase. |

 **Returns:**
[CornerDirectionTransition](../cornerdirectiontransition), [GlitterTransition](../glittertransition), [TransitionValueBase](../transitionvaluebase), [WheelTransition](../wheeltransition), [InOutTransition](../inouttransition), [MorphTransition](../morphtransition), [RevealTransition](../revealtransition), [ShredTransition](../shredtransition), [RippleTransition](../rippletransition), [EightDirectionTransition](../eightdirectiontransition), [SideDirectionTransition](../sidedirectiontransition), [EmptyTransition](../emptytransition), [LeftRightDirectionTransition](../leftrightdirectiontransition), [OptionalBlackTransition](../optionalblacktransition), [FlyThroughTransition](../flythroughtransition), [OrientationTransition](../orientationtransition), [SplitTransition](../splittransition)


---


### hashCode {#hashCode}

| Name | Description |
| --- | --- |
| hashCode () | Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table. |

 **Returns:**
int


---


### setAdvanceAfter {#setAdvanceAfter}

| Name | Description |
| --- | --- |
| setAdvanceAfter (boolean) | This attribute specifies if the slideshow will move to the next slide after a certain time. Read/write boolean. |


---


### setAdvanceAfterTime {#setAdvanceAfterTime}

| Name | Description |
| --- | --- |
| setAdvanceAfterTime (long) | Specifies the time, in milliseconds, after which the transition should start. This setting may be used in conjunction with the advClick attribute. If this attribute is not specified then it is assumed that no auto-advance will occur. Read/write long. |


---


### setAdvanceOnClick {#setAdvanceOnClick}

| Name | Description |
| --- | --- |
| setAdvanceOnClick (boolean) | Specifies whether a mouse click will advance the slide or not. If this attribute is not specified then a value of true is assumed. Read/write boolean. |


---


### setSound {#setSound}

| Name | Description |
| --- | --- |
| setSound ([Audio](../audio)) | Returns or sets the embedded audio data. Read/write IAudio. |


---


### setSoundIsBuiltIn {#setSoundIsBuiltIn}

| Name | Description |
| --- | --- |
| setSoundIsBuiltIn (boolean) | Specifies whether or not this sound is a built-in sound. If this attribute is set to true then the generating application is alerted to check the name attribute specified for this sound in it's list of built-in sounds and can then surface a custom name or UI as needed. Read-write boolean. |


---


### setSoundLoop {#setSoundLoop}

| Name | Description |
| --- | --- |
| setSoundLoop (boolean) | This attribute specifies if the sound will loop until the next sound event occurs in slideshow. Read/write boolean. |


---


### setSoundMode {#setSoundMode}

| Name | Description |
| --- | --- |
| setSoundMode (int) | Set or returns sound mode for slide transition. Read/write TransitionSoundMode. |


---


### setSoundName {#setSoundName}

| Name | Description |
| --- | --- |
| setSoundName (String) | Specifies a human readable name for the sound of the transition. The Sound( #getSound/ #setSound(IAudio)) property must be assigned to get or set the sound name. Read-write String. |

 **Error**

| Error | Condition |
| --- | --- |
 | PptxException | When {@code Sound}( #getSound/ #setSound(IAudio)) property is not assigned. This name appears in the PowerPoint user interface when configuring the transition sound manually. |


---


### setSpeed {#setSpeed}

| Name | Description |
| --- | --- |
| setSpeed (int) | Specifies the transition speed that is to be used when transitioning from the current slide to the next. Read/write TransitionSpeed. |


---


### setType {#setType}

| Name | Description |
| --- | --- |
| setType (int) | Type of transition. Read/write TransitionType. |


---


