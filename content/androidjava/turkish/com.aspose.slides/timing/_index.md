---
title: Timing
second_title: Aspose.Slides for Android via Java API Referansı
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
| [getAccelerate()](#getAccelerate--) | Süre hızlanma davranışı etkisinin yüzdesini tanımlar. |
| [setAccelerate(float value)](#setAccelerate-float-) | Süre hızlanma davranışı etkisinin yüzdesini tanımlar. |
| [getDecelerate()](#getDecelerate--) | Süre yavaşlama davranışı etkisinin yüzdesini tanımlar. |
| [setDecelerate(float value)](#setDecelerate-float-) | Süre yavaşlama davranışı etkisinin yüzdesini tanımlar. |
| [getAutoReverse()](#getAutoReverse--) | Etkinin ileri yönde oynatıldıktan sonra otomatik olarak ters yönde oynatılıp oynatılmayacağını belirtir. |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | Etkinin ileri yönde oynatıldıktan sonra otomatik olarak ters yönde oynatılıp oynatılmayacağını belirtir. |
| [getDuration()](#getDuration--) | Animasyon etkisinin süresini tanımlar. |
| [setDuration(float value)](#setDuration-float-) | Animasyon etkisinin süresini tanımlar. |
| [getRepeatCount()](#getRepeatCount--) | Etkinin tekrar sayısını tanımlar. |
| [setRepeatCount(float value)](#setRepeatCount-float-) | Etkinin tekrar sayısını tanımlar. |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | Bu öznitelik, etkinin slayt sonuna kadar tekrar edip etmeyeceğini belirtir. |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | Bu öznitelik, etkinin slayt sonuna kadar tekrar edip etmeyeceğini belirtir. |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | Bu öznitelik, etkinin bir sonraki tıklamaya kadar tekrar edip etmeyeceğini belirtir. |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | Bu öznitelik, etkinin bir sonraki tıklamaya kadar tekrar edip etmeyeceğini belirtir. |
| [getRepeatDuration()](#getRepeatDuration--) | Etkinin tekrar sayısını tanımlar. |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | Etkinin tekrar sayısını tanımlar. |
| [getRestart()](#getRestart--) | Etkinin tamamlandıktan sonra yeniden başlayıp başlamayacağını belirtir. |
| [setRestart(int value)](#setRestart-int-) | Etkinin tamamlandıktan sonra yeniden başlayıp başlamayacağını belirtir. |
| [getRewind()](#getRewind--) | Bu öznitelik, etkinin çalma tamamlandığında geri sarılıp sarılmayacağını belirtir. |
| [setRewind(boolean value)](#setRewind-boolean-) | Bu öznitelik, etkinin çalma tamamlandığında geri sarılıp sarılmayacağını belirtir. |
| [getSpeed()](#getSpeed--) | Zamanlamayı ne kadar hızlandırmak (veya yavaşlatmak) istediğinizi yüzde olarak belirtir. |
| [setSpeed(float value)](#setSpeed-float-) | Zamanlamayı ne kadar hızlandırmak (veya yavaşlatmak) istediğinizi yüzde olarak belirtir. |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | Tetikleyiciden sonraki gecikme süresini tanımlar. |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | Tetikleyiciden sonraki gecikme süresini tanımlar. |
| [getTriggerType()](#getTriggerType--) | Tetikleme türünü tanımlar. |
| [setTriggerType(int value)](#setTriggerType-int-) | Tetikleme türünü tanımlar. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getAccelerate() {#getAccelerate--}
```
public final float getAccelerate()
```

Süre hızlanma davranışı etkisinin yüzdesini tanımlar. Okunur/Yazılabilir float.

**Döndürür:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public final void setAccelerate(float value)
```

Süre hızlanma davranışı etkisinin yüzdesini tanımlar. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public final float getDecelerate()
```

Süre yavaşlama davranışı etkisinin yüzdesini tanımlar. Okunur/Yazılabilir float.

**Döndürür:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public final void setDecelerate(float value)
```

Süre yavaşlama davranışı etkisinin yüzdesini tanımlar. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public final boolean getAutoReverse()
```

Etkinin ileri yönde oynatıldıktan sonra otomatik olarak ters yönde oynatılıp oynatılmayacağını belirtir. Okunur/Yazılabilir boolean.

**Döndürür:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public final void setAutoReverse(boolean value)
```

Etkinin ileri yönde oynatıldıktan sonra otomatik olarak ters yönde oynatılıp oynatılmayacağını belirtir. Okunur/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public final float getDuration()
```

Animasyon etkisinin süresini tanımlar. Okunur/Yazılabilir float.

**Döndürür:**
float
### setDuration(float value) {#setDuration-float-}
```
public final void setDuration(float value)
```

Animasyon etkisinin süresini tanımlar. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public final float getRepeatCount()
```

Etkinin tekrar sayısını tanımlar. Okunur/Yazılabilir float.

**Döndürür:**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public final void setRepeatCount(float value)
```

Etkinin tekrar sayısını tanımlar. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public final boolean getRepeatUntilEndSlide()
```

Bu öznitelik, etkinin slayt sonuna kadar tekrar edip etmeyeceğini belirtir. Okunur/Yazılabilir boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the effects sequence for the first slide
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Get the first effect of main sequence.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Change the effect Timing/Repeat to "Until End of Slide"
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

Bu öznitelik, etkinin slayt sonuna kadar tekrar edip etmeyeceğini belirtir. Okunur/Yazılabilir boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slayt için efekt sırasını al
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ana sıranın ilk efektini al.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Efektin Timing/Repeat'ini "Slayt Sonuna Kadar" olarak değiştir
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

Bu öznitelik, etkinin bir sonraki tıklamaya kadar tekrar edip etmeyeceğini belirtir. Okunur/Yazılabilir boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slayt için efekt sırasını al
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ana sıranın ilk efektini al.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Efektin Timing/Repeat'ini "Until Next Click" olarak değiştir
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

Bu öznitelik, etkinin bir sonraki tıklamaya kadar tekrar edip etmeyeceğini belirtir. Okunur/Yazılabilir boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slayt için efekt sırasını al
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ana sıranın ilk efektini al.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Efektin Timing/Repeat'ini "Until Next Click" olarak değiştir
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

Etkinin tekrar sayısını tanımlar. Okunur/Yazılabilir float.

**Döndürür:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public final void setRepeatDuration(float value)
```

Etkinin tekrar sayısını tanımlar. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public final int getRestart()
```

Etkinin tamamlandıktan sonra yeniden başlayıp başlamayacağını belirtir. Okunur/Yazılabilir [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Döndürür:**
int
### setRestart(int value) {#setRestart-int-}
```
public final void setRestart(int value)
```

Etkinin tamamlandıktan sonra yeniden başlayıp başlamayacağını belirtir. Okunur/Yazılabilir [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public final boolean getRewind()
```

Bu öznitelik, etkinin çalma tamamlandığında geri sarılıp sarılmayacağını belirtir. Okunur/Yazılabilir boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slayt için efekt sırasını al
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ana sıranın ilk efektini al.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Efektin Timing/Rewind özelliğini aç.
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

Bu öznitelik, etkinin çalma tamamlandığında geri sarılıp sarılmayacağını belirtir. Okunur/Yazılabilir boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slayt için efekt sırasını al
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ana sıranın ilk efektini al.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Efektin Timing/Rewind özelliğini aç.
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

Zamanlamayı ne kadar hızlandırmak (veya yavaşlatmak) istediğinizi yüzde olarak belirtir. Okunur/Yazılabilir float.

**Döndürür:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public final void setSpeed(float value)
```

Zamanlamayı ne kadar hızlandırmak (veya yavaşlatmak) istediğinizi yüzde olarak belirtir. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public final float getTriggerDelayTime()
```

Tetikleyiciden sonraki gecikme süresini tanımlar. Okunur/Yazılabilir float.

**Döndürür:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public final void setTriggerDelayTime(float value)
```

Tetikleyiciden sonraki gecikme süresini tanımlar. Okunur/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public final int getTriggerType()
```

Tetikleme türünü tanımlar. Okunur/Yazılabilir [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Döndürür:**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public final void setTriggerType(int value)
```

Tetikleme türünü tanımlar. Okunur/Yazılabilir [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject