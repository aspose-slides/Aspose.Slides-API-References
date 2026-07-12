---
title: ITiming
second_title: Aspose.Slides Androidra a Java API Referenciában
description: Ábrázolja az animáció időzítését.
type: docs
url: /hu/com.aspose.slides/itiming/
---```
public interface ITiming
```

Ábrázolja az animáció időzítését.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | Leírja az időtartam gyorsulási viselkedés hatásának százalékát. |
| [setAccelerate(float value)](#setAccelerate-float-) | Leírja az időtartam gyorsulási viselkedés hatásának százalékát. |
| [getDecelerate()](#getDecelerate--) | Leírja az időtartam lassulási viselkedés hatásának százalékát. |
| [setDecelerate(float value)](#setDecelerate-float-) | Leírja az időtartam lassulási viselkedés hatásának százalékát. |
| [getAutoReverse()](#getAutoReverse--) | Leírja, hogy a animációt automatikusan visszafelé játsszák-e le a előre irányú lejátszás után. |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | Leírja, hogy a animációt automatikusan visszafelé játsszák-e le a előre irányú lejátszás után. |
| [getDuration()](#getDuration--) | Leírja az animáció hatás időtartamát. |
| [setDuration(float value)](#setDuration-float-) | Leírja az animáció hatás időtartamát. |
| [getRepeatCount()](#getRepeatCount--) | Leírja, hogy hányszor ismétlődjön a hatás. |
| [setRepeatCount(float value)](#setRepeatCount-float-) | Leírja, hogy hányszor ismétlődjön a hatás. |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | Ez az attribútum meghatározza, hogy a hatás a diára végéig ismétlődjön-e. |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | Ez az attribútum meghatározza, hogy a hatás a diára végéig ismétlődjön-e. |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | Ez az attribútum meghatározza, hogy a hatás a következő kattintásig ismétlődjön-e. |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | Ez az attribútum meghatározza, hogy a hatás a következő kattintásig ismétlődjön-e. |
| [getRepeatDuration()](#getRepeatDuration--) | Leírja, hogy hányszor ismétlődjön a hatás. |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | Leírja, hogy hányszor ismétlődjön a hatás. |
| [getRestart()](#getRestart--) | Megadja, hogy a hatás befejezés után újraindul-e. |
| [setRestart(int value)](#setRestart-int-) | Megadja, hogy a hatás befejezés után újraindul-e. |
| [getSpeed()](#getSpeed--) | Megadja a százalékos értéket, amellyel a időzítést felgyorsítják (vagy lelassítják). |
| [setSpeed(float value)](#setSpeed-float-) | Megadja a százalékos értéket, amellyel a időzítést felgyorsítják (vagy lelassítják). |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | Leírja a trigger után lévő késleltetési időt. |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | Leírja a trigger után lévő késleltetési időt. |
| [getTriggerType()](#getTriggerType--) | Leírja a trigger típusát. |
| [setTriggerType(int value)](#setTriggerType-int-) | Leírja a trigger típusát. |
| [getRewind()](#getRewind--) | Ez az attribútum meghatározza, hogy a hatás lejátszás befejezése után visszatekerődik-e. |
| [setRewind(boolean value)](#setRewind-boolean-) | Ez az attribútum meghatározza, hogy a hatás lejátszás befejezése után visszatekerődik-e. |

### getAccelerate() {#getAccelerate--}
```
public abstract float getAccelerate()
```

Leírja az időtartam gyorsulási viselkedés hatásának százalékát. Olvasás/írás float.

**Visszatér:**
float

### setAccelerate(float value) {#setAccelerate-float-}
```
public abstract void setAccelerate(float value)
```

Leírja az időtartam gyorsulási viselkedés hatásának százalékát. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public abstract float getDecelerate()
```

Leírja az időtartam lassulási viselkedés hatásának százalékát. Olvasás/írás float.

**Visszatér:**
float

### setDecelerate(float value) {#setDecelerate-float-}
```
public abstract void setDecelerate(float value)
```

Leírja az időtartam lassulási viselkedés hatásának százalékát. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public abstract boolean getAutoReverse()
```

Leírja, hogy a animációt automatikusan visszafelé játsszák-e le a előre irányú lejátszás után. Olvasás/írás boolean.

**Visszatér:**
boolean

### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public abstract void setAutoReverse(boolean value)
```

Leírja, hogy a animációt automatikusan visszafelé játsszák-e le a előre irányú lejátszás után. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public abstract float getDuration()
```

Leírja az animáció hatás időtartamát. Olvasás/írás float.

**Visszatér:**
float

### setDuration(float value) {#setDuration-float-}
```
public abstract void setDuration(float value)
```

Leírja az animáció hatás időtartamát. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public abstract float getRepeatCount()
```

Leírja, hogy hányszor ismétlődjön a hatás. Olvasás/írás float.

**Visszatér:**
float

### setRepeatCount(float value) {#setRepeatCount-float-}
```
public abstract void setRepeatCount(float value)
```

Leírja, hogy hányszor ismétlődjön a hatás. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public abstract boolean getRepeatUntilEndSlide()
```

Ez az attribútum meghatározza, hogy a hatás a diára végéig ismétlődjön-e. Olvasás/írás boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Az első dia effektussorozatának lekérése
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // A fő sorozat első effektusának lekérése.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Módosítsa a hatás Timing/Repeat értékét "Until End of Slide"-ra
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Visszatér:**
boolean

### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public abstract void setRepeatUntilEndSlide(boolean value)
```

Ez az attribútum meghatározza, hogy a hatás a diára végéig ismétlődjön-e. Olvasás/írás boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Az első dia effektussorozatának lekérése
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // A fő sorozat első effektusának lekérése.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Módosítsa a hatás Timing/Repeat értékét "Until End of Slide"-ra
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public abstract boolean getRepeatUntilNextClick()
```

Ez az attribútum meghatározza, hogy a hatás a következő kattintásig ismétlődjön-e. Olvasás/írás boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Az első dia effektussorozatának lekérése
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // A fő sorozat első effektusának lekérése.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Módosítsa a hatás Timing/Repeat értékét "Until Next Click"-ra
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Visszatér:**
boolean

### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public abstract void setRepeatUntilNextClick(boolean value)
```

Ez az attribútum meghatározza, hogy a hatás a következő kattintásig ismétlődjön-e. Olvasás/írás boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Az első dia effektussorozatának lekérése
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // A fő sorozat első effektusának lekérése.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Módosítsa a hatás Timing/Repeat értékét "Until Next Click"-ra
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getRepeatDuration() {#getRepeatDuration--}
```
public abstract float getRepeatDuration()
```

Leírja, hogy hányszor ismétlődjön a hatás. Olvasás/írás float.

**Visszatér:**
float

### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public abstract void setRepeatDuration(float value)
```

Leírja, hogy hányszor ismétlődjön a hatás. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public abstract int getRestart()
```

Megadja, hogy a hatás befejezés után újraindul-e. Olvasás/írás [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Visszatér:**
int

### setRestart(int value) {#setRestart-int-}
```
public abstract void setRestart(int value)
```

Megadja, hogy a hatás befejezés után újraindul-e. Olvasás/írás [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSpeed() {#getSpeed--}
```
public abstract float getSpeed()
```

Megadja a százalékos értéket, amellyel a időzítést felgyorsítják (vagy lelassítják). Olvasás/írás float.

**Visszatér:**
float

### setSpeed(float value) {#setSpeed-float-}
```
public abstract void setSpeed(float value)
```

Megadja a százalékos értéket, amellyel a időzítést felgyorsítják (vagy lelassítják). Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public abstract float getTriggerDelayTime()
```

Leírja a trigger után lévő késleltetési időt. Olvasás/írás float.

**Visszatér:**
float

### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public abstract void setTriggerDelayTime(float value)
```

Leírja a trigger után lévő késleltetési időt. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public abstract int getTriggerType()
```

Leírja a trigger típusát. Olvasás/írás [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Visszatér:**
int

### setTriggerType(int value) {#setTriggerType-int-}
```
public abstract void setTriggerType(int value)
```

Leírja a trigger típusát. Olvasás/írás [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public abstract boolean getRewind()
```

Ez az attribútum meghatározza, hogy a hatás lejátszás befejezése után visszatekerődik-e. Olvasás/írás boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Az első dia effektussorozatának lekérése
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // A fő sorozat első effektusának lekérése.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Kapcsolja be a hatás Timing/Rewind funkcióját.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Visszatér:**
boolean

### setRewind(boolean value) {#setRewind-boolean-}
```
public abstract void setRewind(boolean value)
```

Ez az attribútum meghatározza, hogy a hatás lejátszás befejezése után visszatekerődik-e. Olvasás/írás boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Az első dia effektussorozatának lekérése
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // A fő sorozat első effektusának lekérése.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Kapcsolja be a hatás Timing/Rewind funkcióját.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |