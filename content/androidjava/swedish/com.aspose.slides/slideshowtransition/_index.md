---
title: SlideShowTransition
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar bildspelsövergång.
type: docs
url: /sv/com.aspose.slides/slideshowtransition/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

Representerar bildspelsövergång.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSound()](#getSound--) | Returnerar eller anger den inbäddade ljuddata. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Returnerar eller anger den inbäddade ljuddata. |
| [getSoundMode()](#getSoundMode--) | Anger eller returnerar ljudläge för bildspelsövergång. |
| [setSoundMode(int value)](#setSoundMode-int-) | Anger eller returnerar ljudläge för bildspelsövergång. |
| [getSoundLoop()](#getSoundLoop--) | Detta attribut anger om ljudet ska loopa tills nästa ljudhändelse inträffar i bildspelet. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Detta attribut anger om ljudet ska loopa tills nästa ljudhändelse inträffar i bildspelet. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Anger om ett musklick ska gå vidare till nästa bild eller inte. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Anger om ett musklick ska gå vidare till nästa bild eller inte. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Detta attribut anger om bildspelet ska gå till nästa bild efter en viss tid. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Detta attribut anger om bildspelet ska gå till nästa bild efter en viss tid. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Anger tiden i millisekunder efter vilken övergången ska starta. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Anger tiden i millisekunder efter vilken övergången ska starta. |
| [getSpeed()](#getSpeed--) | Anger övergångshastigheten som ska användas när man går från den aktuella bilden till nästa. |
| [setSpeed(int value)](#setSpeed-int-) | Anger övergångshastigheten som ska användas när man går från den aktuella bilden till nästa. |
| [getValue()](#getValue--) | Värde för bildspelsövergång. |
| [getType()](#getType--) | Typ av övergång. |
| [setType(int value)](#setType-int-) | Typ av övergång. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Anger om detta ljud är ett inbyggt ljud eller inte. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Anger om detta ljud är ett inbyggt ljud eller inte. |
| [getSoundName()](#getSoundName--) | Anger ett läsbart namn för övergångens ljud. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Anger ett läsbart namn för övergångens ljud. |
| [getDuration()](#getDuration--) | Hämtar eller anger varaktigheten för bildspelsövergångseffekten i millisekunder. |
| [setDuration(int value)](#setDuration-int-) | Hämtar eller anger varaktigheten för bildspelsövergångseffekten i millisekunder. |
| [equals(Object obj)](#equals-java.lang.Object-) | Avgör om de två SlideShowTransition-instanserna är lika. |
| [hashCode()](#hashCode--) | Fungerar som en hashfunktion för en viss typ, lämplig för användning i hashalgoritmer och datastrukturer som en hash-tabell. |
### getSound() {#getSound--}
```
public final IAudio getSound()
```

Returnerar eller anger den inbäddade ljuddata. Läs/skriv [IAudio](../../com.aspose.slides/iaudio).

**Returnerar:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Returnerar eller anger den inbäddade ljuddata. Läs/skriv [IAudio](../../com.aspose.slides/iaudio).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

Anger eller returnerar ljudläge för bildspelsövergång. Läs/skriv [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Returnerar:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

Anger eller returnerar ljudläge för bildspelsövergång. Läs/skriv [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

Detta attribut anger om ljudet ska loopa tills nästa ljudhändelse inträffar i bildspelet. Läs/skriv boolean.

**Returnerar:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Detta attribut anger om ljudet ska loopa tills nästa ljudhändelse inträffar i bildspelet. Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Anger om ett musklick ska gå vidare till nästa bild eller inte. Om detta attribut inte anges antas värdet true. Läs/skriv boolean.

**Returnerar:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Anger om ett musklick ska gå vidare till nästa bild eller inte. Om detta attribut inte anges antas värdet true. Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

Detta attribut anger om bildspelet ska gå till nästa bild efter en viss tid. Läs/skriv boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Hämta den första bildspelsövergången
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Kontrollera om flaggan Advance Slide After är markerad
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Hämta värdet för Advance Slide After Time
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public final void setAdvanceAfter(boolean value)
```

Detta attribut anger om bildspelet ska gå till nästa bild efter en viss tid. Läs/skriv boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Hämta den första bildspelsövergången
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Kontrollera om flaggan Advance Slide After är markerad
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Hämta värdet för Advance Slide After Time
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public final long getAdvanceAfterTime()
```

Anger tiden i millisekunder efter vilken övergången ska starta. Denna inställning kan användas tillsammans med advClick-attributet. Om detta attribut inte anges antas ingen automatisk förflyttning. Läs/skriv long.

**Returnerar:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Anger tiden i millisekunder efter vilken övergången ska starta. Denna inställning kan användas tillsammans med advClick-attributet. Om detta attribut inte anges antas ingen automatisk förflyttning. Läs/skriv long.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |
### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Anger övergångshastigheten som ska användas när man går från den aktuella bilden till nästa. Läs/skriv [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Returnerar:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Anger övergångshastigheten som ska användas när man går från den aktuella bilden till nästa. Läs/skriv [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

Värde för bildspelsövergång. Skrivskyddad [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Returnerar:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public final int getType()
```

Typ av övergång. Läs/skriv [TransitionType](../../com.aspose.slides/transitiontype).

**Returnerar:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Typ av övergång. Läs/skriv [TransitionType](../../com.aspose.slides/transitiontype).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

Anger om detta ljud är ett inbyggt ljud eller inte. Om detta attribut är true får den genererande applikationen kontrollera namn-attributet för detta ljud i sin lista över inbyggda ljud och kan då visa ett anpassat namn eller UI vid behov. Läs/skriv boolean.

**Returnerar:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Anger om detta ljud är ett inbyggt ljud eller inte. Om detta attribut är true får den genererande applikationen kontrollera namn-attributet för detta ljud i sin lista över inbyggda ljud och kan då visa ett anpassat namn eller UI vid behov. Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Anger ett läsbart namn för övergångens ljud. Sound-egenskapen (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) måste tilldelas för att hämta eller ange ljudnamnet. Läs/skriv String.

**Returnerar:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Anger ett läsbart namn för övergångens ljud. Sound-egenskapen (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) måste tilldelas för att hämta eller ange ljudnamnet. Läs/skriv String.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getDuration() {#getDuration--}
```
public final int getDuration()
```

Hämtar eller anger varaktigheten för bildspelsövergångseffekten i millisekunder. Läs/skriv int.

--------------------

Motsvarar p14:dur-attributet för p:transition-elementet i PresentationML-schemat. Om det inte är satt bestäms varaktigheten automatiskt baserat på \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int)-egenskapen och övergångstypen.

**Returnerar:**
int
### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Hämtar eller anger varaktigheten för bildspelsövergångseffekten i millisekunder. Läs/skriv int.

--------------------

Motsvarar p14:dur-attributet för p:transition-elementet i PresentationML-schemat. Om det inte är satt bestäms varaktigheten automatiskt baserat på \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int)-egenskapen och övergångstypen.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Avgör om de två SlideShowTransition-instanserna är lika. Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | SlideShowTransition-instansen att jämföra med den aktuella SlideShowTransition. |

**Returnerar:**
boolean -  **true**  om den angivna SlideShowTransition är lika med den aktuella SlideShowTransition; annars,  **false** .
### hashCode() {#hashCode--}
```
public int hashCode()
```

Fungerar som en hashfunktion för en viss typ, lämplig för användning i hashalgoritmer och datastrukturer som en hash-tabell.

**Returnerar:**
int - 23454

--------------------

Återdefinierad för att göra kompilatorn nöjd. Returnerar alltid ett konstant värde eftersom objektet är muterbart.