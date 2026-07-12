---
title: ISlideShowTransition
second_title: Aspose.Slides for Android via Java API Reference
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
| [getSoundMode()](#getSoundMode--) | Legt den Soundmodus für den Folienübergang fest oder gibt ihn zurück. |
| [setSoundMode(int value)](#setSoundMode-int-) | Legt den Soundmodus für den Folienübergang fest oder gibt ihn zurück. |
| [getSoundLoop()](#getSoundLoop--) | Dieses Attribut gibt an, ob der Sound wiederholt wird, bis das nächste Soundereignis in der Diashow auftritt. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Dieses Attribut gibt an, ob der Sound wiederholt wird, bis das nächste Soundereignis in der Diashow auftritt. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Gibt an, ob ein Mausklick die Folie weiterblättert oder nicht. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Gibt an, ob ein Mausklick die Folie weiterblättert oder nicht. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Gibt die Zeit in Millisekunden an, nach der der Übergang starten soll. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Gibt die Zeit in Millisekunden an, nach der der Übergang starten soll. |
| [getSpeed()](#getSpeed--) | Gibt die Übergangsgeschwindigkeit an, die beim Übergang von der aktuellen Folie zur nächsten verwendet wird. |
| [setSpeed(int value)](#setSpeed-int-) | Gibt die Übergangsgeschwindigkeit an, die beim Übergang von der aktuellen Folie zur nächsten verwendet wird. |
| [getValue()](#getValue--) | Wert des Folienübergangs. |
| [getType()](#getType--) | Art des Übergangs. |
| [setType(int value)](#setType-int-) | Art des Übergangs. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Gibt an, ob dieser Sound ein integrierter Sound ist oder nicht. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Gibt an, ob dieser Sound ein integrierter Sound ist oder nicht. |
| [getSoundName()](#getSoundName--) | Gibt einen menschenlesbaren Namen für den Sound des Übergangs an. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Gibt einen menschenlesbaren Namen für den Sound des Übergangs an. |
| [getDuration()](#getDuration--) | Liest oder legt die Dauer des Folienübergangseffekts in Millisekunden fest. |
| [setDuration(int value)](#setDuration-int-) | Liest oder legt die Dauer des Folienübergangseffekts in Millisekunden fest. |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Gibt die eingebetteten Audiodaten zurück oder legt sie fest. Lesen-Schreiben [IAudio](../../com.aspose.slides/iaudio).

**Rückgabe:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Gibt die eingebetteten Audiodaten zurück oder legt sie fest. Lesen-Schreiben [IAudio](../../com.aspose.slides/iaudio).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

Legt den Soundmodus für den Folienübergang fest oder gibt ihn zurück. Lesen-Schreiben [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Rückgabe:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

Legt den Soundmodus für den Folienübergang fest oder gibt ihn zurück. Lesen-Schreiben [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

Dieses Attribut gibt an, ob der Sound wiederholt wird, bis das nächste Soundereignis in der Diashow auftritt. Lesen-Schreiben boolean.

**Rückgabe:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

Dieses Attribut gibt an, ob der Sound wiederholt wird, bis das nächste Soundereignis in der Diashow auftritt. Lesen-Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

Gibt an, ob ein Mausklick die Folie weiterblättert oder nicht. Wenn dieses Attribut nicht angegeben ist, wird ein Wert von true angenommen. Lesen-Schreiben boolean.

**Rückgabe:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

Gibt an, ob ein Mausklick die Folie weiterblättert oder nicht. Wenn dieses Attribut nicht angegeben ist, wird ein Wert von true angenommen. Lesen-Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. Lesen/Schreiben  boolean .

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Hole den ersten Folienübergang
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Prüfe, ob das Advance Slide After-Flag gesetzt ist
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Hole den Advance Slide After Time-Wert
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

Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. Lesen/Schreiben  boolean .

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Hole den ersten Folienübergang
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Prüfe, ob das Advance Slide After-Flag gesetzt ist
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Hole den Advance Slide After Time-Wert
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

Gibt die Zeit in Millisekunden an, nach der der Übergang starten soll. Diese Einstellung kann in Verbindung mit dem advClick-Attribut verwendet werden. Wenn dieses Attribut nicht angegeben ist, wird angenommen, dass kein automatisches Vorblättern erfolgt. Lesen-Schreiben long.

**Rückgabe:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

Gibt die Zeit in Millisekunden an, nach der der Übergang starten soll. Diese Einstellung kann in Verbindung mit dem advClick-Attribut verwendet werden. Wenn dieses Attribut nicht angegeben ist, wird angenommen, dass kein automatisches Vorblättern erfolgt. Lesen-Schreiben long.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

Gibt die Übergangsgeschwindigkeit an, die beim Übergang von der aktuellen Folie zur nächsten verwendet wird. Lesen-Schreiben [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Rückgabe:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

Gibt die Übergangsgeschwindigkeit an, die beim Übergang von der aktuellen Folie zur nächsten verwendet wird. Lesen-Schreiben [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

Wert des Folienübergangs. Nur-Lesen [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Rückgabe:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public abstract int getType()
```

Art des Übergangs. Lesen-Schreiben [TransitionType](../../com.aspose.slides/transitiontype).

**Rückgabe:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Art des Übergangs. Lesen-Schreiben [TransitionType](../../com.aspose.slides/transitiontype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

Gibt an, ob dieser Sound ein integrierter Sound ist oder nicht. Wenn dieses Attribut auf true gesetzt ist, wird die erzeugende Anwendung darauf hingewiesen, das Namensattribut für diesen Sound in ihrer Liste integrierter Sounds zu prüfen und kann dann bei Bedarf einen benutzerdefinierten Namen oder eine Benutzeroberfläche bereitstellen. Lesen-Schreiben boolean.

**Rückgabe:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

Gibt an, ob dieser Sound ein integrierter Sound ist oder nicht. Wenn dieses Attribut auf true gesetzt ist, wird die erzeugende Anwendung darauf hingewiesen, das Namensattribut für diesen Sound in ihrer Liste integrierter Sounds zu prüfen und kann dann bei Bedarf einen benutzerdefinierten Namen oder eine Benutzeroberfläche bereitstellen. Lesen-Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

Gibt einen menschenlesbaren Namen für den Sound des Übergangs an. Die (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) Eigenschaft muss zugewiesen werden, um den Soundnamen zu erhalten oder festzulegen. Lesen-Schreiben String.

**Rückgabe:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

Gibt einen menschenlesbaren Namen für den Sound des Übergangs an. Die \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) Eigenschaft muss zugewiesen werden, um den Soundnamen zu erhalten oder festzulegen. Lesen-Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

Liest oder legt die Dauer des Folienübergangseffekts in Millisekunden fest. Lesen/Schreiben int.

--------------------

Entspricht dem Attribut p14:dur des p:transition-Elements im PresentationML-Schema. Wenn nicht gesetzt, wird die Dauer automatisch basierend auf der \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int)-Eigenschaft und dem Übergangstyp ermittelt.

**Rückgabe:**
int

### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

Liest oder legt die Dauer des Folienübergangseffekts in Millisekunden fest. Lesen/Schreiben int.

--------------------

Entspricht dem Attribut p14:dur des p:transition-Elements im PresentationML-Schema. Wenn nicht gesetzt, wird die Dauer automatisch basierend auf der \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int)-Eigenschaft und dem Übergangstyp ermittelt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |