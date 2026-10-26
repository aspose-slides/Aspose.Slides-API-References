---
title: ITextAnimation
second_title: Aspose.Slides for Java API Reference
description: Représente l'animation de texte.
type: docs
url: /fr/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Représente l'animation de texte.
## Méthodes

| Méthode | Description |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Ajoute un nouvel effet à la fin de la séquence actuelle jusqu'à la fin des animations de texte groupées. |
| [getBuildType()](#getBuildType--) | Liste du type de construction (par ex. |
| [setBuildType(int value)](#setBuildType-int-) | Liste du type de construction (par ex. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Effet de forme liée avec groupe ou non (null) Lecture/écriture [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Effet de forme liée avec groupe ou non (null) Lecture/écriture [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```


Ajoute un nouvel effet à la fin de la séquence actuelle jusqu'à la fin des animations de texte groupées. Valide uniquement si le nombre de paragraphes de texte est égal ou supérieur au nombre d'effets de ce groupe !

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| effectType | int | Type d'un effet d'animation [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Sous-types d'effet d'animation [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Type de déclencheur de l'effet [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Renvoie :**
[IEffect](../../com.aspose.slides/ieffect) - Nouvel objet effet [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```


Liste du type de construction (par ex. Paragraphe 1,2,3, Tous en même temps) de l'animation de texte. Lecture/écriture \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Renvoie :**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```


Liste du type de construction (par ex. Paragraphe 1,2,3, Tous en même temps) de l'animation de texte. Lecture/écriture \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```


Effet de forme liée avec groupe ou non (null) Lecture/écriture [IEffect](../../com.aspose.slides/ieffect).

**Renvoie :**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```


Effet de forme liée avec groupe ou non (null) Lecture/écriture [IEffect](../../com.aspose.slides/ieffect).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |