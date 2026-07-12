---
title: IEffect
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen Animationseffekt dar.
type: docs
url: /de/com.aspose.slides/ieffect/
---```
public interface IEffect
```

Stellt einen Animationseffekt dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSequence()](#getSequence--) | Gibt eine Sequenz für einen Effekt zurück. |
| [getTextAnimation()](#getTextAnimation--) | Gibt Textanimation zurück. |
| [getPresetClassType()](#getPresetClassType--) | Definiert die Klasse des Effekts. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Definiert die Klasse des Effekts. |
| [getType()](#getType--) | Definiert den Typ des Effekts. |
| [setType(int value)](#setType-int-) | Definiert den Typ des Effekts. |
| [getSubtype()](#getSubtype--) | Definiert den Subtyp des Effekts. |
| [setSubtype(int value)](#setSubtype-int-) | Definiert den Subtyp des Effekts. |
| [getBehaviors()](#getBehaviors--) | Gibt die Sammlung von Verhalten für den Effekt zurück. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Gibt die Sammlung von Verhalten für den Effekt zurück. |
| [getTiming()](#getTiming--) | Definiert den Timing-Wert für den Effekt. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Definiert den Timing-Wert für den Effekt. |
| [getTargetShape()](#getTargetShape--) | Gibt die Zielform für den Effekt zurück. |
| [getSound()](#getSound--) | Definiert eingebetteten Sound für den Effekt. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Definiert eingebetteten Sound für den Effekt. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Dieses Attribut gibt an, ob der Animationseffekt den vorherigen Sound stoppt. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Dieses Attribut gibt an, ob der Animationseffekt den vorherigen Sound stoppt. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Definiert einen Nach-Animationstyp für den Effekt. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Definiert einen Nach-Animationstyp für den Effekt. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Definiert eine Nach-Animationsfarbe für den Effekt. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Definiert eine Nach-Animationsfarbe für den Effekt. |
| [getAnimateTextType()](#getAnimateTextType--) | Definiert einen animierten Texttyp für den Effekt. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Definiert einen animierten Texttyp für den Effekt. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Definiert eine Verzögerung zwischen animierten Textteilen (Wörter oder Buchstaben). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Definiert eine Verzögerung zwischen animierten Textteilen (Wörter oder Buchstaben). |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```


Gibt eine Sequenz für einen Effekt zurück. Nur lesbar [ISequence](../../com.aspose.slides/isequence).

**Rückgabe:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```


Gibt Textanimation zurück. Nur lesbar [ITextAnimation](../../com.aspose.slides/itextanimation).

**Rückgabe:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```


Definiert die Klasse des Effekts. Lese-/Schreib [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Rückgabe:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```


Definiert die Klasse des Effekts. Lese-/Schreib [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```


Definiert den Typ des Effekts. Lese-/Schreib [EffectType](../../com.aspose.slides/effecttype).

**Rückgabe:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


Definiert den Typ des Effekts. Lese-/Schreib [EffectType](../../com.aspose.slides/effecttype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```


Definiert den Subtyp des Effekts. Lese-/Schreib [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Rückgabe:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```


Definiert den Subtyp des Effekts. Lese-/Schreib [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```


Gibt die Sammlung von Verhalten für den Effekt zurück. Lese-/Schreib [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Rückgabe:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```


Gibt die Sammlung von Verhalten für den Effekt zurück. Lese-/Schreib [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


Definiert den Timing-Wert für den Effekt. Lese-/Schreib [ITiming](../../com.aspose.slides/itiming).

**Rückgabe:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


Definiert den Timing-Wert für den Effekt. Lese-/Schreib [ITiming](../../com.aspose.slides/itiming).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```


Gibt die Zielform für den Effekt zurück. Nur lesbar [IShape](../../com.aspose.slides/ishape).

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


Definiert eingebetteten Sound für den Effekt. Lese-/Schreib [IAudio](../../com.aspose.slides/iaudio).

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


Definiert eingebetteten Sound für den Effekt. Lese-/Schreib [IAudio](../../com.aspose.slides/iaudio).

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```


Dieses Attribut gibt an, ob der Animationseffekt den vorherigen Sound stoppt. Lese-/Schreib boolean .

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
>          // Ändert das Sound-Enhancement des zweiten Effekts zu "Stop Previous Sound"
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


Dieses Attribut gibt an, ob der Animationseffekt den vorherigen Sound stoppt. Lese-/Schreib boolean .

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
>          // Ändert das Sound-Enhancement des zweiten Effekts zu "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```


Definiert einen Nach-Animationstyp für den Effekt. Lese-/Schreib AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Holt den ersten Effekt der ersten Folie.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändert die After-Animation des Effekts zu "Ausblenden beim nächsten Mausklick"
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


Definiert einen Nach-Animationstyp für den Effekt. Lese-/Schreib AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Holt den ersten Effekt der ersten Folie.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändert die After-Animation des Effekts zu "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```


Definiert eine Nach-Animationsfarbe für den Effekt. Lese-/Schreib [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Holt den ersten Effekt der ersten Folie.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändert den After-Animationstyp des Effekts zu "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Setzt die After-Animationsfarbe des Effekts.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
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


Definiert eine Nach-Animationsfarbe für den Effekt. Lese-/Schreib [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Holt den ersten Effekt der ersten Folie.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändert den After-Animationstyp des Effekts zu "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Setzt die After-Animationsfarbe des Effekts.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```


Definiert einen animierten Texttyp für den Effekt. Der Formtext kann Buchstabe für Buchstabe, Wort für Wort oder komplett auf einmal animiert werden. Lese-/Schreib AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Holt den ersten Effekt der ersten Folie.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändert den Animate-Texttyp des Effekts zu "By letter"
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


Definiert einen animierten Texttyp für den Effekt. Der Formtext kann Buchstabe für Buchstabe, Wort für Wort oder komplett auf einmal animiert werden. Lese-/Schreib AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Holt den ersten Effekt der ersten Folie.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändert den Animate-Texttyp des Effekts zu "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```


Definiert eine Verzögerung zwischen animierten Textteilen (Wörter oder Buchstaben). Ein positiver Wert gibt den Prozentsatz der Effektdauer an. Ein negativer Wert gibt die Verzögerung in Sekunden an. Lese-/Schreib float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Holt den ersten Effekt der ersten Folie.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändert den Animate-Texttyp des Effekts zu "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Setzt die Verzögerung zwischen animierten Textteilen auf 20 % der Effektdauer.
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


Definiert eine Verzögerung zwischen animierten Textteilen (Wörter oder Buchstaben). Ein positiver Wert gibt den Prozentsatz der Effektdauer an. Ein negativer Wert gibt die Verzögerung in Sekunden an. Lese-/Schreib float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Holt den ersten Effekt der ersten Folie.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ändert den Animate-Texttyp des Effekts zu "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Setzt die Verzögerung zwischen animierten Textteilen auf 20 % der Effektdauer.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |