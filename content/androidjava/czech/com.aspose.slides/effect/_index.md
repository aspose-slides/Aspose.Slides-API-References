---
title: Effect
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje animační efekt.
type: docs
url: /cs/com.aspose.slides/effect/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject
```
public class Effect implements IEffect, IDOMObject
```

Reprezentuje animační efekt.
## Metody

| Method | Description |
| --- | --- |
| [getSequence()](#getSequence--) | Vrací sekvenci pro efekt. |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation Pouze ke čtení [ITextAnimation](../../com.aspose.slides/itextanimation). |
| [getPresetClassType()](#getPresetClassType--) | Definuje třídu efektu. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Definuje třídu efektu. |
| [getType()](#getType--) | Definuje typ efektu. |
| [setType(int value)](#setType-int-) | Definuje typ efektu. |
| [getSubtype()](#getSubtype--) | Definuje podtyp efektu. |
| [setSubtype(int value)](#setSubtype-int-) | Definuje podtyp efektu. |
| [getBehaviors()](#getBehaviors--) | Vrací kolekci chování pro efekt. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Vrací kolekci chování pro efekt. |
| [getTiming()](#getTiming--) | Definuje časování pro efekt. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Definuje časování pro efekt. |
| [getTargetShape()](#getTargetShape--) | Vrací cílový tvar pro efekt. |
| [getSound()](#getSound--) | Definovaný vložený zvuk pro efekt. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Definovaný vložený zvuk pro efekt. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Tento atribut určuje, zda animační efekt zastavuje předchozí zvuk. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Tento atribut určuje, zda animační efekt zastavuje předchozí zvuk. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Definuje typ následné animace pro efekt. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Definuje typ následné animace pro efekt. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Definuje barvu následné animace pro efekt. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Definuje barvu následné animace pro efekt. |
| [getAnimateTextType()](#getAnimateTextType--) | Definuje typ animovaného textu pro efekt. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Definuje typ animovaného textu pro efekt. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Definuje zpoždění mezi částmi animovaného textu (slova nebo písmena). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Definuje zpoždění mezi částmi animovaného textu (slova nebo písmena). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```


Vrací sekvenci pro efekt. Pouze ke čtení [ISequence](../../com.aspose.slides/isequence).

**Returns:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```


TextAnimation Pouze ke čtení [ITextAnimation](../../com.aspose.slides/itextanimation).

**Returns:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```


Definuje třídu efektu. Čtení/zápis [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Returns:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```


Definuje třídu efektu. Čtení/zápis [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```


Definuje typ efektu. Čtení/zápis [EffectType](../../com.aspose.slides/effecttype).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Definuje typ efektu. Čtení/zápis [EffectType](../../com.aspose.slides/effecttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```


Definuje podtyp efektu. Čtení/zápis [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Returns:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```


Definuje podtyp efektu. Čtení/zápis [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```


Vrací kolekci chování pro efekt. Čtení/zápis [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Returns:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```


Vrací kolekci chování pro efekt. Čtení/zápis [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```


Definuje časování pro efekt. Čtení/zápis [ITiming](../../com.aspose.slides/itiming).

**Returns:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```


Definuje časování pro efekt. Čtení/zápis [ITiming](../../com.aspose.slides/itiming).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```


Vrací cílový tvar pro efekt. Pouze ke čtení [IShape](../../com.aspose.slides/ishape).

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public final IAudio getSound()
```


Definovaný vložený zvuk pro efekt. Čtení/zápis [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Získá sekvenci efektů pro snímek
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extrahuje zvuk efektu do pole bajtů
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
```

**Returns:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```


Definovaný vložený zvuk pro efekt. Čtení/zápis [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Získá sekvenci efektů pro snímek
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extrahuje zvuk efektu do pole bajtů
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public final boolean getStopPreviousSound()
```


Tento atribut určuje, zda animační efekt zastavuje předchozí zvuk. Čtení/zápis boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Získá první efekt druhého snímku.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Změní druhý efekt Enhancements/Sound na "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public final void setStopPreviousSound(boolean value)
```


Tento atribut určuje, zda animační efekt zastavuje předchozí zvuk. Čtení/zápis boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Získá první efekt druhého snímku.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Změní druhý efekt Enhancements/Sound na "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public final int getAfterAnimationType()
```


Definuje typ následné animace pro efekt. Čtení/zápis [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní After animation efekt na "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public final void setAfterAnimationType(int value)
```


Definuje typ následné animace pro efekt. Čtení/zápis [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní After animation efekt na "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public final IColorFormat getAfterAnimationColor()
```


Definuje barvu následné animace pro efekt. Čtení/zápis [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní typ After animation efektu na "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Nastaví barvu After animation efektu.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public final void setAfterAnimationColor(IColorFormat value)
```


Definuje barvu následné animace pro efekt. Čtení/zápis [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní typ After animation efektu na "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Nastaví barvu After animation efektu.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public final int getAnimateTextType()
```


Definuje typ animovaného textu pro efekt. Text tvaru může být animován písmenem, slovem nebo najednou. Čtení/zápis AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní typ animovaného textu efektu na "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public final void setAnimateTextType(int value)
```


Definuje typ animovaného textu pro efekt. Text tvaru může být animován písmenem, slovem nebo najednou. Čtení/zápis AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní typ animovaného textu efektu na "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public final float getDelayBetweenTextParts()
```


Definuje zpoždění mezi částmi animovaného textu (slova nebo písmena). Kladná hodnota udává procento trvání efektu. Záporná hodnota udává zpoždění v sekundách. Čtení/zápis float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní typ animovaného textu efektu na "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Nastaví zpoždění mezi částmi animovaného textu na 20% trvání efektu.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public final void setDelayBetweenTextParts(float value)
```


Definuje zpoždění mezi částmi animovaného textu (slova nebo písmena). Kladná hodnota udává procento trvání efektu. Záporná hodnota udává zpoždění v sekundách. Čtení/zápis float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní typ animovaného textu efektu na "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Nastaví zpoždění mezi částmi animovaného textu na 20% trvání efektu.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Vrací objekt Parent_Immediate. Pouze ke čtení IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject