---
title: Sequence
second_title: Référence de l'API Aspose.Slides pour Android via Java
description: Représente une collection de séquences d'effets.
type: docs
url: /fr/com.aspose.slides/sequence/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)
```
public final class Sequence implements ISequence
```

Représente une séquence (collection d'effets).
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCount()](#getCount--) | Renvoie le nombre d'effets dans une séquence. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Supprime l'effet spécifié d'une collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime un effet d'une collection. |
| [clear()](#clear--) | Supprime tous les effets d'une collection. |
| [get_Item(int index)](#get-Item-int-) | Renvoie un effet à l'index spécifié. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
| [getTriggerShape()](#getTriggerShape--) | Renvoie ou définit la forme cible pour la séquence INTERACTIVE. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Renvoie ou définit la forme cible pour la séquence INTERACTIVE. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Supprime l'effet pour la forme spécifiée. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Renvoie un tableau d'effets pour la forme spécifiée. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Renvoie un tableau d'effets pour le paragraphe spécifié. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Renvoie le nombre d'effets pour la forme spécifiée. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Ajoute un nouvel effet à la fin de la séquence. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Ajoute un nouvel effet d'animation pour le paragraphe à la fin de la séquence. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Ajoute le nouvel effet d'animation de graphique pour une catégorie ou une série à la fin de la séquence. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Ajoute le nouvel effet d'animation de graphique pour les éléments d'une catégorie ou d'une série à la fin de la séquence. |

### getCount() {#getCount--}
```
public final int getCount()
```

Renvoie le nombre d'effets dans une séquence. Lecture seule int.

**Renvoie :**
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

Supprime l'effet spécifié d'une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Effet à supprimer. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime un effet d'une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index d'un effet qui doit être supprimé. |

### clear() {#clear--}
```
public final void clear()
```

Supprime tous les effets d'une collection.

### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

Renvoie un effet à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'élément. |

**Renvoie :**
[IEffect](../../com.aspose.slides/ieffect) - L'objet [IEffect](../../com.aspose.slides/ieffect).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - Un java.util.Iterator pour l'ensemble de la collection.

### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

Renvoie ou définit la forme cible pour la séquence INTERACTIVE. Si la séquence n'est pas interactive alors renvoie null. Lecture/écriture [IShape](../../com.aspose.slides/ishape).

**Renvoie :**
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

Renvoie ou définit la forme cible pour la séquence INTERACTIVE. Si la séquence n'est pas interactive alors renvoie null. Lecture/écriture [IShape](../../com.aspose.slides/ishape).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

Supprime l'effet pour la forme spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

Renvoie un tableau d'effets pour la forme spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Renvoie :**
com.aspose.slides.IEffect[]

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Renvoie un tableau d'effets pour le paragraphe spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**Renvoie :**
com.aspose.slides.IEffect[]

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

Renvoie le nombre d'effets pour la forme spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Renvoie :**
int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Ajoute un nouvel effet à la fin de la séquence.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objet Shape [IShape](../../com.aspose.slides/ishape) pour ajouter un effet |
| effectType | int | Type d'un effet d'animation [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Sous-types d'effet d'animation [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Type de déclenchement de l'effet [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Renvoie :**
[IEffect](../../com.aspose.slides/ieffect) - Nouvel objet d'effet [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Ajoute un nouvel effet d'animation pour le paragraphe à la fin de la séquence.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // select paragraph to add effect
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // add Fly animation effect to selected paragraph
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
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
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```
Adds the new chart animation effect for category or series to the end of sequence.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart object [IChart](../../com.aspose.slides/ichart) |
| type | int | Type of an animation effect [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Index int |
| effectType | int | Type of an animation effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypes of animation effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger type of effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returns:**
[IEffect](../../com.aspose.slides/ieffect) - New effect object [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)


Ajoute le nouvel effet d'animation de graphique pour les éléments d'une catégorie ou d'une série à la fin de la séquence.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Objet graphique [IChart](../../com.aspose.slides/ichart) |
| type | int | Type d'un effet d'animation [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Index de la série du graphique int |
| categoriesIndex | int | Index de la catégorie int |
| effectType | int | Type d'un effet d'animation [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Sous-types d'effet d'animation [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Type de déclenchement de l'effet [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Renvoie :**
[IEffect](../../com.aspose.slides/ieffect) - Nouvel objet d'effet [IEffect](../../com.aspose.slides/ieffect)