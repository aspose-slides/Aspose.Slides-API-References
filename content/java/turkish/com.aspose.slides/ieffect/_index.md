---
title: IEffect
second_title: Aspose.Slides for Java API Referansı
description: Animasyon efektini temsil eder.
type: docs
url: /tr/com.aspose.slides/ieffect/
---```
public interface IEffect
```

Animasyon efektini temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getSequence()](#getSequence--) | Bir efekt için bir dizi döndürür. |
| [getTextAnimation()](#getTextAnimation--) | Metin animasyonunu döndürür. |
| [getPresetClassType()](#getPresetClassType--) | Efekt sınıfını tanımlar. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Efekt sınıfını tanımlar. |
| [getType()](#getType--) | Efekt tipini tanımlar. |
| [setType(int value)](#setType-int-) | Efekt tipini tanımlar. |
| [getSubtype()](#getSubtype--) | Efekt alt tipini tanımlar. |
| [setSubtype(int value)](#setSubtype-int-) | Efekt alt tipini tanımlar. |
| [getBehaviors()](#getBehaviors--) | Efekt için davranış koleksiyonunu döndürür. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Efekt için davranış koleksiyonunu döndürür. |
| [getTiming()](#getTiming--) | Efekt için zamanlama değerini tanımlar. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Efekt için zamanlama değerini tanımlar. |
| [getTargetShape()](#getTargetShape--) | Efekt için hedef şekli döndürür. |
| [getSound()](#getSound--) | Efekt için gömülü sesi tanımladı. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Efekt için gömülü sesi tanımladı. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Bu öznitelik, animasyon efektinin önceki sesi durdurup durdurmadığını belirtir. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Bu öznitelik, animasyon efektinin önceki sesi durdurup durdurmadığını belirtir. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Efekt için bir sonrası animasyon tipini tanımladı. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Efekt için bir sonrası animasyon tipini tanımladı. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Efekt için bir sonrası animasyon rengini tanımladı. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Efekt için bir sonrası animasyon rengini tanımladı. |
| [getAnimateTextType()](#getAnimateTextType--) | Efekt için bir metin animasyon tipi tanımlar. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Efekt için bir metin animasyon tipi tanımlar. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Animasyonlu metin bölümleri (kelimeler veya harfler) arasındaki gecikmeyi tanımlar. |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Animasyonlu metin bölümleri (kelimeler veya harfler) arasındaki gecikmeyi tanımlar. |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```

Bir efekt için bir dizi döndürür. Salt okunur [ISequence](../../com.aspose.slides/isequence).

**Döndürür:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```

Metin animasyonunu döndürür. Salt okunur [ITextAnimation](../../com.aspose.slides/itextanimation).

**Döndürür:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```

Efekt sınıfını tanımlar. Okunabilir/Yazılabilir [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Döndürür:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```

Efekt sınıfını tanımlar. Okunabilir/Yazılabilir [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```

Efekt tipini tanımlar. Okunabilir/Yazılabilir [EffectType](../../com.aspose.slides/effecttype).

**Döndürür:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Efekt tipini tanımlar. Okunabilir/Yazılabilir [EffectType](../../com.aspose.slides/effecttype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```

Efekt alt tipini tanımlar. Okunabilir/Yazılabilir [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Döndürür:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```

Efekt alt tipini tanımlar. Okunabilir/Yazılabilir [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```

Efekt için davranış koleksiyonunu döndürür. Okunabilir/Yazılabilir [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Döndürür:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```

Efekt için davranış koleksiyonunu döndürür. Okunabilir/Yazılabilir [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Efekt için zamanlama değerini tanımlar. Okunabilir/Yazılabilir [ITiming](../../com.aspose.slides/itiming).

**Döndürür:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Efekt için zamanlama değerini tanımlar. Okunabilir/Yazılabilir [ITiming](../../com.aspose.slides/itiming).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```

Efekt için hedef şekli döndürür. Salt okunur [IShape](../../com.aspose.slides/ishape).

**Döndürür:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Efekt için gömülü sesi tanımladı. Okunabilir/Yazılabilir [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Slayt için efekt sırasını alır
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Efekt sesini byte dizisi olarak çıkarır
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Döndürür:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Efekt için gömülü sesi tanımladı. Okunabilir/Yazılabilir [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Slayt için efekt sırasını alır
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Efekt sesini byte dizisi olarak çıkarır
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```

Bu öznitelik, animasyon efektinin önceki sesi durdurup durdurmadığını belirtir. Okunabilir/Yazılabilir boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slaydın ilk efektini al.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // İkinci slaydın ilk efektini al.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // İkinci efektin Gelişmeler/Sesini "Stop Previous Sound" olarak değiştir
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Döndürür:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public abstract void setStopPreviousSound(boolean value)
```

Bu öznitelik, animasyon efektinin önceki sesi durdurup durdurmadığını belirtir. Okunabilir/Yazılabilir boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slaydın ilk efektini al.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // İkinci slaydın ilk efektini al.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // İkinci efektin Gelişmeler/Sesini "Stop Previous Sound" olarak değiştir
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```

Efekt için bir sonrası animasyon tipini tanımladı. Okunabilir/Yazılabilir AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slaydın ilk efektini al.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Efektin After animation'ını "Hide on Next Mouse Click" olarak değiştir
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Döndürür:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```

Efekt için bir sonrası animasyon tipini tanımladı. Okunabilir/Yazılabilir AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slaydın ilk efektini al.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Efektin After animation'ını "Hide on Next Mouse Click" olarak değiştir
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```

Efekt için bir sonrası animasyon rengini tanımladı. Okunabilir/Yazılabilir [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slaydın ilk efektini al.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Etkinin After animation tipini "Color" olarak değiştir
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Etkinin After animation rengini ayarla.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```

Efekt için bir sonrası animasyon rengini tanımladı. Okunabilir/Yazılabilir [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slaydın ilk efektini al.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Etkinin After animation tipini "Color" olarak değiştir
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Etkinin After animation rengini ayarla.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```

Efekt için bir metin animasyon tipi tanımlar. Şekil metni harf, kelime veya tümü birden animasyonlanabilir. Okunabilir/Yazılabilir AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // İlk slaydın ilk efektini al.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Etkinin Animate text tipini "By letter" olarak değiştir
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Döndürür:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```

Efekt için bir metin animasyon tipi tanımlar. Şekil metni harf, kelime veya tümü birden animasyonlanabilir. Okunabilir/Yazılabilir AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // İlk slaydın ilk efektini al.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Etkinin Animate text tipini "By letter" olarak değiştir
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```

Animasyonlu metin bölümleri (kelimeler veya harfler) arasındaki gecikmeyi tanımlar. Pozitif bir değer, efekt süresinin yüzdesini belirtir. Negatif bir değer ise gecikmeyi saniye olarak belirtir. Okunabilir/Yazılabilir float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // İlk slaydın ilk efektini al.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Etkinin Animate text tipini "By word" olarak değiştir
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Animasyonlu metin bölümleri arasındaki gecikmeyi efekt süresinin %20'si olarak ayarla.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Döndürür:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```

Animasyonlu metin bölümleri (kelimeler veya harfler) arasındaki gecikmeyi tanımlar. Pozitif bir değer, efekt süresinin yüzdesini belirtir. Negatif bir değer ise gecikmeyi saniye olarak belirtir. Okunabilir/Yazılabilir float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // İlk slaydın ilk efektini al.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Etkinin Animate text tipini "By word" olarak değiştir
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Animasyonlu metin bölümleri arasındaki gecikmeyi efekt süresinin %20'si olarak ayarla.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |