---
title: Effect
second_title: Référence de l'API Aspose.Slides pour Java
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
| [getSound()](#getSound--) | Définit le son intégré pour l'effet. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Définit le son intégré pour l'effet. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Cet attribut indique si l'effet d'animation arrête le son précédent. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Cet attribut indique si l'effet d'animation arrête le son précédent. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Définit un type d'animation après effet. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Définit un type d'animation après effet. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Définit une couleur d'animation après effet. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Définit une couleur d'animation après effet. |
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

**Renvoie :**  
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```

TextAnimation Lecture seule [ITextAnimation](../../com.aspose.slides/itextanimation).

**Renvoie :**  
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```

Définit la classe de l'effet. Lecture/écriture [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Renvoie :**  
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

**Renvoie :**  
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

**Renvoie :**  
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

**Renvoie :**  
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

**Renvoie :**  
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

**Renvoie :**  
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public final IAudio getSound()
```

Définit le son intégré pour l'effet. Lecture/écriture [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Obtient la séquence des effets pour la diapositive
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

**Renvoie :**  
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Définit le son intégré pour l'effet. Lecture/écriture [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Obtient la séquence des effets pour la diapositive
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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getStopPreviousSound() {#getStopPreviousSound--}
```
public final boolean getStopPreviousSound()
```

Cet attribut indique si l'effet d'animation arrête le son précédent. Lecture/écriture boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtenir le premier effet de la première diapositive.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Obtenir le premier effet de la deuxième diapositive.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Modifier le son du deuxième effet Enhancements/Sound en "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Renvoie :**  
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public final void setStopPreviousSound(boolean value)
```

Cet attribut indique si l'effet d'animation arrête le son précédent. Lecture/écriture boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtenir le premier effet de la première diapositive.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Obtenir le premier effet de la deuxième diapositive.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Modifier le second effet Enhancements/Sound en "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getAfterAnimationType() {#getAfterAnimationType--}
```
public final int getAfterAnimationType()
```

Définit un type d'animation après effet. Lecture/écriture [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtenir le premier effet de la première diapositive.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Modifier l'effet After animation en "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Renvoie :**  
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public final void setAfterAnimationType(int value)
```

Définit un type d'animation après effet. Lecture/écriture [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtenir le premier effet de la première diapositive.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Modifier l'effet After animation en "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public final IColorFormat getAfterAnimationColor()
```

Définit une couleur d'animation après effet. Lecture/écriture [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtenir le premier effet de la première diapositive.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Modifier le type After animation de l'effet en "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Définir la couleur After animation de l'effet.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Renvoie :**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public final void setAfterAnimationColor(IColorFormat value)
```

Définit une couleur d'animation après effet. Lecture/écriture [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtenir le premier effet de la première diapositive.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Modifier le type After animation de l'effet en "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Définir la couleur After animation de l'effet.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getAnimateTextType() {#getAnimateTextType--}
```
public final int getAnimateTextType()
```

Définit un type d'animation de texte pour l'effet. Le texte de la forme peut être animé par lettre, par mot ou en une fois. Lecture/écriture AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtenir le premier effet de la première diapositive.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Modifier le type d'animation du texte de l'effet en "Par lettre"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Renvoie :**  
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public final void setAnimateTextType(int value)
```

Définit un type d'animation de texte pour l'effet. Le texte de la forme peut être animé par lettre, par mot ou en une fois. Lecture/écriture AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtenir le premier effet de la première diapositive.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Modifier le type d'animation du texte de l'effet en "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public final float getDelayBetweenTextParts()
```

Définit un délai entre les parties de texte animées (mots ou lettres). Une valeur positive indique le pourcentage de la durée de l'effet. Une valeur négative indique le délai en secondes. Lecture/écriture float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Obtenir le premier effet de la première diapositive.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Modifier le type d'animation du texte de l'effet en "Par mot"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Définir le délai entre les parties de texte animées à 20% de la durée de l'effet.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Renvoie :**  
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public final void setDelayBetweenTextParts(float value)
```

Définit un délai entre les parties de texte animées (mots ou lettres). Une valeur positive indique le pourcentage de la durée de l'effet. Une valeur négative indique le délai en secondes. Lecture/écriture float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Obtenir le premier effet de la première diapositive.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Modifier le type d'animation du texte de l'effet en "Par mot"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Définir le délai entre les parties de texte animées à 20% de la durée de l'effet.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**  
com.aspose.slides.IDOMObject