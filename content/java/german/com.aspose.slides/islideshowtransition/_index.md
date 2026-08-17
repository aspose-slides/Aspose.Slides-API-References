---
title: ISlideShowTransition
second_title: Aspose.Slides für Java API-Referenz
description: Stellt den Folienübergang dar.
type: docs
url: /de/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

Stellt den Folienübergang dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSound()](#getSound--) | Gibt die eingebetteten Audiodaten zurück oder legt sie fest. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Gibt die eingebetteten Audiodaten zurück oder legt sie fest. |
| [getSoundMode()](#getSoundMode--) | Setzt oder gibt den Soundmodus für den Folienübergang zurück. |
| [setSoundMode(int value)](#setSoundMode-int-) | Setzt oder gibt den Soundmodus für den Folienübergang zurück. |
| [getSoundLoop()](#getSoundLoop--) | Dieses Attribut gibt an, ob der Ton bis zum nächsten Tonevent in der Diashow wiederholt wird. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Dieses Attribut gibt an, ob der Ton bis zum nächsten Tonevent in der Diashow wiederholt wird. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Gibt an, ob ein Mausklick die Folie vorwärts schalten soll oder nicht. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Gibt an, ob ein Mausklick die Folie vorwärts schalten soll oder nicht. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Gibt die Zeit in Millisekunden an, nach der der Übergang starten soll. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Gibt die Zeit in Millisekunden an, nach der der Übergang starten soll. |
| [getSpeed()](#getSpeed--) | Gibt die Übergangsgeschwindigkeit an, die beim Übergang von der aktuellen Folie zur nächsten verwendet werden soll. |
| [setSpeed(int value)](#setSpeed-int-) | Gibt die Übergangsgeschwindigkeit an, die beim Übergang von der aktuellen Folie zur nächsten verwendet werden soll. |
| [getValue()](#getValue--) | Wert des Folienübergangs. |
| [getType()](#getType--) | Typ des Übergangs. |
| [setType(int value)](#setType-int-) | Typ des Übergangs. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Gibt an, ob dieser Sound ein integrierter Sound ist oder nicht. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Gibt an, ob dieser Sound ein integrierter Sound ist oder nicht. |
| [getSoundName()](#getSoundName--) | Gibt einen benutzerfreundlichen Namen für den Sound des Übergangs an. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Gibt einen benutzerfreundlichen Namen für den Sound des Übergangs an. |
| [getDuration()](#getDuration--) | Liest oder setzt die Dauer des Folienübergangseffekts in Millisekunden. |
| [setDuration(int value)](#setDuration-int-) | Liest oder setzt die Dauer des Folienübergangseffekts in Millisekunden. |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Gibt die eingebetteten Audiodaten zurück oder legt sie fest. Lese-/Schreib [IAudio](../../com.aspose.slides/iaudio).

**Rückgabe:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Gibt die eingebetteten Audiodaten zurück oder legt sie fest. Lese-/Schreib [IAudio](../../com.aspose.slides/iaudio).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

Setzt oder gibt den Soundmodus für den Folienübergang zurück. Lese-/Schreib [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Rückgabe:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

Setzt oder gibt den Soundmodus für den Folienübergang zurück. Lese-/Schreib [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

Dieses Attribut gibt an, ob der Ton bis zum nächsten Tonevent in der Diashow wiederholt wird. Lese-/Schreib boolean.

**Rückgabe:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

Dieses Attribut gibt an, ob der Ton bis zum nächsten Tonevent in der Diashow wiederholt wird. Lese-/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

Gibt an, ob ein Mausklick die Folie vorwärts schalten soll oder nicht. Wenn dieses Attribut nicht angegeben ist, wird ein Wert von true angenommen. Lese-/Schreib boolean.

**Rückgabe:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

Gibt an, ob ein Mausklick die Folie vorwärts schalten soll oder nicht. Wenn dieses Attribut nicht angegeben ist, wird ein Wert von true angenommen. Lese-/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. Lese-/Schreib boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Abrufen des ersten Folienübergangs
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Überprüfen, ob das Flag Advance Slide After gesetzt ist
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Abrufen des Werts für Advance Slide After Time
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```

Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. Lese-/Schreib boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Abrufen des ersten Folienübergangs
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Überprüfen, ob das Flag Advance Slide After gesetzt ist
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Abrufen des Werts für Advance Slide After Time
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```

Gibt die Zeit in Millisekunden an, nach der der Übergang starten soll. Diese Einstellung kann in Verbindung mit dem advClick-Attribut verwendet werden. Wenn dieses Attribut nicht angegeben ist, wird angenommen, dass kein automatischer Vorlauf erfolgt. Lese-/Schreib long.

**Rückgabe:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

Gibt die Zeit in Millisekunden an, nach der der Übergang starten soll. Diese Einstellung kann in Verbindung mit dem advClick-Attribut verwendet werden. Wenn dieses Attribut nicht angegeben ist, wird angenommen, dass kein automatischer Vorlauf erfolgt. Lese-/Schreib long.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |
### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

Gibt die Übergangsgeschwindigkeit an, die beim Übergang von der aktuellen Folie zur nächsten verwendet werden soll. Lese-/Schreib [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Rückgabe:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

Gibt die Übergangsgeschwindigkeit an, die beim Übergang von der aktuellen Folie zur nächsten verwendet werden soll. Lese-/Schreib [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

Wert des Folienübergangs. Nur lesbar [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Rückgabe:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```

Typ des Übergangs. Lese-/Schreib [TransitionType](../../com.aspose.slides/transitiontype).

**Rückgabe:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Typ des Übergangs. Lese-/Schreib [TransitionType](../../com.aspose.slides/transitiontype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

Gibt an, ob dieser Sound ein integrierter Sound ist oder nicht. Wenn dieses Attribut auf true gesetzt ist, wird die erzeugende Anwendung darauf hingewiesen, das Namensattribut für diesen Sound in ihrer Liste integrierter Sounds zu prüfen und kann dann bei Bedarf einen benutzerdefinierten Namen oder eine Benutzeroberfläche bereitstellen. Lese-/Schreib boolean.

**Rückgabe:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

Gibt an, ob dieser Sound ein integrierter Sound ist oder nicht. Wenn dieses Attribut auf true gesetzt ist, wird die erzeugende Anwendung darauf hingewiesen, das Namensattribut für diesen Sound in ihrer Liste integrierter Sounds zu prüfen und kann dann bei Bedarf einen benutzerdefinierten Namen oder eine Benutzeroberfläche bereitstellen. Lese-/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

Gibt einen benutzerfreundlichen Namen für den Sound des Übergangs an. Die (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) Eigenschaft muss zugewiesen werden, um den Soundnamen zu erhalten oder zu setzen. Lese-/Schreib String.

**Rückgabe:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

Gibt einen benutzerfreundlichen Namen für den Sound des Übergangs an. Die \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) Eigenschaft muss zugewiesen werden, um den Soundnamen zu erhalten oder zu setzen. Lese-/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

Liest oder setzt die Dauer des Folienübergangseffekts in Millisekunden. Lese-/Schreib int.

--------------------

Entspricht dem p14:dur-Attribut des p:transition-Elements im PresentationML-Schema. Wenn nicht gesetzt, wird die Dauer automatisch basierend auf der \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) Eigenschaft und dem Übergangstyp ermittelt.

**Rückgabe:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

Liest oder setzt die Dauer des Folienübergangseffekts in Millisekunden. Lese-/Schreib int.

--------------------

Entspricht dem p14:dur-Attribut des p:transition-Elements im PresentationML-Schema. Wenn nicht gesetzt, wird die Dauer automatisch basierend auf der \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) Eigenschaft und dem Übergangstyp ermittelt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |