---
title: ITiming
second_title: Aspose.Slides for Java API Referansı
description: Animasyon zamanlamasını temsil eder.
type: docs
url: /tr/com.aspose.slides/itiming/
---```
public interface ITiming
```

Animasyon zamanlamasını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | Süre hızlandırma davranışı etkisinin yüzdesini açıklar. |
| [setAccelerate(float value)](#setAccelerate-float-) | Süre hızlandırma davranışı etkisinin yüzdesini açıklar. |
| [getDecelerate()](#getDecelerate--) | Süre yavaşlatma davranışı etkisinin yüzdesini açıklar. |
| [setDecelerate(float value)](#setDecelerate-float-) | Süre yavaşlatma davranışı etkisinin yüzdesini açıklar. |
| [getAutoReverse()](#getAutoReverse--) | Animasyonu ileri yönde oynattıktan sonra otomatik olarak ters yönde oynatılıp oynatılmayacağını tanımlar. |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | Animasyonu ileri yönde oynattıktan sonra otomatik olarak ters yönde oynatılıp oynatılmayacağını tanımlar. |
| [getDuration()](#getDuration--) | Animasyon etkisinin süresini tanımlar. |
| [setDuration(float value)](#setDuration-float-) | Animasyon etkisinin süresini tanımlar. |
| [getRepeatCount()](#getRepeatCount--) | Etkinin tekrarlanması gereken sayıyı tanımlar. |
| [setRepeatCount(float value)](#setRepeatCount-float-) | Etkinin tekrarlanması gereken sayıyı tanımlar. |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | Bu özellik, etkinin slayt sonuna kadar tekrarlanıp tekrarlanmayacağını belirtir. |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | Bu özellik, etkinin slayt sonuna kadar tekrarlanıp tekrarlanmayacağını belirtir. |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | Bu özellik, etkinin bir sonraki tıklamaya kadar tekrarlanıp tekrarlanmayacağını belirtir. |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | Bu özellik, etkinin bir sonraki tıklamaya kadar tekrarlanıp tekrarlanmayacağını belirtir. |
| [getRepeatDuration()](#getRepeatDuration--) | Etkinin tekrarlanması gereken sayıyı tanımlar. |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | Etkinin tekrarlanması gereken sayıyı tanımlar. |
| [getRestart()](#getRestart--) | Etkinin tamamlandıktan sonra yeniden başlatılıp başlatılmayacağını belirtir. |
| [setRestart(int value)](#setRestart-int-) | Etkinin tamamlandıktan sonra yeniden başlatılıp başlatılmayacağını belirtir. |
| [getSpeed()](#getSpeed--) | Zamanlamanın ne kadar hızlandırılacağını (veya yavaşlatılacağını) yüzde olarak belirtir. |
| [setSpeed(float value)](#setSpeed-float-) | Zamanlamanın ne kadar hızlandırılacağını (veya yavaşlatılacağını) yüzde olarak belirtir. |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | Tetikleyiciden sonraki gecikme süresini tanımlar. |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | Tetikleyiciden sonraki gecikme süresini tanımlar. |
| [getTriggerType()](#getTriggerType--) | Tetikleyici türünü tanımlar. |
| [setTriggerType(int value)](#setTriggerType-int-) | Tetikleyici türünü tanımlar. |
| [getRewind()](#getRewind--) | Bu özellik, etkinin çalma tamamlandığında geri sarılıp sarılmayacağını belirtir. |
| [setRewind(boolean value)](#setRewind-boolean-) | Bu özellik, etkinin çalma tamamlandığında geri sarılıp sarılmayacağını belirtir. |
### getAccelerate() {#getAccelerate--}
```
public abstract float getAccelerate()
```

Süre hızlandırma davranışı etkisinin yüzdesini açıklar. Okunur/Yazılır float.

**Döndürür:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public abstract void setAccelerate(float value)
```

Süre hızlandırma davranışı etkisinin yüzdesini açıklar. Okunur/Yazılır float.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |
### getDecelerate() {#getDecelerate--}
```
public abstract float getDecelerate()
```

Süre yavaşlatma davranışı etkisinin yüzdesini açıklar. Okunur/Yazılır float.

**Döndürür:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public abstract void setDecelerate(float value)
```

Süre yavaşlatma davranışı etkisinin yüzdesini açıklar. Okunur/Yazılır float.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |
### getAutoReverse() {#getAutoReverse--}
```
public abstract boolean getAutoReverse()
```

Animasyonu ileri yönde oynattıktan sonra otomatik olarak ters yönde oynatılıp oynatılmayacağını tanımlar. Okunur/Yazılır boolean.

**Döndürür:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public abstract void setAutoReverse(boolean value)
```

Animasyonu ileri yönde oynattıktan sonra otomatik olarak ters yönde oynatılıp oynatılmayacağını tanımlar. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getDuration() {#getDuration--}
```
public abstract float getDuration()
```

Animasyon etkisinin süresini tanımlar. Okunur/Yazılır float.

**Döndürür:**
float
### setDuration(float value) {#setDuration-float-}
```
public abstract void setDuration(float value)
```

Animasyon etkisinin süresini tanımlar. Okunur/Yazılır float.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |
### getRepeatCount() {#getRepeatCount--}
```
public abstract float getRepeatCount()
```

Etkinin tekrarlanması gereken sayıyı tanımlar. Okunur/Yazılır float.

**Döndürür:**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public abstract void setRepeatCount(float value)
```

Etkinin tekrarlanması gereken sayıyı tanımlar. Okunur/Yazılır float.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |
### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public abstract boolean getRepeatUntilEndSlide()
```

Bu özellik, etkinin slayt sonuna kadar tekrarlanıp tekrarlanmayacağını belirtir. Okunur/Yazılır boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slayt için efekt dizisini al
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ana dizinin ilk efektini al.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Etkinin Timing/Repeat özelliğini "Slayt Sonuna Kadar" olarak değiştir
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Döndürür:**
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public abstract void setRepeatUntilEndSlide(boolean value)
```

Bu özellik, etkinin slayt sonuna kadar tekrarlanıp tekrarlanmayacağını belirtir. Okunur/Yazılır boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slayt için efekt dizisini al
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ana dizinin ilk efektini al.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Etkinin Timing/Repeat özelliğini "Slayt Sonuna Kadar" olarak değiştir
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public abstract boolean getRepeatUntilNextClick()
```

Bu özellik, etkinin bir sonraki tıklamaya kadar tekrarlanıp tekrarlanmayacağını belirtir. Okunur/Yazılır boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slayt için efekt dizisini al
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ana dizinin ilk efektini al.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Etkinin Timing/Repeat özelliğini "Bir Sonraki Tıklamaya Kadar" olarak değiştir
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Döndürür:**
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public abstract void setRepeatUntilNextClick(boolean value)
```

Bu özellik, etkinin bir sonraki tıklamaya kadar tekrarlanıp tekrarlanmayacağını belirtir. Okunur/Yazılır boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slayt için efekt dizisini al
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ana dizinin ilk efektini al.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Etkinin Timing/Repeat özelliğini "Bir Sonraki Tıklamaya Kadar" olarak değiştir
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getRepeatDuration() {#getRepeatDuration--}
```
public abstract float getRepeatDuration()
```

Etkinin tekrarlanması gereken sayıyı tanımlar. Okunur/Yazılır float.

**Döndürür:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public abstract void setRepeatDuration(float value)
```

Etkinin tekrarlanması gereken sayıyı tanımlar. Okunur/Yazılır float.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |
### getRestart() {#getRestart--}
```
public abstract int getRestart()
```

Etkinin tamamlandıktan sonra yeniden başlatılıp başlatılmayacağını belirtir. Okunur/Yazılır [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Döndürür:**
int
### setRestart(int value) {#setRestart-int-}
```
public abstract void setRestart(int value)
```

Etkinin tamamlandıktan sonra yeniden başlatılıp başlatılmayacağını belirtir. Okunur/Yazılır [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |
### getSpeed() {#getSpeed--}
```
public abstract float getSpeed()
```

Zamanlamanın ne kadar hızlandırılacağını (veya yavaşlatılacağını) yüzde olarak belirtir. Okunur/Yazılır float.

**Döndürür:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public abstract void setSpeed(float value)
```

Zamanlamanın ne kadar hızlandırılacağını (veya yavaşlatılacağını) yüzde olarak belirtir. Okunur/Yazılır float.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |
### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public abstract float getTriggerDelayTime()
```

Tetikleyiciden sonraki gecikme süresini tanımlar. Okunur/Yazılır float.

**Döndürür:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public abstract void setTriggerDelayTime(float value)
```

Tetikleyiciden sonraki gecikme süresini tanımlar. Okunur/Yazılır float.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |
### getTriggerType() {#getTriggerType--}
```
public abstract int getTriggerType()
```

Tetikleyici türünü tanımlar. Okunur/Yazılır [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Döndürür:**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public abstract void setTriggerType(int value)
```

Tetikleyici türünü tanımlar. Okunur/Yazılır [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |
### getRewind() {#getRewind--}
```
public abstract boolean getRewind()
```

Bu özellik, etkinin çalma tamamlandığında geri sarılıp sarılmayacağını belirtir. Okunur/Yazılır boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slayt için efekt dizisini al
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ana dizinin ilk efektini al.
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
public abstract void setRewind(boolean value)
```

Bu özellik, etkinin çalma tamamlandığında geri sarılıp sarılmayacağını belirtir. Okunur/Yazılır boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slayt için efekt dizisini al
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Ana dizinin ilk efektini al.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Efektin Timing/Rewind özelliğini aç.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |