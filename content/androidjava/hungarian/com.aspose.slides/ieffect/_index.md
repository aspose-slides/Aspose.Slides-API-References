---
title: IEffect
second_title: Aspose.Slides for Android via Java API Reference
description: Ábrázolja az animációs hatást.
type: docs
url: /hu/com.aspose.slides/ieffect/
---```
public interface IEffect
```

Ábrázolja az animációs hatást.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getSequence()](#getSequence--) | Visszaad egy sorozatot egy effektushoz. |
| [getTextAnimation()](#getTextAnimation--) | Visszaad szöveganimációt. |
| [getPresetClassType()](#getPresetClassType--) | Meghatározza az effektus osztályát. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Meghatározza az effektus osztályát. |
| [getType()](#getType--) | Meghatározza az effektus típusát. |
| [setType(int value)](#setType-int-) | Meghatározza az effektus típusát. |
| [getSubtype()](#getSubtype--) | Meghatározza az effektus altípusát. |
| [setSubtype(int value)](#setSubtype-int-) | Meghatározza az effektus altípusát. |
| [getBehaviors()](#getBehaviors--) | Visszaad a hatás viselkedésének gyűjteményét. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Visszaad a hatás viselkedésének gyűjteményét. |
| [getTiming()](#getTiming--) | Meghatározza a hatás időzítési értékét. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Meghatározza a hatás időzítési értékét. |
| [getTargetShape()](#getTargetShape--) | Visszaad a hatás célalakját. |
| [getSound()](#getSound--) | Meghatározott beágyazott hang az effektushoz. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Meghatározott beágyazott hang az effektushoz. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Ez az attribútum meghatározza, hogy az animációs hatás leállítja-e az előző hangot. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Ez az attribútum meghatározza, hogy az animációs hatás leállítja-e az előző hangot. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Meghatározott egy utóanimáció típusát az effektushoz. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Meghatározott egy utóanimáció típusát az effektushoz. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Meghatározott egy utóanimáció színt az effektushoz. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Meghatározott egy utóanimáció színt az effektushoz. |
| [getAnimateTextType()](#getAnimateTextType--) | Meghatározza az animált szöveg típusát az effektushoz. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Meghatározza az animált szöveg típusát az effektushoz. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Meghatározza a késleltetést az animált szövegrésszek (szavak vagy betűk) között. |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Meghatározza a késleltetést az animált szövegrésszek (szavak vagy betűk) között. |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```


Visszaad egy sorozatot egy effektushoz. Csak olvasható [ISequence](../../com.aspose.slides/isequence).

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


Visszaad a hatás viselkedésének gyűjteményét. Olvasás/írás [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Visszatér:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```


Visszaad a hatás viselkedésének gyűjteményét. Olvasás/írás [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


Meghatározza a hatás időzítési értékét. Olvasás/írás [ITiming](../../com.aspose.slides/itiming).

**Visszatér:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


Meghatározza a hatás időzítési értékét. Olvasás/írás [ITiming](../../com.aspose.slides/itiming).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```


Visszaad a hatás célalakját. Csak olvasható [IShape](../../com.aspose.slides/ishape).

**Visszatér:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


Meghatározott beágyazott hang az effektushoz. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Lekéri a dia hatássorozatát
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Kinyeri a hatás hangját bájt tömbként
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


Meghatározott beágyazott hang az effektushoz. Olvasás/írás [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Lekéri a dia hatássorozatát
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Kinyeri a hatás hangját bájt tömbként
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


Ez az attribútum meghatározza, hogy az animációs hatás leállítja-e az előző hangot. Olvasás/írás boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dia első effektusát.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Lekéri a második dia első effektusát.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Megváltoztatja a második effektus Enhancements/Sound beállítását "Stop Previous Sound"-ra
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


Ez az attribútum meghatározza, hogy az animációs hatás leállítja-e az előző hangot. Olvasás/írás boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dia első effektusát.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Lekéri a második dia első effektusát.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Megváltoztatja a második effektus Enhancements/Sound beállítását "Stop Previous Sound"-ra
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


Meghatározott egy utóanimáció típusát az effektushoz. Olvasás/írás AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dia első effektusát.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Megváltoztatja az effektus After animation beállítását "Hide on Next Mouse Click"-ra
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


Meghatározott egy utóanimáció típusát az effektushoz. Olvasás/írás AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dia első effektusát.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Megváltoztatja az effektus After animation beállítását "Hide on Next Mouse Click"-ra
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


Meghatározott egy utóanimáció színt az effektushoz. Olvasás/írás [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dia első effektusát.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Megváltoztatja az effektus After animation típusát "Color"-ra
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Beállítja az effektus After animation színét.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
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


Meghatározott egy utóanimáció színt az effektushoz. Olvasás/írás [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Lekéri az első dia első effektusát.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Megváltoztatja az effektus After animation típusát "Color"-ra
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
public abstract int getAnimateTextType()
```


Meghatározza az animált szöveg típusát az effektushoz. A forma szövege betű, szó vagy egyszerre animálható. Olvasás/írás AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Lekéri az első dia első effektusát.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Megváltoztatja az effektus Animate text típusát "ByLetter"-re
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


Meghatározza az animált szöveg típusát az effektushoz. A forma szövege betű, szó vagy egyszerre animálható. Olvasás/írás AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Lekéri az első dia első effektusát.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Megváltoztatja az effektus Animate text típusát "By letter"-re
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


Meghatározza a késleltetést az animált szövegrésszek (szavak vagy betűk) között. A pozitív érték a hatás időtartamának százalékát adja meg. A negatív érték az időt másodpercben adja meg. Olvasás/írás float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Lekéri az első dia első effektusát.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Megváltoztatja az effektus Animate text típusát "By word"-ra
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Beállítja az animált szövegrésszek közötti késleltetést a hatás időtartamának 20%-ára.
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


Meghatározza a késleltetést az animált szövegrésszek (szavak vagy betűk) között. A pozitív érték a hatás időtartamának százalékát adja meg. A negatív érték az időt másodpercben adja meg. Olvasás/írás float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Lekéri az első dia első effektusát.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Megváltoztatja az effektus Animate text típusát "By word"-ra
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Beállítja az animált szövegrésszek közötti késleltetést a hatás időtartamának 20%-ára.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |