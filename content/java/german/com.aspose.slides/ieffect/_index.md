---
title: IEffect
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Animationseffekt dar.
type: docs
url: /de/com.aspose.slides/ieffect/
---```
public interface IEffect
```

Stellt einen Animationseffekt dar.
## Methoden

| Method | Description |
| --- | --- |
| [getSequence()](#getSequence--) | Gibt eine Sequenz für einen Effekt zurück. |
| [getTextAnimation()](#getTextAnimation--) | Gibt Textanimation zurück. |
| [getPresetClassType()](#getPresetClassType--) | Definiert die Klasse des Effekts. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Definiert die Klasse des Effekts. |
| [getType()](#getType--) | Definiert den Typ des Effekts. |
| [setType(int value)](#setType-int-) | Definiert den Typ des Effekts. |
| [getSubtype()](#getSubtype--) | Definiert den Subtyp des Effekts. |
| [setSubtype(int value)](#setSubtype-int-) | Definiert den Subtyp des Effekts. |
| [getBehaviors()](#getBehaviors--) | Gibt eine Sammlung von Verhaltensweisen für den Effekt zurück. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Gibt eine Sammlung von Verhaltensweisen für den Effekt zurück. |
| [getTiming()](#getTiming--) | Definiert den Timing-Wert für den Effekt. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Definiert den Timing-Wert für den Effekt. |
| [getTargetShape()](#getTargetShape--) | Gibt die Zielform für den Effekt zurück. |
| [getSound()](#getSound--) | Definiert eingebetteten Sound für den Effekt. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Definiert eingebetteten Sound für den Effekt. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Dieses Attribut gibt an, ob der Animationseffekt den vorherigen Sound stoppt. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Dieses Attribut gibt an, ob der Animationseffekt den vorherigen Sound stoppt. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Definiert einen Nachanimations-Typ für den Effekt. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Definiert einen Nachanimations-Typ für den Effekt. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Definiert eine Nachanimations-Farbe für den Effekt. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Definiert eine Nachanimations-Farbe für den Effekt. |
| [getAnimateTextType()](#getAnimateTextType--) | Definiert einen animierten Texttyp für den Effekt. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Definiert einen animierten Texttyp für den Effekt. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Definiert eine Verzögerung zwischen animierten Textteilen (Wörtern oder Buchstaben). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Definiert eine Verzögerung zwischen animierten Textteilen (Wörtern oder Buchstaben). |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```


Gibt eine Sequenz für einen Effekt zurück. Nur-Lesen [ISequence](../../com.aspose.slides/isequence).

**Rückgabe:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```


Gibt Textanimation zurück. Nur-Lesen [ITextAnimation](../../com.aspose.slides/itextanimation).

**Rückgabe:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```


Definiert die Klasse des Effekts. Lesen/Schreiben [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Rückgabe:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```


Definiert die Klasse des Effekts. Lesen/Schreiben [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```


Definiert den Typ des Effekts. Lesen/Schreiben [EffectType](../../com.aspose.slides/effecttype).

**Rückgabe:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


Definiert den Typ des Effekts. Lesen/Schreiben [EffectType](../../com.aspose.slides/effecttype).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```


Definiert den Subtyp des Effekts. Lesen/Schreiben [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Rückgabe:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```


Definiert den Subtyp des Effekts. Lesen/Schreiben [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```


Gibt eine Sammlung von Verhaltensweisen für den Effekt zurück. Lesen/Schreiben [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Rückgabe:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```


Gibt eine Sammlung von Verhaltensweisen für den Effekt zurück. Lesen/Schreiben [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


Definiert den Timing-Wert für den Effekt. Lesen/Schreiben [ITiming](../../com.aspose.slides/itiming).

**Rückgabe:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


Definiert den Timing-Wert für den Effekt. Lesen/Schreiben [ITiming](../../com.aspose.slides/itiming).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```


Gibt die Zielform für den Effekt zurück. Nur-Lesen [IShape](../../com.aspose.slides/ishape).

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


Definiert eingebetteten Sound für den Effekt. Lesen/Schreiben [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Holt die Effektsequenz für die Folie
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extrahiert den Sound des Effekts in ein Byte-Array
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Rückgabe:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```


Definiert eingebetteten Sound für den Effekt. Lesen/Schreiben [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Holt die Effektsequenz für die Folie
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extrahiert den Sound des Effekts in ein Byte-Array
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```


Dieses Attribut gibt an, ob der Animationseffekt den vorherigen Sound stoppt. Lesen/Schreiben  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Holt den ersten Effekt der ersten Folie.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Holt den ersten Effekt der zweiten Folie.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Ändert das Sound-Enhancement des zweiten Effekts auf "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Rückgabe:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public abstract void setStopPreviousSound(boolean value)
```


Dieses Attribut gibt an, ob der Animationseffekt den vorherigen Sound stoppt. Lesen/Schreiben  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Holt den ersten Effekt der ersten Folie.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Holt den ersten Effekt der zweiten Folie.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Ändert das Sound-Enhancement des zweiten Effekts auf "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```


Definiert einen Nachanimations-Typ für den Effekt. Lesen/Schreiben  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Holt den ersten Effekt der ersten Folie.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändert die Nachanimation des Effekts auf "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Rückgabe:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```


Definiert einen Nachanimations-Typ für den Effekt. Lesen/Schreiben  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Holt den ersten Effekt der ersten Folie.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändert die Nachanimation des Effekts auf "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```


Definiert eine Nachanimations-Farbe für den Effekt. Lesen/Schreiben [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Holt den ersten Effekt der ersten Folie.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändert den Nachanimationstyp des Effekts auf "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Setzt die Nachanimationsfarbe des Effekts.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```


Definiert eine Nachanimations-Farbe für den Effekt. Lesen/Schreiben [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Holt den ersten Effekt der ersten Folie.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändert den Nachanimationstyp des Effekts auf "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Setzt die Nachanimationsfarbe des Effekts.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```


Definiert einen animierten Texttyp für den Effekt. Der Text der Form kann Buchstabe für Buchstabe, Wort für Wort oder auf einmal animiert werden. Lesen/Schreiben  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Holt den ersten Effekt der ersten Folie.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändert den Animate text type des Effekts zu "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Rückgabe:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```


Definiert einen animierten Texttyp für den Effekt. Der Text der Form kann Buchstabe für Buchstabe, Wort für Wort oder auf einmal animiert werden. Lesen/Schreiben  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Holt den ersten Effekt der ersten Folie.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändert den Animate text type des Effekts zu "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```


Definiert eine Verzögerung zwischen animierten Textteilen (Wörtern oder Buchstaben). Ein positiver Wert gibt den Prozentsatz der Effektdauer an. Ein negativer Wert gibt die Verzögerung in Sekunden an. Lesen/Schreiben  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Holt den ersten Effekt der ersten Folie.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändert den Animate text type des Effekts zu "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Setzt die Verzögerung zwischen animierten Textteilen auf 20% der Effektdauer.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Rückgabe:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```


Definiert eine Verzögerung zwischen animierten Textteilen (Wörtern oder Buchstaben). Ein positiver Wert gibt den Prozentsatz der Effektdauer an. Ein negativer Wert gibt die Verzögerung in Sekunden an. Lesen/Schreiben  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Holt den ersten Effekt der ersten Folie.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändert den Animate text type des Effekts zu "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Setzt die Verzögerung zwischen animierten Textteilen auf 20% der Effektdauer.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |