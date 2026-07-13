---
title: ISlideShowTransition
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt diavoorstelling-overgang voor.
type: docs
url: /nl/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

Stelt diavoorstelling-overgang voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getSound()](#getSound--) | Returns or sets the embedded audio data. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Returns or sets the embedded audio data. |
| [getSoundMode()](#getSoundMode--) | Set or returns sound mode for slide transition. |
| [setSoundMode(int value)](#setSoundMode-int-) | Set or returns sound mode for slide transition. |
| [getSoundLoop()](#getSoundLoop--) | This attribute specifies if the sound will loop until the next sound event occurs in slideshow. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | This attribute specifies if the sound will loop until the next sound event occurs in slideshow. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Specifies whether a mouse click will advance the slide or not. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Specifies whether a mouse click will advance the slide or not. |
| [getAdvanceAfter()](#getAdvanceAfter--) | This attribute specifies if the slideshow will move to the next slide after a certain time. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | This attribute specifies if the slideshow will move to the next slide after a certain time. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Specifies the time, in milliseconds, after which the transition should start. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Specifies the time, in milliseconds, after which the transition should start. |
| [getSpeed()](#getSpeed--) | Specifies the transition speed that is to be used when transitioning from the current slide to the next. |
| [setSpeed(int value)](#setSpeed-int-) | Specifies the transition speed that is to be used when transitioning from the current slide to the next. |
| [getValue()](#getValue--) | Slide show transition value. |
| [getType()](#getType--) | Type of transition. |
| [setType(int value)](#setType-int-) | Type of transition. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Specifies whether or not this sound is a built-in sound. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Specifies whether or not this sound is a built-in sound. |
| [getSoundName()](#getSoundName--) | Specifies a human readable name for the sound of the transition. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Specifies a human readable name for the sound of the transition. |
| [getDuration()](#getDuration--) | Gets or sets the duration of the slide transition effect in milliseconds. |
| [setDuration(int value)](#setDuration-int-) | Gets or sets the duration of the slide transition effect in milliseconds. |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Geeft de ingebedde audiogegevens terug of stelt ze in. Lezen-schrijven [IAudio](../../com.aspose.slides/iaudio).

**Returns:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Geeft de ingebedde audiogegevens terug of stelt ze in. Lezen-schrijven [IAudio](../../com.aspose.slides/iaudio).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

Stelt de geluidsmodus voor de dia-overgang in of geeft deze terug. Lezen-schrijven [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Returns:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

Stelt de geluidsmodus voor de dia-overgang in of geeft deze terug. Lezen-schrijven [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

Dit attribuut geeft aan of het geluid herhaalt tot het volgende geluidsevenement zich voordoet in de diavoorstelling. Lezen-schrijven boolean.

**Returns:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

Dit attribuut geeft aan of het geluid herhaalt tot het volgende geluidsevenement zich voordoet in de diavoorstelling. Lezen-schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

Geeft aan of een muisklik de dia vooruit beweegt of niet. Als dit attribuut niet is opgegeven, wordt een waarde van true aangenomen. Lezen-schrijven boolean.

**Returns:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

Geeft aan of een muisklik de dia vooruit beweegt of niet. Als dit attribuut niet is opgegeven, wordt een waarde van true aangenomen. Lezen-schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

Dit attribuut geeft aan of de diavoorstelling naar de volgende dia gaat na een bepaalde tijd. Lezen/schrijven boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Haal de eerste dia-overgang op
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Controleer of de vlag 'Advance Slide After' is aangevinkt
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Haal de waarde van 'Advance Slide After Time' op
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```

Dit attribuut geeft aan of de diavoorstelling naar de volgende dia gaat na een bepaalde tijd. Lezen/schrijven boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Haal de eerste dia overgang op
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Controleer of de vlag Advance Slide After is aangevinkt
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Haal de waarde van Advance Slide After Time op
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```

Geeft de tijd, in milliseconden, waarna de overgang moet beginnen. Deze instelling kan samen met het advClick-attribuut worden gebruikt. Als dit attribuut niet is opgegeven, wordt aangenomen dat er geen automatische vooruitgang plaatsvindt. Lezen-schrijven long.

**Returns:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

Geeft de tijd, in milliseconden, waarna de overgang moet beginnen. Deze instelling kan samen met het advClick-attribuut worden gebruikt. Als dit attribuut niet is opgegeven, wordt aangenomen dat er geen automatische vooruitgang plaatsvindt. Lezen-schrijven long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

Geeft de overgangssnelheid die moet worden gebruikt bij het overgaan van de huidige dia naar de volgende. Lezen-schrijven [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Returns:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

Geeft de overgangssnelheid die moet worden gebruikt bij het overgaan van de huidige dia naar de volgende. Lezen-schrijven [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

Diavoorstelling-overgangswaarde. Alleen-lezen [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Returns:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```

Type overgang. Lezen-schrijven [TransitionType](../../com.aspose.slides/transitiontype).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Type overgang. Lezen-schrijven [TransitionType](../../com.aspose.slides/transitiontype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

Geeft aan of dit geluid een ingebouwd geluid is. Als dit attribuut op true staat, wordt de genererende toepassing geadviseerd de naam-attribuut van dit geluid in de lijst met ingebouwde geluiden te controleren en vervolgens een aangepaste naam of UI weer te geven indien nodig. Lezen-schrijven boolean.

**Returns:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

Geeft aan of dit geluid een ingebouwd geluid is. Als dit attribuut op true staat, wordt de genererende toepassing geadviseerd de naam-attribuut van dit geluid in de lijst met ingebouwde geluiden te controleren en vervolgens een aangepaste naam of UI weer te geven indien nodig. Lezen-schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

Geeft een menselijk leesbare naam voor het geluid van de overgang. De (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio))-eigenschap moet worden toegewezen om de geluidsnaam te verkrijgen of in te stellen. Lezen-schrijven String.

**Returns:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

Geeft een menselijk leesbare naam voor het geluid van de overgang. De \#getSound.getSound/\#setSound(IAudio).setSound(IAudio)-eigenschap moet worden toegewezen om de geluidsnaam te verkrijgen of in te stellen. Lezen-schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

Haalt de duur van het dia-overgangseffect op of stelt deze in in milliseconden. Lezen/schrijven int.

--------------------

Komt overeen met het p14:dur-attribuut van het p:transition-element in het PresentationML-schema. Als het niet is ingesteld, wordt de duur automatisch bepaald op basis van de \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int)-eigenschap en het overgangstype.

**Returns:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

Stelt de duur van het dia-overgangseffect in of haalt deze op in milliseconden. Lezen/schrijven int.

--------------------

Komt overeen met het p14:dur-attribuut van het p:transition-element in het PresentationML-schema. Als het niet is ingesteld, wordt de duur automatisch bepaald op basis van de \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int)-eigenschap en het overgangstype.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |