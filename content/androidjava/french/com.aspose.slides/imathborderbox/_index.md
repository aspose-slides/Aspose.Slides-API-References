---
title: IMathBorderBox
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Dessine un rectangle ou une autre bordure autour de l'IMathElement.
type: docs
url: /fr/com.aspose.slides/imathborderbox/
---
**Toutes les interfaces implémentées :**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Dessine un rectangle ou une autre bordure autour de l'IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getHideTop()](#getHideTop--) | Hide Top Edge (default is false) - specifies the hidden or shown state of the top edge of border box. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Hide Top Edge (default is false) - specifies the hidden or shown state of the top edge of border box. |
| [getHideBottom()](#getHideBottom--) | Hide Bottom Edge (default is false) - specifies the hidden or shown state of the bottom edge of border box. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Hide Bottom Edge (default is false) - specifies the hidden or shown state of the bottom edge of border box. |
| [getHideLeft()](#getHideLeft--) | Hide Left Edge (default is false) - specifies the hidden or shown state of the left edge of border box. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Hide Left Edge (default is false) - specifies the hidden or shown state of the left edge of border box. |
| [getHideRight()](#getHideRight--) | Hide Right Edge (default is false) - specifies the hidden or shown state of the right edge of border box. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Hide Right Edge (default is false) - specifies the hidden or shown state of the right edge of border box. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Strikethrough Horizontal (default is false) - specifies the hidden or shown state of a strikethrough horizontal line. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Strikethrough Horizontal (default is false) - specifies the hidden or shown state of a strikethrough horizontal line. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Strikethrough Vertical (default is false) - specifies the hidden or shown state of a strikethrough vertical line. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Strikethrough Vertical (default is false) - specifies the hidden or shown state of a strikethrough vertical line. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Strikethrough Bottom-Left to Top-Right (default is false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Strikethrough Bottom-Left to Top-Right (default is false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Strikethrough Top-Left to Bottom-Right (default is false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Strikethrough Top-Left to Bottom-Right (default is false). |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Base argument

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```

Masquer le bord supérieur (false par défaut) - spécifie l'état masqué ou affiché du bord supérieur de la boîte de bordure.

--------------------

> ```
> Exemple :
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Renvoie :**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```

Masquer le bord supérieur (false par défaut) - spécifie l'état masqué ou affiché du bord supérieur de la boîte de bordure.

--------------------

> ```
> Exemple :
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```

Masquer le bord inférieur (false par défaut) - spécifie l'état masqué ou affiché du bord inférieur de la boîte de bordure.

--------------------

> ```
> Exemple :
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Renvoie :**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```

Masquer le bord inférieur (false par défaut) - spécifie l'état masqué ou affiché du bord inférieur de la boîte de bordure.

--------------------

> ```
> Exemple :
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```

Masquer le bord gauche (false par défaut) - spécifie l'état masqué ou affiché du bord gauche de la boîte de bordure.

--------------------

> ```
> Exemple :
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Renvoie :**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```

Masquer le bord gauche (false par défaut) - spécifie l'état masqué ou affiché du bord gauche de la boîte de bordure.

--------------------

> ```
> Exemple :
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```

Masquer le bord droit (false par défaut) - spécifie l'état masqué ou affiché du bord droit de la boîte de bordure.

--------------------

> ```
> Exemple :
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Renvoie :**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```

Hide Right Edge (default is false) - specifies the hidden or shown state of the right edge of border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```

Rayure horizontale (false par défaut) - spécifie l'état masqué ou affiché d'une ligne de rayure horizontale.

--------------------

> ```
> Exemple :
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Renvoie :**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```

Rayure horizontale (false par défaut) - spécifie l'état masqué ou affiché d'une ligne de rayure horizontale.

--------------------

> ```
> Exemple :
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```
 
Strikethrough Vertical (default is false) - specifies the hidden or shown state of a strikethrough vertical line.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Returns:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```

Rayure verticale (false par défaut) - spécifie l'état masqué ou affiché d'une ligne de rayure verticale.

--------------------

> ```
> Exemple :
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```

Rayure diagonale du coin inférieur gauche au coin supérieur droit (false par défaut). Spécifie l'état masqué ou affiché d'une ligne de rayure diagonale du coin inférieur gauche au coin supérieur droit de la boîte de bordure.

--------------------

> ```
> Exemple :
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Renvoie :**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```

Strikethrough Bottom-Left to Top-Right (default is false). Specifies the hidden or shown state of a strikethrough diagonal line from the bottom-left corner to the top-right corner of border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```

Strikethrough Top-Left to Bottom-Right (default is false). Specifies the hidden or shown state of a strikethrough diagonal line from the top-left corner to the bottom-right corner of border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Returns:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)

Rayure diagonale du coin supérieur gauche au coin inférieur droit (false par défaut). Spécifie l'état masqué ou affiché d'une ligne de rayure diagonale du coin supérieur gauche au coin inférieur droit de la boîte de bordure.

--------------------

> ```
> Exemple :
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |