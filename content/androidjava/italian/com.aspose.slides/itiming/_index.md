---
title: ITiming
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta il timing dell'animazione.
type: docs
url: /it/com.aspose.slides/itiming/
---```
public interface ITiming
```

Rappresenta il timing dell'animazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | Descrive la percentuale della durata dell'effetto di accelerazione. |
| [setAccelerate(float value)](#setAccelerate-float-) | Descrive la percentuale della durata dell'effetto di accelerazione. |
| [getDecelerate()](#getDecelerate--) | Descrive la percentuale della durata dell'effetto di decelerazione. |
| [setDecelerate(float value)](#setDecelerate-float-) | Descrive la percentuale della durata dell'effetto di decelerazione. |
| [getAutoReverse()](#getAutoReverse--) | Descrive se riprodurre automaticamente l'animazione al contrario dopo averla riprodotta in avanti. |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | Descrive se riprodurre automaticamente l'animazione al contrario dopo averla riprodotta in avanti. |
| [getDuration()](#getDuration--) | Descrive la durata dell'effetto di animazione. |
| [setDuration(float value)](#setDuration-float-) | Descrive la durata dell'effetto di animazione. |
| [getRepeatCount()](#getRepeatCount--) | Descrive il numero di volte in cui l'effetto deve ripetersi. |
| [setRepeatCount(float value)](#setRepeatCount-float-) | Descrive il numero di volte in cui l'effetto deve ripetersi. |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | Questo attributo specifica se l'effetto si ripeterà fino alla fine della diapositiva. |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | Questo attributo specifica se l'effetto si ripeterà fino alla fine della diapositiva. |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | Questo attributo specifica se l'effetto si ripeterà fino al prossimo clic. |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | Questo attributo specifica se l'effetto si ripeterà fino al prossimo clic. |
| [getRepeatDuration()](#getRepeatDuration--) | Descrive il numero di volte in cui l'effetto deve ripetersi. |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | Descrive il numero di volte in cui l'effetto deve ripetersi. |
| [getRestart()](#getRestart--) | Specifica se un effetto deve riavviarsi al completamento. |
| [setRestart(int value)](#setRestart-int-) | Specifica se un effetto deve riavviarsi al completamento. |
| [getSpeed()](#getSpeed--) | Specifica la percentuale con cui velocizzare (o rallentare) il timing. |
| [setSpeed(float value)](#setSpeed-float-) | Specifica la percentuale con cui velocizzare (o rallentare) il timing. |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | Descrive il tempo di ritardo dopo il trigger. |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | Descrive il tempo di ritardo dopo il trigger. |
| [getTriggerType()](#getTriggerType--) | Descrive il tipo di trigger. |
| [setTriggerType(int value)](#setTriggerType-int-) | Descrive il tipo di trigger. |
| [getRewind()](#getRewind--) | Questo attributo specifica se l'effetto si riavvolgerà al termine della riproduzione. |
| [setRewind(boolean value)](#setRewind-boolean-) | Questo attributo specifica se l'effetto si riavvolgerà al termine della riproduzione. |
### getAccelerate() {#getAccelerate--}
```
public abstract float getAccelerate()
```

Descrive la percentuale della durata dell'effetto di accelerazione. Lettura/scrittura float.

**Restituisce:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public abstract void setAccelerate(float value)
```

Descrive la percentuale della durata dell'effetto di accelerazione. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getDecelerate() {#getDecelerate--}
```
public abstract float getDecelerate()
```

Descrive la percentuale della durata dell'effetto di decelerazione. Lettura/scrittura float.

**Restituisce:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public abstract void setDecelerate(float value)
```

Descrive la percentuale della durata dell'effetto di decelerazione. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getAutoReverse() {#getAutoReverse--}
```
public abstract boolean getAutoReverse()
```

Descrive se riprodurre automaticamente l'animazione al contrario dopo averla riprodotta in avanti. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public abstract void setAutoReverse(boolean value)
```

Descrive se riprodurre automaticamente l'animazione al contrario dopo averla riprodotta in avanti. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getDuration() {#getDuration--}
```
public abstract float getDuration()
```

Descrive la durata dell'effetto di animazione. Lettura/scrittura float.

**Restituisce:**
float
### setDuration(float value) {#setDuration-float-}
```
public abstract void setDuration(float value)
```

Descrive la durata dell'effetto di animazione. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getRepeatCount() {#getRepeatCount--}
```
public abstract float getRepeatCount()
```

Descrive il numero di volte in cui l'effetto deve ripetersi. Lettura/scrittura float.

**Restituisce:**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public abstract void setRepeatCount(float value)
```

Descrive il numero di volte in cui l'effetto deve ripetersi. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public abstract boolean getRepeatUntilEndSlide()
```

Questo attributo specifica se l'effetto si ripeterà fino alla fine della diapositiva. Lettura/scrittura boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Ottieni la sequenza di effetti per la prima diapositiva
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ottieni il primo effetto della sequenza principale.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Modifica il timing/ripetizione dell'effetto a "Until End of Slide"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Restituisce:**
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public abstract void setRepeatUntilEndSlide(boolean value)
```

Questo attributo specifica se l'effetto si ripeterà fino alla fine della diapositiva. Lettura/scrittura boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Ottieni la sequenza di effetti per la prima diapositiva
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ottieni il primo effetto della sequenza principale.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Modifica il timing/ripetizione dell'effetto a "Until End of Slide"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public abstract boolean getRepeatUntilNextClick()
```

Questo attributo specifica se l'effetto si ripeterà fino al prossimo clic. Lettura/scrittura boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Ottieni la sequenza di effetti per la prima diapositiva
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ottieni il primo effetto della sequenza principale.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Modifica il timing/ripetizione dell'effetto a "Until Next Click"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Restituisce:**
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public abstract void setRepeatUntilNextClick(boolean value)
```

Questo attributo specifica se l'effetto si ripeterà fino al prossimo clic. Lettura/scrittura boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Ottieni la sequenza di effetti per la prima diapositiva
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ottieni il primo effetto della sequenza principale.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Modifica il timing/ripetizione dell'effetto a "Until Next Click"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getRepeatDuration() {#getRepeatDuration--}
```
public abstract float getRepeatDuration()
```

Descrive il numero di volte in cui l'effetto deve ripetersi. Lettura/scrittura float.

**Restituisce:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public abstract void setRepeatDuration(float value)
```

Descrive il numero di volte in cui l'effetto deve ripetersi. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getRestart() {#getRestart--}
```
public abstract int getRestart()
```

Specifica se un effetto deve riavviarsi al completamento. Lettura/scrittura [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Restituisce:**
int
### setRestart(int value) {#setRestart-int-}
```
public abstract void setRestart(int value)
```

Specifica se un effetto deve riavviarsi al completamento. Lettura/scrittura [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getSpeed() {#getSpeed--}
```
public abstract float getSpeed()
```

Specifica la percentuale con cui velocizzare (o rallentare) il timing. Lettura/scrittura float.

**Restituisce:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public abstract void setSpeed(float value)
```

Specifica la percentuale con cui velocizzare (o rallentare) il timing. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public abstract float getTriggerDelayTime()
```

Descrive il tempo di ritardo dopo il trigger. Lettura/scrittura float.

**Restituisce:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public abstract void setTriggerDelayTime(float value)
```

Descrive il tempo di ritardo dopo il trigger. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getTriggerType() {#getTriggerType--}
```
public abstract int getTriggerType()
```

Descrive il tipo di trigger. Lettura/scrittura [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Restituisce:**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public abstract void setTriggerType(int value)
```

Descrive il tipo di trigger. Lettura/scrittura [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getRewind() {#getRewind--}
```
public abstract boolean getRewind()
```

Questo attributo specifica se l'effetto si riavvolgerà al termine della riproduzione. Lettura/scrittura boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Ottieni la sequenza di effetti per la prima diapositiva
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ottieni il primo effetto della sequenza principale.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Attiva il timing/riavvolgimento dell'effetto.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Restituisce:**
boolean
### setRewind(boolean value) {#setRewind-boolean-}
```
public abstract void setRewind(boolean value)
```

Questo attributo specifica se l'effetto si riavvolgerà al termine della riproduzione. Lettura/scrittura boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Ottieni la sequenza di effetti per la prima diapositiva
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ottieni il primo effetto della sequenza principale.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Attiva il timing/riavvolgimento dell'effetto.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |