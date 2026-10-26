---
title: ITiming
second_title: Aspose.Slides för Java API-referens
description: Representerar animationstiming.
type: docs
url: /sv/com.aspose.slides/itiming/
---```
public interface ITiming
```

Representerar animationstiming.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | Beskriver procentandelen av varaktigheten för accelerationsbeteendeeffekten. |
| [setAccelerate(float value)](#setAccelerate-float-) | Beskriver procentandelen av varaktigheten för accelerationsbeteendeeffekten. |
| [getDecelerate()](#getDecelerate--) | Beskriver procentandelen av varaktigheten för decelerationsbeteendeeffekten. |
| [setDecelerate(float value)](#setDecelerate-float-) | Beskriver procentandelen av varaktigheten för decelerationsbeteendeeffekten. |
| [getAutoReverse()](#getAutoReverse--) | Beskriver huruvida animationen automatiskt spelas upp i omvänd riktning efter att ha spelats i framåtriktning. |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | Beskriver huruvida animationen automatiskt spelas upp i omvänd riktning efter att ha spelats i framåtriktning. |
| [getDuration()](#getDuration--) | Beskriver varaktigheten av animationseffekten. |
| [setDuration(float value)](#setDuration-float-) | Beskriver varaktigheten av animationseffekten. |
| [getRepeatCount()](#getRepeatCount--) | Beskriver antalet gånger effekten ska upprepas. |
| [setRepeatCount(float value)](#setRepeatCount-float-) | Beskriver antalet gånger effekten ska upprepas. |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | Detta attribut anger om effekten ska upprepas till slidens slut. |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | Detta attribut anger om effekten ska upprepas till slidens slut. |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | Detta attribut anger om effekten ska upprepas till nästa klick. |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | Detta attribut anger om effekten ska upprepas till nästa klick. |
| [getRepeatDuration()](#getRepeatDuration--) | Beskriver antalet gånger effekten ska upprepas. |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | Beskriver antalet gånger effekten ska upprepas. |
| [getRestart()](#getRestart--) | Anger om en effekt ska startas om efter fullbordning. |
| [setRestart(int value)](#setRestart-int-) | Anger om en effekt ska startas om efter fullbordning. |
| [getSpeed()](#getSpeed--) | Anger procentandelen för att påskynda (eller sakta ner) timingen. |
| [setSpeed(float value)](#setSpeed-float-) | Anger procentandelen för att påskynda (eller sakta ner) timingen. |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | Beskriver fördröjningstid efter utlösare. |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | Beskriver fördröjningstid efter utlösare. |
| [getTriggerType()](#getTriggerType--) | Beskriver utlösartyp. |
| [setTriggerType(int value)](#setTriggerType-int-) | Beskriver utlösartyp. |
| [getRewind()](#getRewind--) | Detta attribut anger om effekten ska spolas tillbaka när den är klar. |
| [setRewind(boolean value)](#setRewind-boolean-) | Detta attribut anger om effekten ska spolas tillbaka när den är klar. |
### getAccelerate() {#getAccelerate--}
```
public abstract float getAccelerate()
```

Beskriver procentandelen av varaktigheten för accelerationsbeteendeeffekten. Läs/skriv float.

**Returnerar:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public abstract void setAccelerate(float value)
```

Beskriver procentandelen av varaktigheten för accelerationsbeteendeeffekten. Läs/skriv float.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getDecelerate() {#getDecelerate--}
```
public abstract float getDecelerate()
```

Beskriver procentandelen av varaktigheten för decelerationsbeteendeeffekten. Läs/skriv float.

**Returnerar:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public abstract void setDecelerate(float value)
```

Beskriver procentandelen av varaktigheten för decelerationsbeteendeeffekten. Läs/skriv float.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getAutoReverse() {#getAutoReverse--}
```
public abstract boolean getAutoReverse()
```

Beskriver huruvida animationen automatiskt spelas upp i omvänd riktning efter att ha spelats i framåtriktning. Läs/skriv boolean.

**Returnerar:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public abstract void setAutoReverse(boolean value)
```

Beskriver huruvida animationen automatiskt spelas upp i omvänd riktning efter att ha spelats i framåtriktning. Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getDuration() {#getDuration--}
```
public abstract float getDuration()
```

Beskriver varaktigheten av animationseffekten. Läs/skriv float.

**Returnerar:**
float
### setDuration(float value) {#setDuration-float-}
```
public abstract void setDuration(float value)
```

Beskriver varaktigheten av animationseffekten. Läs/skriv float.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getRepeatCount() {#getRepeatCount--}
```
public abstract float getRepeatCount()
```

Beskriver antalet gånger effekten ska upprepas. Läs/skriv float.

**Returnerar:**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public abstract void setRepeatCount(float value)
```

Beskriver antalet gånger effekten ska upprepas. Läs/skriv float.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public abstract boolean getRepeatUntilEndSlide()
```

Detta attribut anger om effekten ska upprepas till slidens slut. Läs/skriv boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Hämta effektsekvensen för den första sliden
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Hämta den första effekten i huvudsekvensen.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Ändra effekten Timing/Upprepning till "Tills slutet av sliden"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returnerar:**
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public abstract void setRepeatUntilEndSlide(boolean value)
```

Detta attribut anger om effekten ska upprepas till slidens slut. Läs/skriv boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Hämta effektsekvensen för den första sliden
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Hämta den första effekten i huvudsekvensen.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Ändra effektens Timing/Upprepning till "Tills slutet av sliden"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public abstract boolean getRepeatUntilNextClick()
```

Detta attribut anger om effekten ska upprepas till nästa klick. Läs/skriv boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Hämta effektsekvensen för den första sliden
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Hämta den första effekten i huvudsekvensen.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Ändra effektens Timing/Upprepning till "Tills nästa klick"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Returnerar:**
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public abstract void setRepeatUntilNextClick(boolean value)
```

Detta attribut anger om effekten ska upprepas till nästa klick. Läs/skriv boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Hämta effektsekvensen för den första sliden
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Hämta den första effekten i huvudsekvensen.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Ändra effektens Timing/Upprepning till "Tills nästa klick"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getRepeatDuration() {#getRepeatDuration--}
```
public abstract float getRepeatDuration()
```

Beskriver antalet gånger effekten ska upprepas. Läs/skriv float.

**Returnerar:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public abstract void setRepeatDuration(float value)
```

Beskriver antalet gånger effekten ska upprepas. Läs/skriv float.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getRestart() {#getRestart--}
```
public abstract int getRestart()
```

Anger om en effekt ska startas om efter fullbordning. Läs/skriv [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Returnerar:**
int
### setRestart(int value) {#setRestart-int-}
```
public abstract void setRestart(int value)
```

Anger om en effekt ska startas om efter fullbordning. Läs/skriv [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSpeed() {#getSpeed--}
```
public abstract float getSpeed()
```

Anger procentandelen för att påskynda (eller sakta ner) timingen. Läs/skriv float.

**Returnerar:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public abstract void setSpeed(float value)
```

Anger procentandelen för att påskynda (eller sakta ner) timingen. Läs/skriv float.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public abstract float getTriggerDelayTime()
```

Beskriver fördröjningstid efter utlösare. Läs/skriv float.

**Returnerar:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public abstract void setTriggerDelayTime(float value)
```

Beskriver fördröjningstid efter utlösare. Läs/skriv float.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getTriggerType() {#getTriggerType--}
```
public abstract int getTriggerType()
```

Beskriver utlösartyp. Läs/skriv [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Returnerar:**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public abstract void setTriggerType(int value)
```

Beskriver utlösartyp. Läs/skriv [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getRewind() {#getRewind--}
```
public abstract boolean getRewind()
```

Detta attribut anger om effekten ska spolas tillbaka när den är klar. Läs/skriv boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Hämta effektsekvensen för den första sliden
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Hämta den första effekten i huvudsekvensen.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Aktivera effektens Timing/Rewind.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Returnerar:**
boolean
### setRewind(boolean value) {#setRewind-boolean-}
```
public abstract void setRewind(boolean value)
```

Detta attribut anger om effekten ska spolas tillbaka när den är klar. Läs/skriv boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Hämta effektsekvensen för den första sliden
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Hämta den första effekten i huvudsekvensen.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Aktivera effektens Timing/Rewind.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |