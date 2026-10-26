---
title: Effect
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente un effet d'animation.
type: docs
url: /fr/com.aspose.slides/effect/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject
```
public class Effect implements IEffect, IDOMObject
```

Représente un effet d'animation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSequence()](#getSequence--) | Renvoie une séquence pour un effet. |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation Lecture seule [ITextAnimation](../../com.aspose.slides/itextanimation). |
| [getPresetClassType()](#getPresetClassType--) | Définit la classe de l'effet. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Définit la classe de l'effet. |
| [getType()](#getType--) | Définit le type de l'effet. |
| [setType(int value)](#setType-int-) | Définit le type de l'effet. |
| [getSubtype()](#getSubtype--) | Définit le sous-type de l'effet. |
| [setSubtype(int value)](#setSubtype-int-) | Définit le sous-type de l'effet. |
| [getBehaviors()](#getBehaviors--) | Renvoie la collection de comportements pour l'effet. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Renvoie la collection de comportements pour l'effet. |
| [getTiming()](#getTiming--) | Définit la valeur de synchronisation pour l'effet. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Définit la valeur de synchronisation pour l'effet. |
| [getTargetShape()](#getTargetShape--) | Renvoie la forme cible pour l'effet. |
| [getSound()](#getSound--) | Son intégré défini pour l'effet. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Son intégré défini pour l'effet. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Cet attribut spécifie si l'effet d'animation arrête le son précédent. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Cet attribut spécifie si l'effet d'animation arrête le son précédent. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Définit un type d'animation après l'effet. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Définit un type d'animation après l'effet. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Définit une couleur d'animation après l'effet. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Définit une couleur d'animation après l'effet. |
| [getAnimateTextType()](#getAnimateTextType--) | Définit un type d'animation de texte pour l'effet. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Définit un type d'animation de texte pour l'effet. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Définit un délai entre les parties de texte animées (mots ou lettres). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Définit un délai entre les parties de texte animées (mots ou lettres). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```

Renvoie une séquence pour un effet. Lecture seule [ISequence](../../com.aspose.slides/isequence).

**Retour :**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```

TextAnimation Lecture seule [ITextAnimation](../../com.aspose.slides/itextanimation).

**Retour :**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```

Définit la classe de l'effet. Lecture/écriture [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Retour :**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```

Définit la classe de l'effet. Lecture/écriture [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public final int getType()
```

Définit le type de l'effet. Lecture/écriture [EffectType](../../com.aspose.slides/effecttype).

**Retour :**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Définit le type de l'effet. Lecture/écriture [EffectType](../../com.aspose.slides/effecttype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```

Définit le sous-type de l'effet. Lecture/écriture [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Retour :**
int
### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```

Définit le sous-type de l'effet. Lecture/écriture [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```

Renvoie la collection de comportements pour l'effet. Lecture/écriture [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Retour :**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```

Renvoie la collection de comportements pour l'effet. Lecture/écriture [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

Définit la valeur de synchronisation pour l'effet. Lecture/écriture [ITiming](../../com.aspose.slides/itiming).

**Retour :**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

Définit la valeur de synchronisation pour l'effet. Lecture/écriture [ITiming](../../com.aspose.slides/itiming).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```

Renvoie la forme cible pour l'effet. Lecture seule [IShape](../../com.aspose.slides/ishape).

**Retour :**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public final IAudio getSound()
```

Son intégré défini pour l'effet. Lecture/écriture [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Gets the effects sequence for the slide
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extracts the effect sound in byte array
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```
Defined embedded sound for effect. Read/write [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Obtient la séquence d'effets pour la diapositive
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extrait le son de l'effet en tableau d'octets
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public final boolean getStopPreviousSound()
```

This attribute specifies if the animation effect stops the previous sound. Read/write  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtient le premier effet de la première diapositive.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Obtient le premier effet de la deuxième diapositive.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Modifie le son de l'effet second en "Stop Previous Sound"
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
This attribute specifies if the animation effect stops the previous sound. Read/write  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtient le premier effet de la première diapositive.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Obtient le premier effet de la deuxième diapositive.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Modifie le son du second effet en « Stop Previous Sound »
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
```
public final int getAfterAnimationType()
```

Defines an after animation type for effect. Read/write [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtient le premier effet de la première diapositive.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Modifie l'animation après effet en "Hide on Next Mouse Click"
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

Defines an after animation type for effect. Read/write [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtient le premier effet de la première diapositive.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Modifie l'animation après effet en "Hide on Next Mouse Click"
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

Defines an after animation color for effect. Read/write [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtenir le premier effet de la première diapositive.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Modifier le type d'animation après l'effet en "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Définir la couleur d'animation après l'effet.
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

Defines an after animation color for effect. Read/write [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtient le premier effet de la première diapositive.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Modifier le type d'animation après l'effet en "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Définir la couleur d'animation après l'effet.
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

Defines an animate text type for effect. The shape text can be animated by letter, by word or all at once. Read/write  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtient le premier effet de la première diapositive.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Modifie le type d'animation du texte de l'effet en "Par lettre"
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

Defines an animate text type for effect. The shape text can be animated by letter, by word or all at once. Read/write  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtient le premier effet de la première diapositive.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Modifie le type d'animation du texte de l'effet en "Par lettre"
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
Defines a delay between animated text parts (words or letters). A positive value specifies the percentage of effect duration. A negative value specifies the delay in seconds. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtient le premier effet de la première diapositive.
>       IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>       // Modifie le type d'animation du texte de l'effet en "Par mot"
>       firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>       // Définit le délai entre les parties de texte animées à 20 % de la durée de l'effet.
>       firstSlideEffect.setDelayBetweenTextParts(20f);
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**Returns:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public final void setDelayBetweenTextParts(float value)
```
 


Defines a delay between animated text parts (words or letters). A positive value specifies the percentage of effect duration. A negative value specifies the delay in seconds. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Obtient le premier effet de la première diapositive.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Modifie le type d'animation du texte de l'effet en "Par mot"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Définit le délai entre les parties de texte animées à 20 % de la durée de l'effet.
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
Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject