---
title: ITiming
second_title: Aspose.Slides for Android via Java API Reference
description: Stelt animatietiming voor.
type: docs
url: /nl/com.aspose.slides/itiming/
---```
public interface ITiming
```

Stelt animatietiming voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | Beschrijft het percentage van de duur van het versnellingseffect. |
| [setAccelerate(float value)](#setAccelerate-float-) | Beschrijft het percentage van de duur van het versnellingseffect. |
| [getDecelerate()](#getDecelerate--) | Beschrijft het percentage van de duur van het vertragingseffect. |
| [setDecelerate(float value)](#setDecelerate-float-) | Beschrijft het percentage van de duur van het vertragingseffect. |
| [getAutoReverse()](#getAutoReverse--) | Beschrijft of de animatie automatisch in omgekeerde volgorde wordt afgespeeld nadat deze in de voorwaartse richting is afgespeeld. |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | Beschrijft of de animatie automatisch in omgekeerde volgorde wordt afgespeeld nadat deze in de voorwaartse richting is afgespeeld. |
| [getDuration()](#getDuration--) | Beschrijft de duur van het animatie-effect. |
| [setDuration(float value)](#setDuration-float-) | Beschrijft de duur van het animatie-effect. |
| [getRepeatCount()](#getRepeatCount--) | Beschrijft hoe vaak het effect moet worden herhaald. |
| [setRepeatCount(float value)](#setRepeatCount-float-) | Beschrijft hoe vaak het effect moet worden herhaald. |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | Dit attribuut geeft aan of het effect wordt herhaald tot het einde van de dia. |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | Dit attribuut geeft aan of het effect wordt herhaald tot het einde van de dia. |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | Dit attribuut geeft aan of het effect wordt herhaald tot de volgende klik. |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | Dit attribuut geeft aan of het effect wordt herhaald tot de volgende klik. |
| [getRepeatDuration()](#getRepeatDuration--) | Beschrijft hoe vaak het effect moet worden herhaald. |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | Beschrijft hoe vaak het effect moet worden herhaald. |
| [getRestart()](#getRestart--) | Geeft aan of een effect opnieuw moet starten na voltooiing. |
| [setRestart(int value)](#setRestart-int-) | Geeft aan of een effect opnieuw moet starten na voltooiing. |
| [getSpeed()](#getSpeed--) | Geeft het percentage aan waarmee de timing wordt versneld (of vertraagd). |
| [setSpeed(float value)](#setSpeed-float-) | Geeft het percentage aan waarmee de timing wordt versneld (of vertraagd). |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | Beschrijft de vertragingstijd na de trigger. |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | Beschrijft de vertragingstijd na de trigger. |
| [getTriggerType()](#getTriggerType--) | Beschrijft het type trigger. |
| [setTriggerType(int value)](#setTriggerType-int-) | Beschrijft het type trigger. |
| [getRewind()](#getRewind--) | Dit attribuut geeft aan of het effect wordt teruggespoeld wanneer het afspelen is voltooid. |
| [setRewind(boolean value)](#setRewind-boolean-) | Dit attribuut geeft aan of het effect wordt teruggespoeld wanneer het afspelen is voltooid. |
### getAccelerate() {#getAccelerate--}
```
public abstract float getAccelerate()
```


Beschrijft het percentage van de duur van het versnellingseffect. Lezen/schrijven float.

**Retour:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public abstract void setAccelerate(float value)
```


Beschrijft het percentage van de duur van het versnellingseffect. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public abstract float getDecelerate()
```


Beschrijft het percentage van de duur van het vertragingseffect. Lezen/schrijven float.

**Retour:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public abstract void setDecelerate(float value)
```


Beschrijft het percentage van de duur van het vertragingseffect. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public abstract boolean getAutoReverse()
```


Beschrijft of de animatie automatisch in omgekeerde volgorde wordt afgespeeld nadat deze in de voorwaartse richting is afgespeeld. Lezen/schrijven boolean.

**Retour:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public abstract void setAutoReverse(boolean value)
```


Beschrijft of de animatie automatisch in omgekeerde volgorde wordt afgespeeld nadat deze in de voorwaartse richting is afgespeeld. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public abstract float getDuration()
```


Beschrijft de duur van het animatie-effect. Lezen/schrijven float.

**Retour:**
float
### setDuration(float value) {#setDuration-float-}
```
public abstract void setDuration(float value)
```


Beschrijft de duur van het animatie-effect. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public abstract float getRepeatCount()
```


Beschrijft hoe vaak het effect moet worden herhaald. Lezen/schrijven float.

**Retour:**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public abstract void setRepeatCount(float value)
```


Beschrijft hoe vaak het effect moet worden herhaald. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public abstract boolean getRepeatUntilEndSlide()
```


Dit attribuut geeft aan of het effect wordt herhaald tot het einde van de dia. Lezen/schrijven boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Haal de effectensequentie op voor de eerste dia
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Haal het eerste effect van de hoofdsequentie op.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Wijzig de Timing/Herhaling van het effect naar "Until End of Slide"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retour:**
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public abstract void setRepeatUntilEndSlide(boolean value)
```


Dit attribuut geeft aan of het effect wordt herhaald tot het einde van de dia. Lezen/schrijven boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Haal de effectensequentie op voor de eerste dia
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Haal het eerste effect van de hoofdsequentie op.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Wijzig de Timing/Herhaling van het effect naar "Until End of Slide"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public abstract boolean getRepeatUntilNextClick()
```


Dit attribuut geeft aan of het effect wordt herhaald tot de volgende klik. Lezen/schrijven boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Haal de effectensequentie op voor de eerste dia
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Haal het eerste effect van de hoofdsequentie op.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Wijzig de Timing/Herhaling van het effect naar "Tot volgende klik"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retour:**
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public abstract void setRepeatUntilNextClick(boolean value)
```


Dit attribuut geeft aan of het effect wordt herhaald tot de volgende klik. Lezen/schrijven boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Haal de effectensequentie op voor de eerste dia
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Haal het eerste effect van de hoofdsequentie op.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Wijzig de Timing/Herhaling van het effect naar "Until Next Click"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getRepeatDuration() {#getRepeatDuration--}
```
public abstract float getRepeatDuration()
```


Beschrijft hoe vaak het effect moet worden herhaald. Lezen/schrijven float.

**Retour:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public abstract void setRepeatDuration(float value)
```


Beschrijft hoe vaak het effect moet worden herhaald. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public abstract int getRestart()
```


Geeft aan of een effect opnieuw moet starten na voltooiing. Lezen/schrijven [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Retour:**
int
### setRestart(int value) {#setRestart-int-}
```
public abstract void setRestart(int value)
```


Geeft aan of een effect opnieuw moet starten na voltooiing. Lezen/schrijven [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSpeed() {#getSpeed--}
```
public abstract float getSpeed()
```


Geeft het percentage aan waarmee de timing wordt versneld (of vertraagd). Lezen/schrijven float.

**Retour:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public abstract void setSpeed(float value)
```


Geeft het percentage aan waarmee de timing wordt versneld (of vertraagd). Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public abstract float getTriggerDelayTime()
```


Beschrijft de vertragingstijd na de trigger. Lezen/schrijven float.

**Retour:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public abstract void setTriggerDelayTime(float value)
```


Beschrijft de vertragingstijd na de trigger. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public abstract int getTriggerType()
```


Beschrijft het type trigger. Lezen/schrijven [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Retour:**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public abstract void setTriggerType(int value)
```


Beschrijft het type trigger. Lezen/schrijven [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public abstract boolean getRewind()
```


Dit attribuut geeft aan of het effect wordt teruggespoeld wanneer het afspelen is voltooid. Lezen/schrijven boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Haal de effectensequentie op voor de eerste dia
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Haal het eerste effect van de hoofdsequentie op.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Schakel de Timing/Rewind van het effect in.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retour:**
boolean
### setRewind(boolean value) {#setRewind-boolean-}
```
public abstract void setRewind(boolean value)
```


Dit attribuut geeft aan of het effect wordt teruggespoeld wanneer het afspelen is voltooid. Lezen/schrijven boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Haal de effectensequentie op voor de eerste dia
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Haal het eerste effect van de hoofdsequentie op.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Schakel de Timing/Rewind van het effect in.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |