---
title: SlideShowTransition
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Stellt den Folienübergang dar.
type: docs
url: /de/com.aspose.slides/slideshowtransition/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

Stellt den Folienübergang dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSound()](#getSound--) | Gibt die eingebetteten Audiodaten zurück oder setzt sie. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Gibt die eingebetteten Audiodaten zurück oder setzt sie. |
| [getSoundMode()](#getSoundMode--) | Setzt oder gibt den Soundmodus für den Folienübergang zurück. |
| [setSoundMode(int value)](#setSoundMode-int-) | Setzt oder gibt den Soundmodus für den Folienübergang zurück. |
| [getSoundLoop()](#getSoundLoop--) | Dieses Attribut gibt an, ob der Ton bis zum nächsten Soundereignis in der Diashow wiederholt wird. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Dieses Attribut gibt an, ob der Ton bis zum nächsten Soundereignis in der Diashow wiederholt wird. |
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
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Gibt an, ob dieser Ton ein integrierter Ton ist oder nicht. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Gibt an, ob dieser Ton ein integrierter Ton ist oder nicht. |
| [getSoundName()](#getSoundName--) | Gibt einen menschenlesbaren Namen für den Ton des Übergangs an. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Gibt einen menschenlesbaren Namen für den Ton des Übergangs an. |
| [getDuration()](#getDuration--) | Liest oder setzt die Dauer des Folienübergangseffekts in Millisekunden. |
| [setDuration(int value)](#setDuration-int-) | Liest oder setzt die Dauer des Folienübergangseffekts in Millisekunden. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob die beiden SlideShowTransition-Instanzen gleich sind. |
| [hashCode()](#hashCode--) | Dient als Hashfunktion für einen bestimmten Typ, geeignet für den Einsatz in Hash-Algorithmen und Datenstrukturen wie einer Hashtabelle. |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Gibt die eingebetteten Audiodaten zurück oder setzt sie. Lesen/Schreiben [IAudio](../../com.aspose.slides/iaudio).

**Rückgabe:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Gibt die eingebetteten Audiodaten zurück oder setzt sie. Lesen/Schreiben [IAudio](../../com.aspose.slides/iaudio).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

Setzt oder gibt den Soundmodus für den Folienübergang zurück. Lesen/Schreiben [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Rückgabe:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

Setzt oder gibt den Soundmodus für den Folienübergang zurück. Lesen/Schreiben [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

Dieses Attribut gibt an, ob der Ton bis zum nächsten Soundereignis in der Diashow wiederholt wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Dieses Attribut gibt an, ob der Ton bis zum nächsten Soundereignis in der Diashow wiederholt wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Gibt an, ob ein Mausklick die Folie weiterblättert oder nicht. Falls dieses Attribut nicht angegeben ist, wird ein Wert von true angenommen. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Gibt an, ob ein Mausklick die Folie weiterblättert oder nicht. Falls dieses Attribut nicht angegeben ist, wird ein Wert von true angenommen. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. Lesen/Schreiben boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Holt den ersten Folienübergang
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Prüft, ob das Flag 'Advance Slide After' aktiviert ist
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Holt den Wert für 'Advance Slide After Time'
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
public final void setAdvanceAfter(boolean value)
```

Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. Lesen/Schreiben boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Holt den ersten Folienübergang
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Prüft, ob das Flag 'Advance Slide After' aktiviert ist
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Holt den Wert für 'Advance Slide After Time'
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
public final long getAdvanceAfterTime()
```

Gibt die Zeit in Millisekunden an, nach der der Übergang starten soll. Diese Einstellung kann in Verbindung mit dem advClick-Attribut verwendet werden. Falls dieses Attribut nicht angegeben ist, wird angenommen, dass kein automatisches Weiterblättern erfolgt. Lesen/Schreiben long.

**Rückgabe:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Gibt die Zeit in Millisekunden an, nach der der Übergang starten soll. Diese Einstellung kann in Verbindung mit dem advClick-Attribut verwendet werden. Falls dieses Attribut nicht angegeben ist, wird angenommen, dass kein automatisches Weiterblättern erfolgt. Lesen/Schreiben long.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Gibt die Übergangsgeschwindigkeit an, die beim Übergang von der aktuellen Folie zur nächsten verwendet wird. Lesen/Schreiben [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Rückgabe:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Gibt die Übergangsgeschwindigkeit an, die beim Übergang von der aktuellen Folie zur nächsten verwendet wird. Lesen/Schreiben [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

Wert des Folienübergangs. Nur Lesen [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Rückgabe:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public final int getType()
```

Art des Übergangs. Lesen/Schreiben [TransitionType](../../com.aspose.slides/transitiontype).

**Rückgabe:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Art des Übergangs. Lesen/Schreiben [TransitionType](../../com.aspose.slides/transitiontype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

Gibt an, ob dieser Ton ein integrierter Ton ist oder nicht. Wenn dieses Attribut auf true gesetzt ist, wird die erzeugende Anwendung darauf hingewiesen, das name-Attribut dieses Tons in ihrer Liste integrierter Töne zu überprüfen und ggf. einen benutzerdefinierten Namen oder eine Benutzeroberfläche bereitzustellen. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Gibt an, ob dieser Ton ein integrierter Ton ist oder nicht. Wenn dieses Attribut auf true gesetzt ist, wird die erzeugende Anwendung darauf hingewiesen, das name-Attribut dieses Tons in ihrer Liste integrierter Töne zu überprüfen und ggf. einen benutzerdefinierten Namen oder eine Benutzeroberfläche bereitzustellen. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Gibt einen menschenlesbaren Namen für den Ton des Übergangs an. Die Eigenschaft Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) muss zugewiesen werden, um den Namen des Tons zu erhalten oder zu setzen. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Gibt einen menschenlesbaren Namen für den Ton des Übergangs an. Die Eigenschaft Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) muss zugewiesen werden, um den Namen des Tons zu erhalten oder zu setzen. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

Liest oder setzt die Dauer des Folienübergangseffekts in Millisekunden. Lesen/Schreiben int.

--------------------

Entspricht dem p14:dur-Attribut des p:transition-Elements im PresentationML-Schema. Wenn nicht gesetzt, wird die Dauer automatisch basierend auf der \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int)-Eigenschaft und dem Übergangstyp bestimmt.

**Rückgabe:**
int

### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Liest oder setzt die Dauer des Folienübergangseffekts in Millisekunden. Lesen/Schreiben int.

--------------------

Entspricht dem p14:dur-Attribut des p:transition-Elements im PresentationML-Schema. Wenn nicht gesetzt, wird die Dauer automatisch basierend auf der \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int)-Eigenschaft und dem Übergangstyp bestimmt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestimmt, ob die beiden SlideShowTransition-Instanzen gleich sind. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Der SlideShowTransition zum Vergleich mit dem aktuellen SlideShowTransition. |

**Rückgabe:**
boolean - **true** wenn der angegebene SlideShowTransition gleich dem aktuellen SlideShowTransition ist; sonst **false**.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als Hashfunktion für einen bestimmten Typ, geeignet für den Einsatz in Hash-Algorithmen und Datenstrukturen wie einer Hashtabelle.

**Rückgabe:**
int - 23454

--------------------

Überschrieben, um den Compiler zufrieden zu stellen. Gibt immer eine Konstante zurück, da das Objekt veränderlich ist.