---
title: Effect
second_title: Aspose.Slides Java API-referencia
description: Animációs hatást képvisel.
type: docs
url: /hu/com.aspose.slides/effect/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject
```
public class Effect implements IEffect, IDOMObject
```

Az animációs effektust reprezentálja.
## Metódusok

| Method | Description |
| --- | --- |
| [getSequence()](#getSequence--) | Visszatér egy sorozattal egy effektushoz. |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation csak olvasható [ITextAnimation](../../com.aspose.slides/itextanimation). |
| [getPresetClassType()](#getPresetClassType--) | Meghatározza az effektus osztályát. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Meghatározza az effektus osztályát. |
| [getType()](#getType--) | Meghatározza az effektus típusát. |
| [setType(int value)](#setType-int-) | Meghatározza az effektus típusát. |
| [getSubtype()](#getSubtype--) | Meghatározza az effektus altípusát. |
| [setSubtype(int value)](#setSubtype-int-) | Meghatározza az effektus altípusát. |
| [getBehaviors()](#getBehaviors--) | Visszatér az effektus viselkedésének gyűjteményével. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Visszatér az effektus viselkedésének gyűjteményével. |
| [getTiming()](#getTiming--) | Meghatározza az effektus időzítési értékét. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Meghatározza az effektus időzítési értékét. |
| [getTargetShape()](#getTargetShape--) | Visszatér az effektus cél alakzatával. |
| [getSound()](#getSound--) | Meghatározott beágyazott hang az effektushoz. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Meghatározott beágyazott hang az effektushoz. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Ez az attribútum meghatározza, hogy az animációs effektus leállítja-e az előző hangot. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Ez az attribútum meghatározza, hogy az animációs effektus leállítja-e az előző hangot. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Meghatározza az effektus utáni animáció típusát. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Meghatározza az effektus utáni animáció típusát. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Meghatározza az effektus utáni animáció színét. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Meghatározza az effektus utáni animáció színét. |
| [getAnimateTextType()](#getAnimateTextType--) | Meghatározza az animált szöveg típusát az effektusban. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Meghatározza az animált szöveg típusát az effektusban. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Meghatározza a késleltetést az animált szövegrészek (szavak vagy betűk) között. |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Meghatározza a késleltetést az animált szövegrészek (szavak vagy betűk) között. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```

Visszatér egy sorozattal egy effektushoz. Csak olvasható [ISequence](../../com.aspose.slides/isequence).

**Visszatér:**
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```

TextAnimation csak olvasható [ITextAnimation](../../com.aspose.slides/itextanimation).

**Visszatér:**
[ITextAnimation](../../com.aspose.slides/itextanimation)

### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```

Meghatározza az effektus osztályát. Olvasható/írható [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Visszatér:**
int

### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```

Meghatározza az effektus osztályát. Olvasható/írható [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Meghatározza az effektus típusát. Olvasható/írható [EffectType](../../com.aspose.slides/effecttype).

**Visszatér:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Meghatározza az effektus típusát. Olvasható/írható [EffectType](../../com.aspose.slides/effecttype).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```

Meghatározza az effektus altípusát. Olvasható/írható [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Visszatér:**
int

### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```

Meghatározza az effektus altípusát. Olvasható/írható [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```

Visszatér az effektus viselkedésének gyűjteményével. Olvasható/írható [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Visszatér:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)

### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```

Visszatér az effektus viselkedésének gyűjteményével. Olvasható/írható [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

Meghatározza az effektus időzítési értékét. Olvasható/írható [ITiming](../../com.aspose.slides/itiming).

**Visszatér:**
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

Meghatározza az effektus időzítési értékét. Olvasható/írható [ITiming](../../com.aspose.slides/itiming).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```

Visszatér az effektus cél alakzatával. Csak olvasható [IShape](../../com.aspose.slides/ishape).

**Visszatér:**
[IShape](../../com.aspose.slides/ishape)

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Meghatározott beágyazott hang az effektushoz. Olvasható/írható [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Lekéri a dia effektus sorozatát
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Kivonja az effektus hangját byte tömbbe
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
public final void setSound(IAudio value)
```

Meghatározott beágyazott hang az effektushoz. Olvasható/írható [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Lekéri a dia effektus sorozatát
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Kivonja az effektus hangját byte tömbbe
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public final boolean getStopPreviousSound()
```

Ez az attribútum meghatározza, hogy az animációs effektus leállítja-e az előző hangot. Olvasható/írható  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dia első effektusát.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Lekéri az első effektust a második dián.
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
public final void setStopPreviousSound(boolean value)
```

Ez az attribútum meghatározza, hogy az animációs effektus leállítja-e az előző hangot. Olvasható/írható  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dia első effektusát.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Lekéri az első effektust a második dián.
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public final int getAfterAnimationType()
```

Meghatározza az effektus utáni animáció típusát. Olvasható/írható [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dia első effektusát.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // A első effektus After animation beállítása "Hide on Next Mouse Click"-ra
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Visszatér:**
int

### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public final void setAfterAnimationType(int value)
```

Meghatározza az effektus utáni animáció típusát. Olvasható/írható [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dia első effektusát.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // A első effektus After animation beállítása "Hide on Next Mouse Click"-ra
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public final IColorFormat getAfterAnimationColor()
```

Meghatározza az effektus utáni animáció színét. Olvasható/írható [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dia első effektusát.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // A hatás After animation típusát "Color"-ra állítja
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Beállítja a hatás After animation színét.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public final void setAfterAnimationColor(IColorFormat value)
```

Meghatározza az effektus utáni animáció színét. Olvasható/írható [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dia első effektusát.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // A hatás After animation típusát "Color"-ra állítja
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Beállítja a hatás After animation színét.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public final int getAnimateTextType()
```

Meghatározza az animált szöveg típusát az effektusban. Az alakzat szövege betű szerint, szó szerint vagy egyszerre animálható. Olvasható/írható  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dia első effektusát.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // A hatás Animate text típusát "By letter"-ra állítja
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Visszatér:**
int

### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public final void setAnimateTextType(int value)
```

Meghatározza az animált szöveg típusát az effektusban. Az alakzat szövege betű szerint, szó szerint vagy egyszerre animálható. Olvasható/írható  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dia első effektusát.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // A hatás Animate text típusát "By letter"-ra állítja
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public final float getDelayBetweenTextParts()
```

Meghatározza a késleltetést az animált szövegrészek (szavak vagy betűk) között. A pozitív érték az effektus időtartamának százalékát adja meg. A negatív érték a késleltetést másodpercben adja meg. Olvasható/írható  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Lekéri az első dia első effektusát.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // A hatás Animate text típusát "By word"-ra állítja
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Beállítja a késleltetést az animált szövegrészek között a hatás időtartamának 20%-ára.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Visszatér:**
float

### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public final void setDelayBetweenTextParts(float value)
```

Meghatározza a késleltetést az animált szövegrészek (szavak vagy betűk) között. A pozitív érték az effektus időtartamának százalékát adja meg. A negatív érték a késleltetést másodpercben adja meg. Olvasható/írható  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Lekéri az első dia első effektusát.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // A hatás Animate text típusát "By word"-ra állítja
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Beállítja a késleltetést az animált szövegrészek között a hatás időtartamának 20%-ára.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszatér a Parent_Immediate objektummal. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject