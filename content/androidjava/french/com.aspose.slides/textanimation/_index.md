---
title: TextAnimation
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une animation de texte.
type: docs
url: /fr/com.aspose.slides/textanimation/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)  
```
public class TextAnimation implements ITextAnimation
```

Représente une animation de texte.  
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Ajoute un nouvel effet à la fin de la séquence actuelle jusqu'à la fin des animations de texte du groupe. |
| [getBuildType()](#getBuildType--) | Liste du type de construction (par ex. |
| [setBuildType(int value)](#setBuildType-int-) | Liste du type de construction (par ex. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Effet de forme lié au groupe ou non (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Effet de forme lié au groupe ou non (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```

Ajoute un nouvel effet à la fin de la séquence actuelle jusqu'à la fin des animations de texte du groupe. Valide uniquement si le nombre de paragraphes de texte est égal ou supérieur au nombre d'effets de ce groupe !

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| effectType | int | Type d'un effet d'animation [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Sous-types d'effet d'animation [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Type de déclencheur de l'effet [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retour :**
[IEffect](../../com.aspose.slides/ieffect) - Nouvel objet d'effet [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```

Liste du type de construction (par ex. Paragraphe 1,2,3, Tous en même temps) de l'animation de texte. Lecture/écriture [BuildType](../../com.aspose.slides/buildtype).

**Retour :**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```

Liste du type de construction (par ex. Paragraphe 1,2,3, Tous en même temps) de l'animation de texte. Lecture/écriture [BuildType](../../com.aspose.slides/buildtype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```

Effet de forme lié au groupe ou non (null). Lecture/écriture [IEffect](../../com.aspose.slides/ieffect).

**Retour :**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```

Effet de forme lié au groupe ou non (null). Lecture/écriture [IEffect](../../com.aspose.slides/ieffect).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |