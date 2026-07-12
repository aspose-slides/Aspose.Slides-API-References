---
title: Effect
second_title: Aspose.Slides for Android via Java API Referansı
description: Animasyon etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/effect/
---
**Kalıtım:**  
java.lang.Object

**Tüm Uygulanan Arayüzler:**  
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject  
```
public class Effect implements IEffect, IDOMObject
```

Animasyon efektini temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSequence()](#getSequence--) | Efekt için bir sıralama döndürür. |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation Salt okunur [ITextAnimation](../../com.aspose.slides/itextanimation). |
| [getPresetClassType()](#getPresetClassType--) | Efektin sınıfını tanımlar. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Efektin sınıfını tanımlar. |
| [getType()](#getType--) | Efektin tipini tanımlar. |
| [setType(int value)](#setType-int-) | Efektin tipini tanımlar. |
| [getSubtype()](#getSubtype--) | Efektin alt tipini tanımlar. |
| [setSubtype(int value)](#setSubtype-int-) | Efektin alt tipini tanımlar. |
| [getBehaviors()](#getBehaviors--) | Efekt için davranış koleksiyonunu döndürür. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Efekt için davranış koleksiyonunu döndürür. |
| [getTiming()](#getTiming--) | Efekt için zamanlama değerini tanımlar. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Efekt için zamanlama değerini tanımlar. |
| [getTargetShape()](#getTargetShape--) | Efekt için hedef şekli döndürür. |
| [getSound()](#getSound--) | Efekt için gömülü sesi tanımlar. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Efekt için gömülü sesi tanımlar. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Bu öznitelik, animasyon efektinin önceki sesi durdurup durdurmadığını belirtir. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Bu öznitelik, animasyon efektinin önceki sesi durdurup durdurmadığını belirtir. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Efekt için bir sonraki animasyon tipini tanımlar. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Efekt için bir sonraki animasyon tipini tanımlar. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Efekt için bir sonraki animasyon rengini tanımlar. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Efekt için bir sonraki animasyon rengini tanımlar. |
| [getAnimateTextType()](#getAnimateTextType--) | Efekt için bir animasyon metin tipi tanımlar. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Efekt için bir animasyon metin tipi tanımlar. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Animasyonlu metin parçaları (kelimeler veya harfler) arasındaki gecikmeyi tanımlar. |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Animasyonlu metin parçaları (kelimeler veya harfler) arasındaki gecikmeyi tanımlar. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```

Efekt için bir sıralama döndürür. Salt okunur [ISequence](../../com.aspose.slides/isequence).

**Döndürür:**  
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```

TextAnimation Salt okunur [ITextAnimation](../../com.aspose.slides/itextanimation).

**Döndürür:**  
[ITextAnimation](../../com.aspose.slides/itextanimation)

### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```

Efektin sınıfını tanımlar. Okunur/yazılır [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Döndürür:**  
int

### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```

Efektin sınıfını tanımlar. Okunur/yazılır [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Parametreler:**  
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Efektin tipini tanımlar. Okunur/yazılır [EffectType](../../com.aspose.slides/effecttype).

**Döndürür:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Efektin tipini tanımlar. Okunur/yazılır [EffectType](../../com.aspose.slides/effecttype).

**Parametreler:**  
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```

Efektin alt tipini tanımlar. Okunur/yazılır [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Döndürür:**  
int

### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```

Efektin alt tipini tanımlar. Okunur/yazılır [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Parametreler:**  
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```

Efekt için davranış koleksiyonunu döndürür. Okunur/yazılır [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Döndürür:**  
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)

### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```

Efekt için davranış koleksiyonunu döndürür. Okunur/yazılır [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Parametreler:**  
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

Efekt için zamanlama değerini tanımlar. Okunur/yazılır [ITiming](../../com.aspose.slides/itiming).

**Döndürür:**  
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

Efekt için zamanlama değerini tanımlar. Okunur/yazılır [ITiming](../../com.aspose.slides/itiming).

**Parametreler:**  
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```

Efekt için hedef şekli döndürür. Salt okunur [IShape](../../com.aspose.slides/ishape).

**Döndürür:**  
[IShape](../../com.aspose.slides/ishape)

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Efekt için gömülü sesi tanımlar. Okunur/yazılır [IAudio](../../com.aspose.slides/iaudio).

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
>          // Efekt sesini byte dizisine çıkarır
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
public final void setSound(IAudio value)
```

Efekt için gömülü sesi tanımlar. Okunur/yazılır [IAudio](../../com.aspose.slides/iaudio).

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
>          // Efekt sesini byte dizisine çıkarır
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**  
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public final boolean getStopPreviousSound()
```

Bu öznitelik, animasyon efektinin önceki sesi durdurup durdurmadığını belirtir. Okunur/yazılır  boolean .

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
>          // İkinci efektin Geliştirmeler/Sesini "Stop Previous Sound" olarak değiştir
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
public final void setStopPreviousSound(boolean value)
```

Bu öznitelik, animasyon efektinin önceki sesi durdurup durdurmadığını belirtir. Okunur/yazılır  boolean .

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
>          // İkinci efektin Geliştirmeler/Sesini "Stop Previous Sound" olarak değiştir
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**  
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public final int getAfterAnimationType()
```

Efekt için bir sonraki animasyon tipini tanımlar. Okunur/yazılır [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slaydın ilk efektini al.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Efektin After animation değerini "Hide on Next Mouse Click" olarak değiştir
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Döndürür:**  
int

### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public final void setAfterAnimationType(int value)
```

Efekt için bir sonraki animasyon tipini tanımlar. Okunur/yazılır [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slaydın ilk efektini al.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Efektin After animation değerini "Hide on Next Mouse Click" olarak değiştir
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**  
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public final IColorFormat getAfterAnimationColor()
```

Efekt için bir sonraki animasyon rengini tanımlar. Okunur/yazılır [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slaydın ilk efektini al.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Efektin After animation tipini "Color" olarak değiştir
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Efektin After animation rengini ayarla.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Döndürür:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public final void setAfterAnimationColor(IColorFormat value)
```

Efekt için bir sonraki animasyon rengini tanımlar. Okunur/yazılır [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slaydın ilk efektini al.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Efektin After animation tipini "Color" olarak değiştir
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Efektin After animation rengini ayarla.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametreler:**  
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public final int getAnimateTextType()
```

Efekt için bir animasyon metin tipi tanımlar. Şekil metni harfe, kelimeye ya da tümüne birden animasyon uygulanabilir. Okunur/yazılır  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slaydın ilk efektini al.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Efektin Animate text tipini "By letter" olarak değiştir
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Döndürür:**  
int

### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public final void setAnimateTextType(int value)
```

Efekt için bir animasyon metin tipi tanımlar. Şekil metni harfe, kelimeye ya da tümüne birden animasyon uygulanabilir. Okunur/yazılır  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // İlk slaydın ilk efektini al.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Efektin Animate text tipini "By letter" olarak değiştir
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**  
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public final float getDelayBetweenTextParts()
```

Animasyonlu metin parçaları (kelimeler veya harfler) arasındaki gecikmeyi tanımlar. Pozitif bir değer, efekt süresinin yüzdesini belirtir. Negatif bir değer ise gecikmeyi saniye cinsinden belirtir. Okunur/yazılır  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // İlk slaydın ilk efektini al.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Efektin Animate text tipini "By word" olarak değiştir
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Animasyonlu metin parçaları arasındaki gecikmeyi efekt süresinin %20'si olarak ayarla.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Döndürür:**  
float

### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public final void setDelayBetweenTextParts(float value)
```

Animasyonlu metin parçaları (kelimeler veya harfler) arasındaki gecikmeyi tanımlar. Pozitif bir değer, efekt süresinin yüzdesini belirtir. Negatif bir değer ise gecikmeyi saniye cinsinden belirtir. Okunur/yazılır  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // İlk slaydın ilk efektini al.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Efektin Animate text tipini "By word" olarak değiştir
> 
>      // Animasyonlu metin parçaları arasındaki gecikmeyi efekt süresinin %20'si olarak ayarla.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**  
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt okunur IDOMObject.

**Döndürür:**  
com.aspose.slides.IDOMObject