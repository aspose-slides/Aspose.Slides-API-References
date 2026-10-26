---
title: ISlideShowTransition
second_title: Aspose.Slides for Java API Reference
description: Represents slide show transition.
type: docs
url: /sv/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

Representerar bildspelsövergång.
## Metoder

| Method | Description |
| --- | --- |
| [getSound()](#getSound--) | Returnerar eller sätter den inbäddade ljuddata. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Returnerar eller sätter den inbäddade ljuddata. |
| [getSoundMode()](#getSoundMode--) | Sätter eller returnerar ljudläge för bildspelsövergången. |
| [setSoundMode(int value)](#setSoundMode-int-) | Sätter eller returnerar ljudläge för bildspelsövergången. |
| [getSoundLoop()](#getSoundLoop--) | Detta attribut anger om ljudet ska loopa tills nästa ljudevent inträffar i bildspelet. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Detta attribut anger om ljudet ska loopa tills nästa ljudevent inträffar i bildspelet. |
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
| [getSoundName()](#getSoundName--) | Anger ett människoläsbart namn för ljudet i övergången. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Anger ett människoläsbart namn för ljudet i övergången. |
| [getDuration()](#getDuration--) | Hämtar eller anger varaktigheten för bildspelsövergångseffekten i millisekunder. |
| [setDuration(int value)](#setDuration-int-) | Hämtar eller anger varaktigheten för bildspelsövergångseffekten i millisekunder. |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Returnerar eller sätter den inbäddade ljuddata. Läs/skriv [IAudio](../../com.aspose.slides/iaudio).

**Returnerar:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Returnerar eller sätter den inbäddade ljuddata. Läs/skriv [IAudio](../../com.aspose.slides/iaudio).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

Sätter eller returnerar ljudläge för bildspelsövergången. Läs/skriv [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Returnerar:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

Sätter eller returnerar ljudläge för bildspelsövergången. Läs/skriv [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

Detta attribut anger om ljudet ska loopa tills nästa ljudevent inträffar i bildspelet. Läs/skriv boolean.

**Returnerar:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

Detta attribut anger om ljudet ska loopa tills nästa ljudevent inträffar i bildspelet. Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

Anger om ett musklick ska gå vidare till nästa bild eller inte. Om detta attribut inte anges antas värdet true. Läs/skriv boolean.

**Returnerar:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

Anger om ett musklick ska gå vidare till nästa bild eller inte. Om detta attribut inte anges antas värdet true. Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

Detta attribut anger om bildspelet ska gå till nästa bild efter en viss tid. Läs/skriv  boolean .

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Hämta den första bildens övergång
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Kontrollera om flaggan för automatisk förflyttning efter bild är markerad
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Hämta värdet för tiden för automatisk förflyttning efter bild
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
public abstract void setAdvanceAfter(boolean value)
```

Detta attribut anger om bildspelet ska gå till nästa bild efter en viss tid. Läs/skriv  boolean .

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Hämta den första bildens övergång
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Kontrollera om flaggan för automatisk förflyttning efter bild är markerad
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Hämta värdet för tiden för automatisk förflyttning efter bild
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
public abstract long getAdvanceAfterTime()
```

Anger tiden i millisekunder efter vilken övergången ska starta. Denna inställning kan användas tillsammans med advClick-attributet. Om detta attribut inte anges antas att ingen automatisk vidaregång sker. Läs/skriv long.

**Returnerar:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

Anger tiden i millisekunder efter vilken övergången ska starta. Denna inställning kan användas tillsammans med advClick-attributet. Om detta attribut inte anges antas att ingen automatisk vidaregång sker. Läs/skriv long.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

Anger övergångshastigheten som ska användas när man går från den aktuella bilden till nästa. Läs/skriv [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Returnerar:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

Anger övergångshastigheten som ska användas när man går från den aktuella bilden till nästa. Läs/skriv [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

Värde för bildspelsövergång. Endast läsning [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Returnerar:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public abstract int getType()
```

Typ av övergång. Läs/skriv [TransitionType](../../com.aspose.slides/transitiontype).

**Returnerar:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Typ av övergång. Läs/skriv [TransitionType](../../com.aspose.slides/transitiontype).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

Anger om detta ljud är ett inbyggt ljud eller inte. Om detta attribut är true uppmanas den genererande applikationen att kontrollera namn-attributet som anges för detta ljud i dess lista över inbyggda ljud och kan då presentera ett anpassat namn eller UI vid behov. Läs/skriv boolean.

**Returnerar:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

Anger om detta ljud är ett inbyggt ljud eller inte. Om detta attribut är true uppmanas den genererande applikationen att kontrollera namn-attributet som anges för detta ljud i dess lista över inbyggda ljud och kan då presentera ett anpassat namn eller UI vid behov. Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

Anger ett människoläsbart namn för ljudet i övergången. The (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) property must be assigned to get or set the sound name. Läs/skriv String.

**Returnerar:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

Anger ett människoläsbart namn för ljudet i övergången. The \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) property must be assigned to get or set the sound name. Läs/skriv String.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

Hämtar eller anger varaktigheten för bildspelsövergångseffekten i millisekunder. Läs/skriv int.

--------------------

Motsvarar p14:dur-attributet för p:transition-elementet i PresentationML-schemat. Om det inte anges bestäms varaktigheten automatiskt baserat på \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int)-egenskapen och övergångstypen.

**Returnerar:**
int

### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

Hämtar eller anger varaktigheten för bildspelsövergångseffekten i millisekunder. Läs/skriv int.

--------------------

Motsvarar p14:dur-attributet för p:transition-elementet i PresentationML-schemat. Om det inte anges bestäms varaktigheten automatiskt baserat på \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int)-egenskapen och övergångstypen.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |