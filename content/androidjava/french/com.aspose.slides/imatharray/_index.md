---
title: IMathArray
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Spécifie un tableau vertical d'équations ou tout objet mathématique
type: docs
url: /fr/com.aspose.slides/imatharray/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Spécifie un tableau vertical d'équations ou de tout objet mathématique

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
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
| [getRowSpacingRule()](#getRowSpacingRule--) | The type of vertical spacing between array elements |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | The type of vertical spacing between array elements |
| [getRowSpacing()](#getRowSpacing--) | Spacing between rows of an array It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points or Multiple in which case the unit of measure is half-lines. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Spacing between rows of an array It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points or Multiple in which case the unit of measure is half-lines. |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

The set of items of the array

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
>  ```

**Returns:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. Default value: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
>  ```

**Returns:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Spécifie l'alignement du tableau par rapport au texte environnant. Le texte à l'extérieur du tableau peut être aligné avec le bas, le haut ou le centre d'un objet tableau. Valeur par défaut : Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```

Distribution maximale Lorsque true, le tableau est espacé à la largeur maximale de l'élément contenant (page, colonne, cellule, etc.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
>  ```

**Returns:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

Distribution maximale Lorsque true, le tableau est espacé à la largeur maximale de l'élément contenant (page, colonne, cellule, etc.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```

Distribution d'objet Lorsque true, le contenu du tableau est espacé à la largeur maximale de l'objet tableau.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
>  ```

**Returns:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```

Distribution d'objet Lorsque true, le contenu du tableau est espacé à la largeur maximale de l'objet tableau.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public abstract int getRowSpacingRule()
```

Le type d'espacement vertical entre les éléments du tableau

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
>  ```

**Returns:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public abstract void setRowSpacingRule(int value)
```

The type of vertical spacing between array elements

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public abstract long getRowSpacing()
```

Espacement entre les lignes d'un tableau Il est utilisé uniquement lorsque RowSpacingRule est réglé sur 3 Exactly auquel cas l'unité de mesure est en points ou Multiple auquel cas l'unité de mesure est en demi-lignes. Valeur par défaut: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
>  ```

**Returns:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)


Spacing between rows of an array It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points or Multiple in which case the unit of measure is half-lines. Default: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |