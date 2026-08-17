---
title: Timing
second_title: Aspose.Slides for Java API Referansı
description: Animasyon zamanlamasını temsil eder.
type: docs
url: /tr/com.aspose.slides/timing/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ITiming](../../com.aspose.slides/itiming), com.aspose.slides.IDOMObject
```
public class Timing implements ITiming, IDOMObject
```

Animasyon zamanlamasını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | Süre hızlandırma davranışı etkisinin yüzdesini açıklar. |
| [setAccelerate(float value)](#setAccelerate-float-) | Süre hızlandırma davranışı etkisinin yüzdesini açıklar. |
| [getDecelerate()](#getDecelerate--) | Süre yavaşlatma davranışı etkisinin yüzdesini açıklar. |
| [setDecelerate(float value)](#setDecelerate-float-) | Süre yavaşlatma davranışı etkisinin yüzdesini açıklar. |
| [getAutoReverse()](#getAutoReverse--) | İleri yönde oynatıldıktan sonra animasyonun otomatik olarak ters yönde oynatılıp oynatılmayacağını açıklar. |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | İleri yönde oynatıldıktan sonra animasyonun otomatik olarak ters yönde oynatılıp oynatılmayacağını açıklar. |
| [getDuration()](#getDuration--) | Animasyon etkisinin süresini açıklar. |
| [setDuration(float value)](#setDuration-float-) | Animasyon etkisinin süresini açıklar. |
| [getRepeatCount()](#getRepeatCount--) | Etkinin kaç kez tekrarlanması gerektiğini açıklar. |
| [setRepeatCount(float value)](#setRepeatCount-float-) | Etkinin kaç kez tekrarlanması gerektiğini açıklar. |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | Bu öznitelik, etkinin slayt sonuna kadar tekrarlanıp tekrarlanmayacağını belirtir. |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | Bu öznitelik, etkinin slayt sonuna kadar tekrarlanıp tekrarlanmayacağını belirtir. |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | Bu öznitelik, etkinin bir sonraki tıklamaya kadar tekrarlanıp tekrarlanmayacağını belirtir. |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | Bu öznitelik, etkinin bir sonraki tıklamaya kadar tekrarlanıp tekrarlanmayacağını belirtir. |
| [getRepeatDuration()](#getRepeatDuration--) | Etkinin kaç kez tekrarlanması gerektiğini açıklar. |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | Etkinin kaç kez tekrarlanması gerektiğini açıklar. |
| [getRestart()](#getRestart--) | Bir etkinin tamamlandıktan sonra yeniden başlatılıp başlatılmayacağını belirtir. |
| [setRestart(int value)](#setRestart-int-) | Bir etkinin tamamlandıktan sonra yeniden başlatılıp başlatılmayacağını belirtir. |
| [getRewind()](#getRewind--) | Bu öznitelik, etkinin çalması bittiğinde geri sarılıp sarılmayacağını belirtir. |
| [setRewind(boolean value)](#setRewind-boolean-) | Bu öznitelik, etkinin çalması bittiğinde geri sarılıp sarılmayacağını belirtir. |
| [getSpeed()](#getSpeed--) | Zamanlamayı hızlandırma (veya yavaşlatma) yüzde oranını belirtir. |
| [setSpeed(float value)](#setSpeed-float-) | Zamanlamayı hızlandırma (veya yavaşlatma) yüzde oranını belirtir. |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | Tetikleyiciden sonraki gecikme süresini açıklar. |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | Tetikleyiciden sonraki gecikme süresini açıklar. |
| [getTriggerType()](#getTriggerType--) | Tetikleyici türünü açıklar. |
| [setTriggerType(int value)](#setTriggerType-int-) | Tetikleyici türünü açıklar. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getAccelerate() {#getAccelerate--}
```
public final float getAccelerate()
```

Süre hızlandırma davranışı etkisinin yüzdesini açıklar. Okunur/Yazılabilir float.

**Döndürür:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public final void setAccelerate(float value)
```

Süre hızlandırma davranışı etkisinin yüzdesini açıklar. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public final float getDecelerate()
```

Süre yavaşlatma davranışı etkisinin yüzdesini açıklar. Okunur/Yazılabilir float.

**Döndürür:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public final void setDecelerate(float value)
```

Süre yavaşlatma davranışı etkisinin yüzdesini açıklar. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public final boolean getAutoReverse()
```

İleri yönde oynatıldıktan sonra animasyonun otomatik olarak ters yönde oynatılıp oynatılmayacağını açıklar. Okunur/Yazılabilir boolean.

**Döndürür:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public final void setAutoReverse(boolean value)
```

İleri yönde oynatıldıktan sonra animasyonun otomatik olarak ters yönde oynatılıp oynatılmayacağını açıklar. Okunur/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public final float getDuration()
```

Animasyon etkisinin süresini açıklar. Okunur/Yazılabilir float.

**Döndürür:**
float
### setDuration(float value) {#setDuration-float-}
```
public final void setDuration(float value)
```

Animasyon etkisinin süresini açıklar. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public final float getRepeatCount()
```

Etkinin kaç kez tekrarlanması gerektiğini açıklar. Okunur/Yazılabilir float.

**Döndürür:**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public final void setRepeatCount(float value)
```

Etkinin kaç kez tekrarlanması gerektiğini açıklar. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public final boolean getRepeatUntilEndSlide()
```

Bu öznitelik, etkinin slayt sonuna kadar tekrarlanıp tekrarlanmayacağını belirtir. Okunur/Yazılabilir boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slayt için efekt dizisini al
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ana dizinin ilk efektini al.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Etkinin Zamanlama/Tekrarını "Until End of Slide" olarak değiştir
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Döndürür:**
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public final void setRepeatUntilEndSlide(boolean value)
```

Bu öznitelik, etkinin slayt sonuna kadar tekrarlanıp tekrarlanmayacağını belirtir. Okunur/Yazılabilir boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slayt için efekt sırasını al
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ana sıralamanın ilk efektini al.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Efektin Zamanlama/Tekrarını "Slayt Sonuna Kadar" olarak değiştir
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public final boolean getRepeatUntilNextClick()
```

Bu öznitelik, etkinin bir sonraki tıklamaya kadar tekrarlanıp tekrarlanmayacağını belirtir. Okunur/Yazılabilir boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slayt için efekt sırasını al
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ana sıralamanın ilk efektini al.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Efektin Zamanlama/Tekrarını "Until Next Click" olarak değiştir
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Döndürür:**
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public final void setRepeatUntilNextClick(boolean value)
```

Bu öznitelik, etkinin bir sonraki tıklamaya kadar tekrarlanıp tekrarlanmayacağını belirtir. Okunur/Yazılabilir boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slayt için efekt dizisini al
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ana sıralamanın ilk efektini al.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Efektin Zamanlama/Tekrarını "Until Next Click" olarak değiştir
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getRepeatDuration() {#getRepeatDuration--}
```
public final float getRepeatDuration()
```

Etkinin kaç kez tekrarlanması gerektiğini açıklar. Okunur/Yazılabilir float.

**Döndürür:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public final void setRepeatDuration(float value)
```

Etkinin kaç kez tekrarlanması gerektiğini açıklar. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public final int getRestart()
```

Bir etkinin tamamlandıktan sonra yeniden başlatılıp başlatılmayacağını belirtir. Okunur/Yazılabilir [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Döndürür:**
int
### setRestart(int value) {#setRestart-int-}
```
public final void setRestart(int value)
```

Bir etkinin tamamlandıktan sonra yeniden başlatılıp başlatılmayacağını belirtir. Okunur/Yazılabilir [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public final boolean getRewind()
```

Bu öznitelik, etkinin çalması bittiğinde geri sarılıp sarılmayacağını belirtir. Okunur/Yazılabilir boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slayt için efekt dizisini al
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ana sıralamanın ilk efektini al.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Efektin Zamanlama/Rewind özelliğini etkinleştir.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Döndürür:**
boolean
### setRewind(boolean value) {#setRewind-boolean-}
```
public final void setRewind(boolean value)
```

Bu öznitelik, etkinin çalması bittiğinde geri sarılıp sarılmayacağını belirtir. Okunur/Yazılabilir boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slayt için efekt dizisini al
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ana sıralamanın ilk efektini al.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Efektin Zamanlama/Rewind özelliğini etkinleştir.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSpeed() {#getSpeed--}
```
public final float getSpeed()
```

Zamanlamayı hızlandırma (veya yavaşlatma) yüzde oranını belirtir. Okunur/Yazılabilir float.

**Döndürür:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public final void setSpeed(float value)
```

Zamanlamayı hızlandırma (veya yavaşlatma) yüzde oranını belirtir. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public final float getTriggerDelayTime()
```

Tetikleyiciden sonraki gecikme süresini açıklar. Okunur/Yazılabilir float.

**Döndürür:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public final void setTriggerDelayTime(float value)
```

Tetikleyiciden sonraki gecikme süresini açıklar. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public final int getTriggerType()
```

Tetikleyici türünü açıklar. Okunur/Yazılabilir [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Döndürür:**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public final void setTriggerType(int value)
```

Tetikleyici türünü açıklar. Okunur/Yazılabilir [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject