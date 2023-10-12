---
title: SlideShowTransition
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/slideshowtransition/
---

## SlideShowTransition class

 Represents slide show transition.
 
| Name | Description |
| --- | --- |
| equals (Object) | Determines whether the two SlideShowTransition instances are equal. Read/write boolean. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| obj | Object | The SlideShowTransition to compare with the current SlideShowTransition. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getAdvanceAfter () | This attribute specifies if the slideshow will move to the next slide after a certain time. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getAdvanceAfterTime () | Specifies the time, in milliseconds, after which the transition should start. This setting may be used in conjunction with the advClick attribute. If this attribute is not specified then it is assumed that no auto-advance will occur. Read/write long. |

### Result
long


---


| Name | Description |
| --- | --- |
| getAdvanceOnClick () | Specifies whether a mouse click will advance the slide or not. If this attribute is not specified then a value of true is assumed. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getSound () | Returns or sets the embedded audio data. Read/write IAudio. |

### Result
Audio(../../audio)


---


| Name | Description |
| --- | --- |
| getSoundIsBuiltIn () | Specifies whether or not this sound is a built-in sound. If this attribute is set to true then the generating application is alerted to check the name attribute specified for this sound in it's list of built-in sounds and can then surface a custom name or UI as needed. Read-write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getSoundLoop () | This attribute specifies if the sound will loop until the next sound event occurs in slideshow. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getSoundMode () | Set or returns sound mode for slide transition. Read/write TransitionSoundMode. |

### Result
int


---


| Name | Description |
| --- | --- |
| getSoundName () | Specifies a human readable name for the sound of the transition. The Sound( #getSound/ #setSound(IAudio)) property must be assigned to get or set the sound name. Read-write String. |

### Result
String

### Error

| Error | Condition |
| --- | --- |
 | PptxException | When {@code Sound}( #getSound/ #setSound(IAudio)) property is not assigned. This name appears in the PowerPoint user interface when configuring the transition sound manually. |


---


| Name | Description |
| --- | --- |
| getSpeed () | Specifies the transition speed that is to be used when transitioning from the current slide to the next. Read/write TransitionSpeed. |

### Result
int


---


| Name | Description |
| --- | --- |
| getType () | Type of transition. Read/write TransitionType. |

### Result
int


---


| Name | Description |
| --- | --- |
| getValue () | Slide show transition value. Read-only ITransitionValueBase. |

### Result
EmptyTransition(../../emptytransition), GlitterTransition(../../glittertransition), OrientationTransition(../../orientationtransition), EightDirectionTransition(../../eightdirectiontransition), RevealTransition(../../revealtransition), WheelTransition(../../wheeltransition), OptionalBlackTransition(../../optionalblacktransition), RippleTransition(../../rippletransition), LeftRightDirectionTransition(../../leftrightdirectiontransition), ShredTransition(../../shredtransition), SideDirectionTransition(../../sidedirectiontransition), InOutTransition(../../inouttransition), CornerDirectionTransition(../../cornerdirectiontransition), MorphTransition(../../morphtransition), FlyThroughTransition(../../flythroughtransition), TransitionValueBase(../../transitionvaluebase), SplitTransition(../../splittransition)


---


| Name | Description |
| --- | --- |
| hashCode () | Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table. |

### Result
int


---


| Name | Description |
| --- | --- |
| setAdvanceAfter (boolean) | This attribute specifies if the slideshow will move to the next slide after a certain time. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setAdvanceAfterTime (long) | Specifies the time, in milliseconds, after which the transition should start. This setting may be used in conjunction with the advClick attribute. If this attribute is not specified then it is assumed that no auto-advance will occur. Read/write long. |


---


| Name | Description |
| --- | --- |
| setAdvanceOnClick (boolean) | Specifies whether a mouse click will advance the slide or not. If this attribute is not specified then a value of true is assumed. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setSound (Audio(../audio)) | Returns or sets the embedded audio data. Read/write IAudio. |


---


| Name | Description |
| --- | --- |
| setSoundIsBuiltIn (boolean) | Specifies whether or not this sound is a built-in sound. If this attribute is set to true then the generating application is alerted to check the name attribute specified for this sound in it's list of built-in sounds and can then surface a custom name or UI as needed. Read-write boolean. |


---


| Name | Description |
| --- | --- |
| setSoundLoop (boolean) | This attribute specifies if the sound will loop until the next sound event occurs in slideshow. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setSoundMode (int) | Set or returns sound mode for slide transition. Read/write TransitionSoundMode. |


---


| Name | Description |
| --- | --- |
| setSoundName (String) | Specifies a human readable name for the sound of the transition. The Sound( #getSound/ #setSound(IAudio)) property must be assigned to get or set the sound name. Read-write String. |

### Error

| Error | Condition |
| --- | --- |
 | PptxException | When {@code Sound}( #getSound/ #setSound(IAudio)) property is not assigned. This name appears in the PowerPoint user interface when configuring the transition sound manually. |


---


| Name | Description |
| --- | --- |
| setSpeed (int) | Specifies the transition speed that is to be used when transitioning from the current slide to the next. Read/write TransitionSpeed. |


---


| Name | Description |
| --- | --- |
| setType (int) | Type of transition. Read/write TransitionType. |


---


