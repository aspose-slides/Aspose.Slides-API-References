---
title: IEffect
second_title: Aspose.Slides for Android via Java API Reference
description: Representerar animationseffekt.
type: docs
url: /sv/com.aspose.slides/ieffect/
---```
public interface IEffect
```

Representerar animationseffekt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSequence()](#getSequence--) | Returnerar en sekvens för en effekt. |
| [getTextAnimation()](#getTextAnimation--) | Returnerar textanimation. |
| [getPresetClassType()](#getPresetClassType--) | Definierar klass för effekt. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Definierar klass för effekt. |
| [getType()](#getType--) | Definierar typ för effekt. |
| [setType(int value)](#setType-int-) | Definierar typ för effekt. |
| [getSubtype()](#getSubtype--) | Definierar undertyp för effekt. |
| [setSubtype(int value)](#setSubtype-int-) | Definierar undertyp för effekt. |
| [getBehaviors()](#getBehaviors--) | Returnerar samling av beteenden för effekt. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Returnerar samling av beteenden för effekt. |
| [getTiming()](#getTiming--) | Definierar tidsvärde för effekt. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Definierar tidsvärde för effekt. |
| [getTargetShape()](#getTargetShape--) | Returnerar målform för effekt. |
| [getSound()](#getSound--) | Definierat inbäddat ljud för effekt. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Definierat inbäddat ljud för effekt. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Detta attribut anger om animationseffekten stoppar det föregående ljudet. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Detta attribut anger om animationseffekten stoppar det föregående ljudet. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Definierade en efteranimationstyp för effekt. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Definierade en efteranimationstyp för effekt. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Definierade en efteranimationsfärg för effekt. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Definierade en efteranimationsfärg för effekt. |
| [getAnimateTextType()](#getAnimateTextType--) | Definierar en animering av texttyp för effekt. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Definierar en animering av texttyp för effekt. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Definierar en fördröjning mellan animerade textdelar (ord eller bokstäver). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Definierar en fördröjning mellan animerade textdelar (ord eller bokstäver). |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```


Returnerar en sekvens för en effekt. Skrivskyddad [ISequence](../../com.aspose.slides/isequence).

**Returnerar:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```


Returnerar textanimation. Skrivskyddad [ITextAnimation](../../com.aspose.slides/itextanimation).

**Returnerar:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```


Definierar klass för effekt. Läs/skriv [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Returnerar:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```


Definierar klass för effekt. Läs/skriv [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```


Definierar typ för effekt. Läs/skriv [EffectType](../../com.aspose.slides/effecttype).

**Returnerar:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


Definierar typ för effekt. Läs/skriv [EffectType](../../com.aspose.slides/effecttype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```


Definierar undertyp för effekt. Läs/skriv [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Returnerar:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```


Definierar undertyp för effekt. Läs/skriv [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```


Returnerar samling av beteenden för effekt. Läs/skriv [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Returnerar:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```


Returnerar samling av beteenden för effekt. Läs/skriv [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


Definierar tidsvärde för effekt. Läs/skriv [ITiming](../../com.aspose.slides/itiming).

**Returnerar:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


Definierar tidsvärde för effekt. Läs/skriv [ITiming](../../com.aspose.slides/itiming).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```


Returnerar målform för effekt. Skrivskyddad [IShape](../../com.aspose.slides/ishape).

**Returnerar:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


Definierat inbäddat ljud för effekt. Läs/skriv [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Hämtar effektsekvensen för bilden
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extraherar effektljudet i en bytearray
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
public abstract void setSound(IAudio value)
```


Definierat inbäddat ljud för effekt. Läs/skriv [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Hämtar effektsekvensen för bilden
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extraherar effektljudet i en bytearray
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
public abstract boolean getStopPreviousSound()
```


Det här attributet anger om animationseffekten stoppar det föregående ljudet. Läs/skriv  boolean .

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
>          // Ändra den andra effektens Enhancements/Sound till "Stop Previous Sound"
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
public abstract void setStopPreviousSound(boolean value)
```


Det här attributet anger om animationseffekten stoppar det föregående ljudet. Läs/skriv  boolean .

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
>          // Ändra den andra effektens Enhancements/Sound till "Stop Previous Sound"
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
public abstract int getAfterAnimationType()
```


Definierade en efteranimationstyp för effekt. Läs/skriv  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

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
public abstract void setAfterAnimationType(int value)
```


Definierade en efteranimationstyp för effekt. Läs/skriv  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

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
public abstract IColorFormat getAfterAnimationColor()
```


Definierade en efteranimationsfärg för effekt. Läs/skriv [IColorFormat](../../com.aspose.slides/icolorformat).

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
>      // Ställ in efteranimationsfärgen för effekten.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```


Definierade en efteranimationsfärg för effekt. Läs/skriv [IColorFormat](../../com.aspose.slides/icolorformat).

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
>      // Ställ in efteranimationsfärgen för effekten.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
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
public abstract int getAnimateTextType()
```


Definierar en animering av texttyp för effekt. Formens text kan animeras per bokstav, per ord eller hela på en gång. Läs/skriv  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Hämta den första effekten på den första bilden.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändra effektens Animate text type till "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returnerar:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```


Definierar en animering av texttyp för effekt. Formens text kan animeras per bokstav, per ord eller hela på en gång. Läs/skriv  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Hämta den första effekten på den första bilden.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändra effektens Animate text type till "By letter"
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
public abstract float getDelayBetweenTextParts()
```


Definierar en fördröjning mellan animerade textdelar (ord eller bokstäver). Ett positivt värde anger procentandel av effektens varaktighet. Ett negativt värde anger fördröjningen i sekunder. Läs/skriv  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Hämta den första effekten på den första bilden.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändra effektens Animate text type till "By word"
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
public abstract void setDelayBetweenTextParts(float value)
```


Definierar en fördröjning mellan animerade textdelar (ord eller bokstäver). Ett positivt värde anger procentandel av effektens varaktighet. Ett negativt värde anger fördröjningen i sekunder. Läs/skriv  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Hämta den första effekten på den första bilden.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändra effektens Animate text type till "By word"
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