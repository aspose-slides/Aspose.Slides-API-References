---
title: ISlideShowTransition
second_title: Aspose.Slides voor Java API-referentie
description: Stelt diavoorstellingovergang voor.
type: docs
url: /nl/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

Stelt diavoorstellingovergang voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getSound()](#getSound--) | Retourneert of stelt de ingebedde audiogegevens in. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Retourneert of stelt de ingebedde audiogegevens in. |
| [getSoundMode()](#getSoundMode--) | Stelt de geluidsmodus in of retourneert deze voor de diavoorstellingovergang. |
| [setSoundMode(int value)](#setSoundMode-int-) | Stelt de geluidsmodus in of retourneert deze voor de diavoorstellingovergang. |
| [getSoundLoop()](#getSoundLoop--) | Dit attribuut geeft aan of het geluid zal blijven herhalen tot het volgende geluidsevenement optreedt in de diavoorstelling. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Dit attribuut geeft aan of het geluid zal blijven herhalen tot het volgende geluidsevenement optreedt in de diavoorstelling. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Geeft aan of een muisklik de dia zal voortzetten of niet. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Geeft aan of een muisklik de dia zal voortzetten of niet. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Dit attribuut geeft aan of de diavoorstelling naar de volgende dia gaat na een bepaalde tijd. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Dit attribuut geeft aan of de diavoorstelling naar de volgende dia gaat na een bepaalde tijd. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Geeft de tijd in milliseconden op waarna de overgang moet starten. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Geeft de tijd in milliseconden op waarna de overgang moet starten. |
| [getSpeed()](#getSpeed--) | Geeft de overgangssnelheid op die gebruikt moet worden bij het overgaan van de huidige dia naar de volgende. |
| [setSpeed(int value)](#setSpeed-int-) | Geeft de overgangssnelheid op die gebruikt moet worden bij het overgaan van de huidige dia naar de volgende. |
| [getValue()](#getValue--) | Diavoorstelling-overgangswaarde. |
| [getType()](#getType--) | Type overgang. |
| [setType(int value)](#setType-int-) | Type overgang. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Geeft aan of dit geluid een ingebouwd geluid is. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Geeft aan of dit geluid een ingebouwd geluid is. |
| [getSoundName()](#getSoundName--) | Geeft een menselijk leesbare naam voor het geluid van de overgang. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Geeft een menselijk leesbare naam voor het geluid van de overgang. |
| [getDuration()](#getDuration--) | Haalt de duur van het diavoorstelling-overgangseffect op of stelt deze in (in milliseconden). |
| [setDuration(int value)](#setDuration-int-) | Haalt de duur van het diavoorstelling-overgangseffect op of stelt deze in (in milliseconden). |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Retourneert of stelt de ingebedde audiogegevens in. Lezen/schrijven [IAudio](../../com.aspose.slides/iaudio).

**Retour:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Retourneert of stelt de ingebedde audiogegevens in. Lezen/schrijven [IAudio](../../com.aspose.slides/iaudio).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

Stelt de geluidsmodus in of retourneert deze voor de diavoorstellingovergang. Lezen/schrijven [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Retour:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

Stelt de geluidsmodus in of retourneert deze voor de diavoorstellingovergang. Lezen/schrijven [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

Dit attribuut geeft aan of het geluid zal blijven herhalen tot het volgende geluidsevenement optreedt in de diavoorstelling. Lezen/schrijven boolean.

**Retour:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

Dit attribuut geeft aan of het geluid zal blijven herhalen tot het volgende geluidsevenement optreedt in de diavoorstelling. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

Geeft aan of een muisklik de dia zal voortzetten of niet. Als dit attribuut niet is gespecificeerd, wordt een waarde van true aangenomen. Lezen/schrijven boolean.

**Retour:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

Geeft aan of een muisklik de dia zal voortzetten of niet. Als dit attribuut niet is gespecificeerd, wordt een waarde van true aangenomen. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
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
>      // Haal de eerste slide Transition op
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Controleer of de Advance Slide After-vlag is aangevinkt
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Haal de Advance Slide After Time-waarde op
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retour:**
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
>      // Haal de eerste slide Transition op
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Controleer of de Advance Slide After-vlag is aangevinkt
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Haal de Advance Slide After Time-waarde op
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```

Geeft de tijd in milliseconden op waarna de overgang moet starten. Deze instelling kan in combinatie met het advClick-attribuut worden gebruikt. Als dit attribuut niet is gespecificeerd, wordt aangenomen dat er geen automatische voortzetting plaatsvindt. Lezen/schrijven long.

**Retour:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

Geeft de tijd in milliseconden op waarna de overgang moet starten. Deze instelling kan in combinatie met het advClick-attribuut worden gebruikt. Als dit attribuut niet is gespecificeerd, wordt aangenomen dat er geen automatische voortzetting plaatsvindt. Lezen/schrijven long.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |
### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

Geeft de overgangssnelheid op die gebruikt moet worden bij het overgaan van de huidige dia naar de volgende. Lezen/schrijven [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Retour:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

Geeft de overgangssnelheid op die gebruikt moet worden bij het overgaan van de huidige dia naar de volgende. Lezen/schrijven [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

Diavoorstelling-overgangswaarde. Alleen-lezen [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Retour:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```

Type overgang. Lezen/schrijven [TransitionType](../../com.aspose.slides/transitiontype).

**Retour:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Type overgang. Lezen/schrijven [TransitionType](../../com.aspose.slides/transitiontype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

Geeft aan of dit geluid een ingebouwd geluid is. Als dit attribuut op true wordt gezet, wordt de toepassende applicatie gewezen om het name-attribuut van dit geluid in haar lijst met ingebouwde geluiden te controleren en eventueel een aangepaste naam of UI weer te geven. Lezen/schrijven boolean.

**Retour:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

Geeft aan of dit geluid een ingebouwd geluid is. Als dit attribuut op true wordt gezet, wordt de toepassende applicatie gewezen om het name-attribuut van dit geluid in haar lijst met ingebouwde geluiden te controleren en eventueel een aangepaste naam of UI weer te geven. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

Geeft een menselijk leesbare naam voor het geluid van de overgang. De (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) eigenschap moet worden toegewezen om de geluidsnaam op te halen of in te stellen. Lezen/schrijven String.

**Retour:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

Geeft een menselijk leesbare naam voor het geluid van de overgang. De \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) eigenschap moet worden toegewezen om de geluidsnaam op te halen of in te stellen. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

Haalt de duur van het diavoorstelling-overgangseffect op of stelt deze in (in milliseconden). Lezen/schrijven int.

--------------------

Komt overeen met het attribuut p14:dur van het p:transition-element in het PresentationML-schema. Indien niet ingesteld, wordt de duur automatisch bepaald op basis van de \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) eigenschap en het type overgang.

**Retour:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

Haalt de duur van het diavoorstelling-overgangseffect op of stelt deze in (in milliseconden). Lezen/schrijven int.

--------------------

Komt overeen met het attribuut p14:dur van het p:transition-element in het PresentationML-schema. Indien niet ingesteld, wordt de duur automatisch bepaald op basis van de \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) eigenschap en het type overgang.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |