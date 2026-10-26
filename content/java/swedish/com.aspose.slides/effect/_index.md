---
title: Effect
second_title: Aspose.Slides för Java API-referens
description: Representerar animationseffekt.
type: docs
url: /sv/com.aspose.slides/effect/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject
```
public class Effect implements IEffect, IDOMObject
```

Representerar animationseffekt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSequence()](#getSequence--) | Returnerar en sekvens för en effekt. |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation Skrivskyddad [ITextAnimation](../../com.aspose.slides/itextanimation). |
| [getPresetClassType()](#getPresetClassType--) | Definierar klass av effekt. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Definierar klass av effekt. |
| [getType()](#getType--) | Definierar typ av effekt. |
| [setType(int value)](#setType-int-) | Definierar typ av effekt. |
| [getSubtype()](#getSubtype--) | Definierar undertyp av effekt. |
| [setSubtype(int value)](#setSubtype-int-) | Definierar undertyp av effekt. |
| [getBehaviors()](#getBehaviors--) | Returnerar samling av beteenden för effekt. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Returnerar samling av beteenden för effekt. |
| [getTiming()](#getTiming--) | Definierar tidvärde för effekt. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Definierar tidvärde för effekt. |
| [getTargetShape()](#getTargetShape--) | Returnerar målform för effekt. |
| [getSound()](#getSound--) | Definierar inbäddat ljud för effekt. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Definierar inbäddat ljud för effekt. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Detta attribut anger om animationseffekten stoppar föregående ljud. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Detta attribut anger om animationseffekten stoppar föregående ljud. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Definierar en efteranimationstyp för effekt. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Definierar en efteranimationstyp för effekt. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Definierar en efteranimationsfärg för effekt. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Definierar en efteranimationsfärg för effekt. |
| [getAnimateTextType()](#getAnimateTextType--) | Definierar en typ av textanimation för effekt. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Definierar en typ av textanimation för effekt. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Definierar en fördröjning mellan animerade textdelar (ord eller bokstäver). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Definierar en fördröjning mellan animerade textdelar (ord eller bokstäver). |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```


Returnerar en sekvens för en effekt. Skrivskyddad [ISequence](../../com.aspose.slides/isequence).

**Returnerar:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```


TextAnimation Skrivskyddad [ITextAnimation](../../com.aspose.slides/itextanimation).

**Returnerar:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```


Definierar klass av effekt. Läs/skriv [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Returnerar:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```


Definierar klass av effekt. Läs/skriv [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```


Definierar typ av effekt. Läs/skriv [EffectType](../../com.aspose.slides/effecttype).

**Returnerar:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Definierar typ av effekt. Läs/skriv [EffectType](../../com.aspose.slides/effecttype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```


Definierar undertyp av effekt. Läs/skriv [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Returnerar:**
int
### setSubtype(int value) {#setSubtype-int-}
```java
public final void setSubtype(int value)
```


Definierar undertyp av effekt. Läs/skriv [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```


Returnerar samling av beteenden för effekt. Läs/skriv [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Returnerar:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```


Returnerar samling av beteenden för effekt. Läs/skriv [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```


Definierar tidvärde för effekt. Läs/skriv [ITiming](../../com.aspose.slides/itiming).

**Returnerar:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```


Definierar tidvärde för effekt. Läs/skriv [ITiming](../../com.aspose.slides/itiming).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```


Returnerar målform för effekt. Skrivskyddad [IShape](../../com.aspose.slides/ishape).

**Returnerar:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public final IAudio getSound()
```


Definierar inbäddat ljud för effekt. Läs/skriv [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ``` 
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Hämtar sekvensen av effekter för bilden
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extraherar effektljudet i en byte-array
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Returnerar:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```


Definierar inbäddat ljud för effekt. Läs/skriv [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ``` 
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Hämtar sekvensen av effekter för bilden
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extraherar effektljudet i en byte-array
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public final boolean getStopPreviousSound()
```


Detta attribut anger om animationseffekten stoppar föregående ljud. Läs/skriv  boolean .

--------------------

> ``` 
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Hämta den första effekten på den första bilden.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Hämta den första effekten på den andra bilden.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Ändra den andra effektens Förbättringar/Ljud till "Stoppa föregående ljud"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Returnerar:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public final void setStopPreviousSound(boolean value)
```


Detta attribut anger om animationseffekten stoppar föregående ljud. Läs/skriv  boolean .

--------------------

> ``` 
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Hämta den första effekten på den första bilden.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Hämta den första effekten på den andra bilden.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Ändra den andra effektens Förbättringar/Ljud till "Stoppa föregående ljud"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public final int getAfterAnimationType()
```


Definierar en efteranimationstyp för effekt. Läs/skriv [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ``` 
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Hämta den första effekten på den första bilden.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändra effektens efteranimation till "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returnerar:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public final void setAfterAnimationType(int value)
```


Definierar en efteranimationstyp för effekt. Läs/skriv [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ``` 
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Hämta den första effekten på den första bilden.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändra effektens efteranimation till "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public final IColorFormat getAfterAnimationColor()
```


Definierar en efteranimationsfärg för effekt. Läs/skriv [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ``` 
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Hämta den första effekten på den första bilden.
> 
>      // Ändra effektens efteranimationstyp till "Color"
> 
>      // Ställ in effektens efteranimationsfärg.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public final void setAfterAnimationColor(IColorFormat value)
```


Definierar en efteranimationsfärg för effekt. Läs/skriv [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ``` 
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Hämta den första effekten på den första bilden.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändra effektens efteranimationstyp till "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Ställ in effektens efteranimationsfärg.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public final int getAnimateTextType()
```


Definierar en textanimeringstyp för effekt. Formens text kan animeras per bokstav, per ord eller på en gång. Läs/skriv  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ``` 
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Hämta den första effekten på den första bilden.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändra effektens Animate text-typ till "Per bokstav"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returnerar:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public final void setAnimateTextType(int value)
```


Definierar en textanimeringstyp för effekt. Formens text kan animeras per bokstav, per ord eller på en gång. Läs/skriv  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ``` 
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Hämta den första effekten på den första bilden.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändra effektens Animate text-typ till "Per bokstav"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public final float getDelayBetweenTextParts()
```


Definierar en fördröjning mellan animerade textdelar (ord eller bokstäver). Ett positivt värde anger procentandelen av effektens varaktighet. Ett negativt värde anger fördröjningen i sekunder. Läs/skriv  float .

--------------------

> ``` 
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Hämta den första effekten på den första bilden.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändra effektens Animate text-typ till "ByWord"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Ställ in fördröjningen mellan animerade textdelar till 20% av effektens varaktighet.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returnerar:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public final void setDelayBetweenTextParts(float value)
```


Definierar en fördröjning mellan animerade textdelar (ord eller bokstäver). Ett positivt värde anger procentandelen av effektens varaktighet. Ett negativt värde anger fördröjningen i sekunder. Läs/skriv  float .

--------------------

> ``` 
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Hämta den första effekten på den första bilden.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändra effektens Animate text-typ till "Per ord"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Ställ in fördröjningen mellan animerade textdelar till 20% av effektens varaktighet.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returnerar Parent_Immediate-objekt. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject