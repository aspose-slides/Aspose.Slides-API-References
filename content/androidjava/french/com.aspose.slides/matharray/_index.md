---
title: MathArray
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Spécifie un tableau vertical d'équations ou de tout objet mathématique
type: docs
url: /fr/com.aspose.slides/matharray/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)  
```
public final class MathArray extends MathElementBase implements IMathArray
```

Spécifie un tableau vertical d’équations ou de tout objet mathématique

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Creates a mathematical array and places the specified element in it |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Creates a mathematical array and places specified elements in it |
## Methods

| Method | Description |
| --- | --- |
| [getArguments()](#getArguments--) | The set of items of the array |
| [getBaseJustification()](#getBaseJustification--) | Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum Distribution When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum Distribution When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.). |
| [getObjectDistribution()](#getObjectDistribution--) | Object Distribution When true, the contents of the array are spaced to the maximum width of the array object. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Object Distribution When true, the contents of the array are spaced to the maximum width of the array object. |
| [getRowSpacingRule()](#getRowSpacingRule--) | The type of vertical spacing between array elements Default: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | The type of vertical spacing between array elements Default: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | Spacing between rows of an array It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points or Multiple in which case the unit of measure is half-lines. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Spacing between rows of an array It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points or Multiple in which case the unit of measure is half-lines. |
| [getChildren()](#getChildren--) | Get children elements |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

Creates a mathematical array and places the specified element in it

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | The element to place in the array |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

Creates a mathematical array and places specified elements in it

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Elements to place in the array |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Ensemble des éléments du tableau

--------------------

> ```
> Exemple :
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Renvoie:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

Spécifie l'alignement du tableau par rapport au texte environnant. Le texte à l'extérieur du tableau peut être aligné avec le bas, le haut ou le centre d'un objet tableau. Valeur par défaut : Center

--------------------

> ```
> Exemple :
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Renvoie :**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

Spécifie l'alignement du tableau par rapport au texte environnant. Le texte à l'extérieur du tableau peut être aligné avec le bas, le haut ou le centre d'un objet tableau. Valeur par défaut : Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public final boolean getMaximumDistribution()
```

Distribution maximale : lorsque true, le tableau est espacé à la largeur maximale de l'élément contenant (page, colonne, cellule, etc.).

--------------------

> ```
> Exemple :
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Renvoie :**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```

Distribution maximale : lorsque true, le tableau est espacé à la largeur maximale de l'élément contenant (page, colonne, cellule, etc.).

--------------------

> ```
> Exemple :
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public final boolean getObjectDistribution()
```

Distribution d'objet Lorsque true, le contenu du tableau est espacé à la largeur maximale de l'objet tableau.

--------------------

> ```
> Exemple :
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Renvoie :**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```

Distribution d'objet Lorsque true, le contenu du tableau est espacé à la largeur maximale de l'objet tableau.

--------------------

> ```
> Exemple :
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
>  ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public final int getRowSpacingRule()
```

Le type d'espacement vertical entre les éléments du tableau Valeur par défaut : SingleLineGap

--------------------

> ```
> Exemple :
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Renvoie :**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```

Le type d'espacement vertical entre les éléments du tableau Valeur par défaut : SingleLineGap

--------------------

> ```
> Exemple :
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```

Espacement entre les lignes d'un tableau. Il est utilisé uniquement lorsque RowSpacingRule est réglé sur 3 Exactly, auquel cas l'unité de mesure est les points ou Multiple, auquel cas l'unité est les demi-lignes. Valeur par défaut : 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Renvoie :**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```

Espacement entre les lignes d'un tableau. Il est utilisé uniquement lorsque RowSpacingRule est réglé sur 3 Exactly, auquel cas l'unité de mesure est les points ou Multiple, auquel cas l'unité est les demi-lignes. Valeur par défaut : 0

--------------------

> ```
> Exemple :
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()

Obtenir les éléments enfants

**Renvoie:**  
com.aspose.slides.IMathElement[]