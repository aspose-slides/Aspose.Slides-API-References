---
title: SlideShowTransition
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt diavoorstellingsovergang.
type: docs
url: /nl/com.aspose.slides/slideshowtransition/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

Stelt een diavoorstellingsovergang voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getSound()](#getSound--) | Geeft de ingebedde audiogegevens terug of stelt ze in. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Geeft de ingebedde audiogegevens terug of stelt ze in. |
| [getSoundMode()](#getSoundMode--) | Stelt de geluidsmodus voor de diavoorstellingsovergang in of geeft deze terug. |
| [setSoundMode(int value)](#setSoundMode-int-) | Stelt de geluidsmodus voor de diavoorstellingsovergang in of geeft deze terug. |
| [getSoundLoop()](#getSoundLoop--) | Dit attribuut geeft aan of het geluid blijft herhalen totdat het volgende geluidsevenement zich voordoet in de diavoorstelling. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Dit attribuut geeft aan of het geluid blijft herhalen totdat het volgende geluidsevenement zich voordoet in de diavoorstelling. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Geeft aan of een muisklik de dia zal voortzetten of niet. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Geeft aan of een muisklik de dia zal voortzetten of niet. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Dit attribuut geeft aan of de diavoorstelling naar de volgende dia gaat na een bepaalde tijd. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Dit attribuut geeft aan of de diavoorstelling naar de volgende dia gaat na een bepaalde tijd. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Geeft de tijd, in milliseconden, aan waarna de overgang moet starten. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Geeft de tijd, in milliseconden, aan waarna de overgang moet starten. |
| [getSpeed()](#getSpeed--) | Geeft de overgangssnelheid op die moet worden gebruikt bij het overgaan van de huidige dia naar de volgende. |
| [setSpeed(int value)](#setSpeed-int-) | Geeft de overgangssnelheid op die moet worden gebruikt bij het overgaan van de huidige dia naar de volgende. |
| [getValue()](#getValue--) | Waarde van de diavoorstellingsovergang. |
| [getType()](#getType--) | Type overgang. |
| [setType(int value)](#setType-int-) | Type overgang. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Geef aan of dit geluid een ingebouwd geluid is. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Geef aan of dit geluid een ingebouwd geluid is. |
| [getSoundName()](#getSoundName--) | Geeft een menselijk leesbare naam voor het geluid van de overgang. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Geeft een menselijk leesbare naam voor het geluid van de overgang. |
| [getDuration()](#getDuration--) | Geeft of stelt de duur van het diavoorstellingsovergangseffect in milliseconden. |
| [setDuration(int value)](#setDuration-int-) | Geeft of stelt de duur van het diavoorstellingsovergangseffect in milliseconden. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de twee SlideShowTransition-instanties gelijk zijn. |
| [hashCode()](#hashCode--) | Dient als een hash-functie voor een bepaald type, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hashtabel. |
### getSound() {#getSound--}
```
public final IAudio getSound()
```

Geeft de ingebedde audiogegevens terug of stelt ze in. Lezen/Schrijven [IAudio](../../com.aspose.slides/iaudio).

**Retourneert:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Geeft de ingebedde audiogegevens terug of stelt ze in. Lezen/Schrijven [IAudio](../../com.aspose.slides/iaudio).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

Stelt de geluidsmodus voor de diavoorstellingsovergang in of geeft deze terug. Lezen/Schrijven [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Retourneert:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

Stelt de geluidsmodus voor de diavoorstellingsovergang in of geeft deze terug. Lezen/Schrijven [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

Dit attribuut geeft aan of het geluid blijft herhalen totdat het volgende geluidsevenement zich voordoet in de diavoorstelling. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Dit attribuut geeft aan of het geluid blijft herhalen totdat het volgende geluidsevenement zich voordoet in de diavoorstelling. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Geeft aan of een muisklik de dia zal voortzetten of niet. Als dit attribuut niet is gespecificeerd wordt een waarde van true verondersteld. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Geeft aan of een muisklik de dia zal voortzetten of niet. Als dit attribuut niet is gespecificeerd wordt een waarde van true verondersteld. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

Dit attribuut geeft aan of de diavoorstelling naar de volgende dia gaat na een bepaalde tijd. Lezen/Schrijven boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Haal de eerste diaovergang op
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Controleer of de vlag Advance Slide After is aangevinkt
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Haal de Advance Slide After Time-waarde op
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public final void setAdvanceAfter(boolean value)
```

Dit attribuut geeft aan of de diavoorstelling naar de volgende dia gaat na een bepaalde tijd. Lezen/Schrijven boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Haal de eerste diaovergang op
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Controleer of de vlag Advance Slide After is aangevinkt
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
public final long getAdvanceAfterTime()
```

Geeft de tijd, in milliseconden, aan waarna de overgang moet starten. Deze instelling kan samen met het advClick-attribuut worden gebruikt. Als dit attribuut niet is gespecificeerd wordt aangenomen dat er geen automatische voortzetting plaatsvindt. Lezen/Schrijven long.

**Retourneert:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Geeft de tijd, in milliseconden, aan waarna de overgang moet starten. Deze instelling kan samen met het advClick-attribuut worden gebruikt. Als dit attribuut niet is gespecificeerd wordt aangenomen dat er geen automatische voortzetting plaatsvindt. Lezen/Schrijven long.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |
### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Geeft de overgangssnelheid op die moet worden gebruikt bij het overgaan van de huidige dia naar de volgende. Lezen/Schrijven [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Retourneert:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Geeft de overgangssnelheid op die moet worden gebruikt bij het overgaan van de huidige dia naar de volgende. Lezen/Schrijven [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

Waarde van de diavoorstellingsovergang. Alleen-lezen [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Retourneert:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public final int getType()
```

Type overgang. Lezen/Schrijven [TransitionType](../../com.aspose.slides/transitiontype).

**Retourneert:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Type overgang. Lezen/Schrijven [TransitionType](../../com.aspose.slides/transitiontype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

Geef aan of dit geluid een ingebouwd geluid is. Als dit attribuut op true wordt gezet, wordt de genererende applicatie geïnformeerd om het name-attribuut van dit geluid in de lijst met ingebouwde geluiden te controleren en eventueel een aangepaste naam of UI te tonen. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Geef aan of dit geluid een ingebouwd geluid is. Als dit attribuut op true wordt gezet, wordt de genererende applicatie geïnformeerd om het name-attribuut van dit geluid in de lijst met ingebouwde geluiden te controleren en eventueel een aangepaste naam of UI te tonen. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Geeft een menselijk leesbare naam voor het geluid van de overgang. De eigenschap Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) moet worden toegewezen om de geluidsnaam op te halen of in te stellen. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Geeft een menselijk leesbare naam voor het geluid van de overgang. De eigenschap Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) moet worden toegewezen om de geluidsnaam op te halen of in te stellen. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getDuration() {#getDuration--}
```
public final int getDuration()
```

Geeft of stelt de duur van het diavoorstellingsovergangseffect in milliseconden. Lezen/Schrijven int.

--------------------

Komt overeen met het p14:dur-attribuut van het p:transition-element in het PresentationML-schema. Indien niet ingesteld, wordt de duur automatisch bepaald op basis van de \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int)-eigenschap en het type overgang.

**Retourneert:**
int
### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Geeft of stelt de duur van het diavoorstellingsovergangseffect in milliseconden. Lezen/Schrijven int.

--------------------

Komt overeen met het p14:dur-attribuut van het p:transition-element in het PresentationML-schema. Indien niet ingesteld, wordt de duur automatisch bepaald op basis van de \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int)-eigenschap en het type overgang.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bepaalt of de twee SlideShowTransition-instanties gelijk zijn. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | De SlideShowTransition om te vergelijken met de huidige SlideShowTransition. |

**Retourneert:**
boolean -  **true**  als de opgegeven SlideShowTransition gelijk is aan de huidige SlideShowTransition; anders **false** .
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als een hash-functie voor een bepaald type, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hashtabel.

**Retourneert:**
int - 23454

--------------------

Overschreven om de compiler tevreden te stellen. Geeft altijd een constante terug omdat het object mutabel is.