---
title: Effect
second_title: Aspose.Slides Androidra a Java API hivatkozás alapján
description: Animációs effektust reprezentál.
type: docs
url: /hu/com.aspose.slides/effect/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject
```
public class Effect implements IEffect, IDOMObject
```

Az animációs effektust reprezentálja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getSequence()](#getSequence--) | Visszaad egy sorozatot az effektushoz. |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation Csak olvasható [ITextAnimation](../../com.aspose.slides/itextanimation). |
| [getPresetClassType()](#getPresetClassType--) | Meghatározza az effektus osztályát. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Meghatározza az effektus osztályát. |
| [getType()](#getType--) | Meghatározza az effektus típusát. |
| [setType(int value)](#setType-int-) | Meghatározza az effektus típusát. |
| [getSubtype()](#getSubtype--) | Meghatározza az effektus altípusát. |
| [setSubtype(int value)](#setSubtype-int-) | Meghatározza az effektus altípusát. |
| [getBehaviors()](#getBehaviors--) | Visszaadja a viselkedés gyűjteményét az effektushoz. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Visszaadja a viselkedés gyűjteményét az effektushoz. |
| [getTiming()](#getTiming--) | Meghatározza az effektus időzítési értékét. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Meghatározza az effektus időzítési értékét. |
| [getTargetShape()](#getTargetShape--) | Visszaadja a cél alakzatot az effektushoz. |
| [getSound()](#getSound--) | Beágyazott hang definiálva az effektushoz. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Beágyazott hang definiálva az effektushoz. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Ez az attribútum meghatározza, hogy az animációs effektus leállítja-e az előző hangot. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Ez az attribútum meghatározza, hogy az animációs effektus leállítja-e az előző hangot. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Meghatározza az animáció utáni típust az effektushoz. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Meghatározza az animáció utáni típust az effektushoz. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Meghatározza az animáció utáni színt az effektushoz. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Meghatározza az animáció utáni színt az effektushoz. |
| [getAnimateTextType()](#getAnimateTextType--) | Meghatározza az animált szöveg típusát az effektushoz. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Meghatározza az animált szöveg típusát az effektushoz. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Meghatározza a késleltetést az animált szöveg részei (szavak vagy betűk) között. |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Meghatározza a késleltetést az animált szöveg részei (szavak vagy betűk) között. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```

Visszaad egy sorozatot az effektushoz. Csak olvasható [ISequence](../../com.aspose.slides/isequence).

**Visszaadja:**
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```

TextAnimation Csak olvasható [ITextAnimation](../../com.aspose.slides/itextanimation).

**Visszaadja:**
[ITextAnimation](../../com.aspose.slides/itextanimation)

### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```

Meghatározza az effektus osztályát. Olvasás/írás [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Visszaadja:**
int

### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```

Meghatározza az effektus osztályát. Olvasás/írás [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Meghatározza az effektus típusát. Olvasás/írás [EffectType](../../com.aspose.slides/effecttype).

**Visszaadja:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Meghatározza az effektus típusát. Olvasás/írás [EffectType](../../com.aspose.slides/effecttype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```

Meghatározza az effektus altípusát. Olvasás/írás [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Visszaadja:**
int

### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```

Meghatározza az effektus altípusát. Olvasás/írás [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```

Visszaadja a viselkedés gyűjteményét az effektushoz. Olvasás/írás [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Visszaadja:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)

### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```

Visszaadja a viselkedés gyűjteményét az effektushoz. Olvasás/írás [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

Meghatározza az effektus időzítési értékét. Olvasás/írás [ITiming](../../com.aspose.slides/itiming).

**Visszaadja:**
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

Meghatározza az effektus időzítési értékét. Olvasás/írás [ITiming](../../com.aspose.slides/itiming).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```

Visszaadja a cél alakzatot az effektushoz. Csak olvasható [IShape](../../com.aspose.slides/ishape).

**Visszaadja:**
[IShape](../../com.aspose.slides/ishape)

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Beágyazott hang definiálva az effektushoz. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Lekéri a dia effektussorozatát
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Kinyeri az effektus hangot bájt tömbben
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Visszaadja:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Beágyazott hang definiálva az effektushoz. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Lekéri a dia effektussorozatát
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Kinyeri az effektus hangot bájt tömbben
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
public final boolean getStopPreviousSound()
```

Ez az attribútum meghatározza, hogy az animációs effektus leállítja-e az előző hangot. Olvasás/írás  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dián az első effektust.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Lekéri a második dián az első effektust.
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

**Visszaadja:**
boolean

### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public final void setStopPreviousSound(boolean value)
```

Ez az attribútum meghatározza, hogy az animációs effektus leállítja-e az előző hangot. Olvasás/írás  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dián az első effektust.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Lekéri a második dián az első effektust.
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
public final int getAfterAnimationType()
```

Meghatározza az animáció utáni típust az effektushoz. Olvasás/írás [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dián az első effektust.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Módosítja az effektus After animation értékét "Hide on Next Mouse Click"-ra
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Visszaadja:**
int

### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public final void setAfterAnimationType(int value)
```

Meghatározza az animáció utáni típust az effektushoz. Olvasás/írás [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dián az első effektust.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Módosítja az effektus After animation értékét "Hide on Next Mouse Click"-ra
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
public final IColorFormat getAfterAnimationColor()
```

Meghatározza az animáció utáni színt az effektushoz. Olvasás/írás [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dián az első effektust.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Módosítja az effektus After animation típusát "Color"-ra
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Beállítja az effektus After animation színét.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Visszaadja:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public final void setAfterAnimationColor(IColorFormat value)
```

Meghatározza az animáció utáni színt az effektushoz. Olvasás/írás [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dián az első effektust.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Módosítja az effektus After animation típusát "Color"-ra
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Beállítja az effektus After animation színét.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
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
public final int getAnimateTextType()
```

Meghatározza az animált szöveg típusát az effektushoz. A forma szövege betűnként, szónként vagy egyszerre animálható. Olvasás/írás  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dián az első effektust.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Módosítja az effektus animált szöveg típusát "Betűnként"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Visszaadja:**
int

### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public final void setAnimateTextType(int value)
```

Meghatározza az animált szöveg típusát az effektushoz. A forma szövege betűnként, szónként vagy egyszerre animálható. Olvasás/írás  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dián az első effektust.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Módosítja az effektus animált szöveg típusát "Betűnként"
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
public final float getDelayBetweenTextParts()
```

Meghatározza a késleltetést az animált szöveg részei (szavak vagy betűk) között. A pozitív érték a hatás időtartamának százalékát adja meg. A negatív érték késleltetést másodpercben ad meg. Olvasás/írás  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dián az első effektust.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Módosítja az effektus animált szöveg típusát "Szóként"
> 
>      // Beállítja az animált szöveg részei közötti késleltetést a hatás időtartamának 20%-ára.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Visszaadja:**
float

### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public final void setDelayBetweenTextParts(float value)
```

Meghatározza a késleltetést az animált szöveg részei (szavak vagy betűk) között. A pozitív érték a hatás időtartamának százalékát adja meg. A negatív érték késleltetést másodpercben ad meg. Olvasás/írás  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Lekéri az első dián az első effektust.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Módosítja az effektus animált szöveg típusát "Szóként"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Beállítja az animált szöveg részei közötti késleltetést a hatás időtartamának 20%-ára.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszaadja:**
com.aspose.slides.IDOMObject