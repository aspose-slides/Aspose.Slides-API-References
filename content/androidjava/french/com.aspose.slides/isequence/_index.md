---
title: ISequence
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente la collection de séquences d'effets.
type: docs
url: /fr/com.aspose.slides/isequence/
---
**Toutes les interfaces implémentées :**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

Représente une séquence (collection d'effets).

## Méthodes

| Méthode | Description |
| --- | --- |
| [getCount()](#getCount--) | Retourne le nombre d'effets dans une séquence. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Supprime l'effet spécifié d'une collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime un effet d'une collection. |
| [clear()](#clear--) | Supprime tous les effets d'une collection. |
| [get_Item(int index)](#get-Item-int-) | Retourne un effet à l'index spécifié. |
| [getTriggerShape()](#getTriggerShape--) | Retourne ou définit la forme cible pour la séquence INTERACTIVE. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Retourne ou définit la forme cible pour la séquence INTERACTIVE. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Supprime l'effet pour la forme spécifiée. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Retourne un tableau d'effets pour la forme spécifiée. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Retourne un tableau d'effets pour le paragraphe spécifié. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Retourne le nombre d'effets pour la forme spécifiée. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Ajoute un nouvel effet à la fin de la séquence. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Ajoute un nouvel effet d'animation pour le paragraphe à la fin de la séquence. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Ajoute le nouvel effet d'animation de diagramme pour la catégorie ou la série à la fin de la séquence. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Ajoute le nouvel effet d'animation de diagramme pour les éléments dans la catégorie ou la série à la fin de la séquence. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Retourne le nombre d'effets dans une séquence. Lecture seule int.

**Retour :**  
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

Supprime l'effet spécifié d'une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Effet à supprimer. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime un effet d'une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'effet à supprimer int |

### clear() {#clear--}
```
public abstract void clear()
```

Supprime tous les effets d'une collection.

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

Retourne un effet à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'élément. |

**Retour :**
[IEffect](../../com.aspose.slides/ieffect) - L'objet [IEffect](../../com.aspose.slides/ieffect).

### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

Retourne ou définit la forme cible pour la séquence INTERACTIVE. Si la séquence n'est pas interactive, alors retourne null. Lecture/écriture [IShape](../../com.aspose.slides/ishape).

**Retour :**
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

Retourne ou définit la forme cible pour la séquence INTERACTIVE. Si la séquence n'est pas interactive, alors retourne null. Lecture/écriture [IShape](../../com.aspose.slides/ishape).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

Supprime l'effet pour la forme spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objet forme [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

Retourne un tableau d'effets pour la forme spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objet forme [IShape](../../com.aspose.slides/ishape) |

**Retour :**
com.aspose.slides.IEffect[] - Tableau d'effets [IEffect](../../com.aspose.slides/ieffect)

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Retourne un tableau d'effets pour le paragraphe spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Objet paragraphe [IParagraph](../../com.aspose.slides/iparagraph) |

**Retour :**
com.aspose.slides.IEffect[] - Tableau d'effets [IEffect](../../com.aspose.slides/ieffect)

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

Retourne le nombre d'effets pour la forme spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objet forme [IShape](../../com.aspose.slides/ishape) |

**Retour :**
int - Nombre d'effets int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Ajoute un nouvel effet à la fin de la séquence.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objet forme [IShape](../../com.aspose.slides/ishape) pour ajouter un effet |
| effectType | int | Type d'un effet d'animation [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Sous-types d'effet d'animation [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Type de déclenchement de l'effet [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retour :**
[IEffect](../../com.aspose.slides/ieffect) - Nouvel objet effet [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Ajoute un nouvel effet d'animation pour le paragraphe à la fin de la séquence.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // select paragraph to add effect
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // add Fly animation effect to selected paragraph
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph object [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Type of an animation effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypes of animation effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger type of effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returns:**
[IEffect](../../com.aspose.slides/ieffect) - New effect object [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Ajoute le nouvel effet d'animation de diagramme pour la catégorie ou la série à la fin de la séquence.

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Objet graphique [IChart](../../com.aspose.slides/ichart) |
| type | int | Type d'un effet d'animation [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Index int |
| effectType | int | Type d'un effet d'animation [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Sous-types d'un effet d'animation [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Type de déclenchement de l'effet [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retour:**
[IEffect](../../com.aspose.slides/ieffect) - Nouvel objet d'effet [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)

Ajoute le nouvel effet d'animation de diagramme pour les éléments dans la catégorie ou la série à la fin de la séquence.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Objet diagramme [IChart](../../com.aspose.slides/ichart) |
| type | int | Type d'un effet d'animation [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Index de la série du diagramme int |
| categoriesIndex | int | Index de la catégorie int |
| effectType | int | Type d'un effet d'animation [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Sous-types d'effet d'animation [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Type de déclenchement de l'effet [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retour :**
[IEffect](../../com.aspose.slides/ieffect) - Nouvel objet effet [IEffect](../../com.aspose.slides/ieffect)