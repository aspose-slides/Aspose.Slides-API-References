---
title: IEffect
second_title: Aspose.Slides for Java API Reference
description: Az animációs hatást ábrázolja.
type: docs
url: /hu/com.aspose.slides/ieffect/
---```
public interface IEffect
```

Az animációs hatást ábrázolja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getSequence()](#getSequence--) | Visszaad egy sorozatot az effektushoz. |
| [getTextAnimation()](#getTextAnimation--) | Visszaad szöveganimációt. |
| [getPresetClassType()](#getPresetClassType--) | Meghatározza az effektus osztályát. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Meghatározza az effektus osztályát. |
| [getType()](#getType--) | Meghatározza az effektus típusát. |
| [setType(int value)](#setType-int-) | Meghatározza az effektus típusát. |
| [getSubtype()](#getSubtype--) | Meghatározza az effektus altípusát. |
| [setSubtype(int value)](#setSubtype-int-) | Meghatározza az effektus altípusát. |
| [getBehaviors()](#getBehaviors--) | Visszaad az effektus viselkedésének gyűjteményét. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Visszaad az effektus viselkedésének gyűjteményét. |
| [getTiming()](#getTiming--) | Meghatározza az effektus időzítési értékét. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Meghatározza az effektus időzítési értékét. |
| [getTargetShape()](#getTargetShape--) | Visszaad a cél alakzatot az effektushoz. |
| [getSound()](#getSound--) | Meghatározza az beágyazott hangot az effektushoz. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Meghatározza az beágyazott hangot az effektushoz. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Ez az attribútum meghatározza, hogy az animációs effektus leállítja-e az előző hangot. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Ez az attribútum meghatározza, hogy az animációs effektus leállítja-e az előző hangot. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Meghatározza az effektus utánani animáció típusát. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Meghatározza az effektus utánani animáció típusát. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Meghatározza az effektus utánani animáció színét. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Meghatározza az effektus utánani animáció színét. |
| [getAnimateTextType()](#getAnimateTextType--) | Meghatározza az effektus szöveganimáció típusát. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Meghatározza az effektus szöveganimáció típusát. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Meghatározza a késleltetést a animált szövegrészek (szavak vagy betűk) között. |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Meghatározza a késleltetést a animált szövegrészek (szavak vagy betűk) között. |

### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```


Visszaad egy sorozatot az effektushoz. Csak olvasható [ISequence](../../com.aspose.slides/isequence).

**Visszatér:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```


Visszaad szöveganimációt. Csak olvasható [ITextAnimation](../../com.aspose.slides/itextanimation).

**Visszatér:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```


Meghatározza az effektus osztályát. Olvasás/írás [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Visszatér:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```


Meghatározza az effektus osztályát. Olvasás/írás [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```


Meghatározza az effektus típusát. Olvasás/írás [EffectType](../../com.aspose.slides/effecttype).

**Visszatér:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


Meghatározza az effektus típusát. Olvasás/írás [EffectType](../../com.aspose.slides/effecttype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```


Meghatározza az effektus altípusát. Olvasás/írás [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Visszatér:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```


Meghatározza az effektus altípusát. Olvasás/írás [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```


Visszaad az effektus viselkedésének gyűjteményét. Olvasás/írás [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Visszatér:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```


Visszaad az effektus viselkedésének gyűjteményét. Olvasás/írás [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


Meghatározza az effektus időzítési értékét. Olvasás/írás [ITiming](../../com.aspose.slides/itiming).

**Visszatér:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


Meghatározza az effektus időzítési értékét. Olvasás/írás [ITiming](../../com.aspose.slides/itiming).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```


Visszaad a cél alakzatot az effektushoz. Csak olvasható [IShape](../../com.aspose.slides/ishape).

**Visszatér:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


Meghatározza az beágyazott hangot az effektushoz. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Lekérdezi a dián lévő effektusok sorozatát
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Kivonja az effektus hangját bájt tömbbe
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Visszatér:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```


Meghatározza az beágyazott hangot az effektushoz. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Lekérdezi a dián lévő effektusok sorozatát
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Kivonja az effektus hangját bájt tömbbe
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```


Ez az attribútum meghatározza, hogy az animációs effektus leállítja-e az előző hangot. Olvasás/írás  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // A első dia első effektusát lekéri.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // A második dia első effektusát lekéri.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // A második effektus Enhancements/Sound beállítása "Stop Previous Sound"-ra
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Visszatér:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public abstract void setStopPreviousSound(boolean value)
```


Ez az attribútum meghatározza, hogy az animációs effektus leállítja-e az előző hangot. Olvasás/írás  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Az első dia első effektusát lekéri.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // A második dia első effektusát lekéri.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // A második effektus Enhancements/Sound beállítása "Stop Previous Sound"-ra
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```


Meghatározza az effektus utánani animáció típusát. Olvasás/írás  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Az első dia első effektusát lekéri.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // A effektus After animation beállítása "Hide on Next Mouse Click"-ra
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Visszatér:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```


Meghatározza az effektus utánani animáció típusát. Olvasás/írás  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Az első dia első effektusát lekéri.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // A effektus After animation beállítása "Hide on Next Mouse Click"-ra
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```


Meghatározza az effektus utánani animáció színét. Olvasás/írás [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Az első dia első effektusát lekéri.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // A effektus After animation típusát "Color"-ra változtatja
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Beállítja a effektus After animation színét.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```


Meghatározza az effektus utánani animáció színét. Olvasás/írás [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Az első dia első effektusát lekéri.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // A effektus After animation típusát "Color"-ra változtatja
> 
>      // Beállítja a effektus After animation színét.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```


Meghatározza az effektus szöveganimáció típusát. A forma szövege betűnként, szó szerint vagy egyszerre animálható. Olvasás/írás  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Az első dia első effektusát lekéri.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // A effektus Animate text típusát "By letter"-ra változtatja
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Visszatér:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```


Meghatározza az effektus szöveganimáció típusát. A forma szövege betűnként, szó szerint vagy egyszerre animálható. Olvasás/írás  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Az első dia első effektusát lekéri.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // A effektus Animate text típusát "By letter"-ra változtatja
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```


Meghatározza a késleltetést a animált szövegrészek (szavak vagy betűk) között. Pozitív érték esetén a hatás időtartamának százalékát adja meg. Negatív érték esetén a késleltetést másodpercben adja meg. Olvasás/írás  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Az első dia első effektusát lekéri.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // A effektus Animate text típusát "By word"-ra változtatja
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Beállítja az animált szövegrészek közötti késleltetést az effektus időtartamának 20%-ára.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Visszatér:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```


Meghatározza a késleltetést a animált szövegrészek (szavak vagy betűk) között. Pozitív érték esetén a hatás időtartamának százalékát adja meg. Negatív érték esetén a késleltetést másodpercben adja meg. Olvasás/írás  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Az első dia első effektusát lekéri.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // A effektus Animate text típusát "By word"-ra változtatja
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Beállítja az animált szövegrészek közötti késleltetést az effektus időtartamának 20%-ára.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |