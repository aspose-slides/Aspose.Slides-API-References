---
title: Effect
second_title: Aspose.Slides pro Java - referenční příručka API
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

| Metoda | Popis |
| --- | --- |
| [getSequence()](#getSequence--) | Vrací sekvenci pro efekt. |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation pouze pro čtení [ITextAnimation](../../com.aspose.slides/itextanimation). |
| [getPresetClassType()](#getPresetClassType--) | Definuje třídu efektu. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Definuje třídu efektu. |
| [getType()](#getType--) | Definuje typ efektu. |
| [setType(int value)](#setType-int-) | Definuje typ efektu. |
| [getSubtype()](#getSubtype--) | Definuje podtyp efektu. |
| [setSubtype(int value)](#setSubtype-int-) | Definuje podtyp efektu. |
| [getBehaviors()](#getBehaviors--) | Vrací kolekci chování pro efekt. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Vrací kolekci chování pro efekt. |
| [getTiming()](#getTiming--) | Definuje časovou hodnotu pro efekt. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Definuje časovou hodnotu pro efekt. |
| [getTargetShape()](#getTargetShape--) | Vrací cílový tvar pro efekt. |
| [getSound()](#getSound--) | Definuje vložený zvuk pro efekt. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Definuje vložený zvuk pro efekt. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Tento atribut určuje, zda animační efekt zastaví předchozí zvuk. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Tento atribut určuje, zda animační efekt zastaví předchozí zvuk. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Definuje typ po-animace pro efekt. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Definuje typ po-animace pro efekt. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Definuje barvu po-animace pro efekt. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Definuje barvu po-animace pro efekt. |
| [getAnimateTextType()](#getAnimateTextType--) | Definuje typ animovaného textu pro efekt. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Definuje typ animovaného textu pro efekt. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Definuje prodlevu mezi částmi animovaného textu (slovy nebo písmeny). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Definuje prodlevu mezi částmi animovaného textu (slovy nebo písmeny). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```


Vrací sekvenci pro efekt. Pouze pro čtení [ISequence](../../com.aspose.slides/isequence).

**Vrací:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```


TextAnimation pouze pro čtení [ITextAnimation](../../com.aspose.slides/itextanimation).

**Vrací:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```


Definuje třídu efektu. Čtení/zápis [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Vrací:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```


Definuje třídu efektu. Čtení/zápis [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public final int getType()
```


Definuje typ efektu. Čtení/zápis [EffectType](../../com.aspose.slides/effecttype).

**Vrací:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Definuje typ efektu. Čtení/zápis [EffectType](../../com.aspose.slides/effecttype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```


Definuje podtyp efektu. Čtení/zápis [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Vrací:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```


Definuje podtyp efektu. Čtení/zápis [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```


Vrací kolekci chování pro efekt. Čtení/zápis [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Vrací:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```


Vrací kolekci chování pro efekt. Čtení/zápis [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```


Definuje časovou hodnotu pro efekt. Čtení/zápis [ITiming](../../com.aspose.slides/itiming).

**Vrací:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```


Definuje časovou hodnotu pro efekt. Čtení/zápis [ITiming](../../com.aspose.slides/itiming).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```


Vrací cílový tvar pro efekt. Pouze pro čtení [IShape](../../com.aspose.slides/ishape).

**Vrací:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public final IAudio getSound()
```


Definuje vložený zvuk pro efekt. Čtení/zápis [IAudio](../../com.aspose.slides/iaudio).

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
>          // Extrahuje zvuk efektu do pole byte
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Vrací:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```


Definuje vložený zvuk pro efekt. Čtení/zápis [IAudio](../../com.aspose.slides/iaudio).

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
>          // Extrahuje zvuk efektu do pole byte
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getStopPreviousSound() {#getStopPreviousSound--}
```
public final boolean getStopPreviousSound()
```


Tento atribut určuje, zda animační efekt zastaví předchozí zvuk. Čtení/zápis boolean.

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
>          // Změní zvuk druhého efektu na "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Vrací:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public final void setStopPreviousSound(boolean value)
```


Tento atribut určuje, zda animační efekt zastaví předchozí zvuk. Čtení/zápis boolean.

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
>          // Změní zvuk druhého efektu na "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getAfterAnimationType() {#getAfterAnimationType--}
```
public final int getAfterAnimationType()
```


Definuje typ po-animace pro efekt. Čtení/zápis [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní po-animaci efektu na "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Vrací:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public final void setAfterAnimationType(int value)
```


Definuje typ po-animace pro efekt. Čtení/zápis [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní po-animaci efektu na "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public final IColorFormat getAfterAnimationColor()
```


Definuje barvu po-animace pro efekt. Čtení/zápis [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní po-animaci efektu na "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Nastaví barvu po-animace efektu.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public final void setAfterAnimationColor(IColorFormat value)
```


Definuje barvu po-animace pro efekt. Čtení/zápis [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní po-animaci efektu na "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Nastaví barvu po-animace efektu.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getAnimateTextType() {#getAnimateTextType--}
```
public final int getAnimateTextType()
```


Definuje typ animovaného textu pro efekt. Text ve tvaru může být animován po písmenu, po slovu nebo najednou. Čtení/zápis AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní typ animace textu efektu na "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Vrací:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public final void setAnimateTextType(int value)
```


Definuje typ animovaného textu pro efekt. Text ve tvaru může být animován po písmenu, po slovu nebo najednou. Čtení/zápis AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní typ animace textu efektu na "Po písmenu"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public final float getDelayBetweenTextParts()
```


Definuje prodlevu mezi částmi animovaného textu (slovy nebo písmeny). Kladná hodnota udává procento trvání efektu. Záporná hodnota udává prodlevu v sekundách. Čtení/zápis float.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní typ animace textu efektu na "By word"
> 
>      // Nastaví prodlevu mezi částmi animovaného textu na 20% trvání efektu.
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  ```

**Vrací:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public final void setDelayBetweenTextParts(float value)
```


Definuje prodlevu mezi částmi animovaného textu (slovy nebo písmeny). Kladná hodnota udává procento trvání efektu. Záporná hodnota udává prodlevu v sekundách. Čtení/zápis float.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Získá první efekt prvního snímku.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Změní typ animace textu efektu na "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Nastaví prodlevu mezi částmi animovaného textu na 20% trvání efektu.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject