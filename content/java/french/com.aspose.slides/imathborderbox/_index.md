---
title: IMathBorderBox
second_title: Référence de l'API Aspose.Slides pour Java
description: Dessine une bordure rectangulaire ou autre autour de l'IMathElement.
type: docs
url: /fr/com.aspose.slides/imathborderbox/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Dessine une bordure rectangulaire ou autre autour de l'IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBase()](#getBase--) | Argument de base |
| [getHideTop()](#getHideTop--) | Masquer le bord supérieur (false par défaut) - spécifie l'état masqué ou affiché du bord supérieur de la boîte de bordure. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Masquer le bord supérieur (false par défaut) - spécifie l'état masqué ou affiché du bord supérieur de la boîte de bordure. |
| [getHideBottom()](#getHideBottom--) | Masquer le bord inférieur (false par défaut) - spécifie l'état masqué ou affiché du bord inférieur de la boîte de bordure. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Masquer le bord inférieur (false par défaut) - spécifie l'état masqué ou affiché du bord inférieur de la boîte de bordure. |
| [getHideLeft()](#getHideLeft--) | Masquer le bord gauche (false par défaut) - spécifie l'état masqué ou affiché du bord gauche de la boîte de bordure. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Masquer le bord gauche (false par défaut) - spécifie l'état masqué ou affiché du bord gauche de la boîte de bordure. |
| [getHideRight()](#getHideRight--) | Masquer le bord droit (false par défaut) - spécifie l'état masqué ou affiché du bord droit de la boîte de bordure. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Masquer le bord droit (false par défaut) - spécifie l'état masqué ou affiché du bord droit de la boîte de bordure. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Barre horizontale (false par défaut) - spécifie l'état masqué ou affiché d'une ligne de barre horizontale. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Barre horizontale (false par défaut) - spécifie l'état masqué ou affiché d'une ligne de barre horizontale. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Barre verticale (false par défaut) - spécifie l'état masqué ou affiché d'une ligne de barre verticale. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Barre verticale (false par défaut) - spécifie l'état masqué ou affiché d'une ligne de barre verticale. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Barre du coin inférieur gauche au coin supérieur droit (false par défaut). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Barre du coin inférieur gauche au coin supérieur droit (false par défaut). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Barre du coin supérieur gauche au coin inférieur droit (false par défaut). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Barre du coin supérieur gauche au coin inférieur droit (false par défaut). |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argument de base

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```

**Retour :**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```


Masquer le bord supérieur (false par défaut) - spécifie l'état masqué ou affiché du bord supérieur de la boîte de bordure.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Retour :**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```


Masquer le bord supérieur (false par défaut) - spécifie l'état masqué ou affiché du bord supérieur de la boîte de bordure.

--------------------

> ```
> Example:
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
> Exemple:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Retour :**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```


Masquer le bord inférieur (false par défaut) - spécifie l'état masqué ou affiché du bord inférieur de la boîte de bordure.

--------------------

> ```
> Exemple:
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
> Exemple:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Retour :**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```


Masquer le bord gauche (false par défaut) - spécifie l'état masqué ou affiché du bord gauche de la boîte de bordure.

--------------------

> ```
> Example:
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
> Exemple:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```


**Retour :**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```


Masquer le bord droit (false par défaut) - spécifie l'état masqué ou affiché du bord droit de la boîte de bordure.

--------------------

> ```
> Exemple:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```


Barre horizontale (false par défaut) - spécifie l'état masqué ou affiché d'une ligne de barre horizontale.

--------------------

> ```
> Exemple:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```


**Retour :**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```


Barre horizontale (false par défaut) - spécifie l'état masqué ou affiché d'une ligne de barre horizontale.

--------------------

> ```
> Exemple:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```


Barre verticale (false par défaut) - spécifie l'état masqué ou affiché d'une ligne de barre verticale.

--------------------

> ```
> Exemple:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Retour :**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```


Barre verticale (false par défaut) - spécifie l'état masqué ou affiché d'une ligne de barre verticale.

--------------------

> ```
> Exemple:
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


Barre du coin inférieur gauche au coin supérieur droit (false par défaut). Spécifie l'état masqué ou affiché d'une ligne de barre diagonale du coin inférieur gauche au coin supérieur droit de la boîte de bordure.

--------------------

> ```
> Exemple:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Retour :**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```


Barre du coin inférieur gauche au coin supérieur droit (false par défaut). Spécifie l'état masqué ou affiché d'une ligne de barre diagonale du coin inférieur gauche au coin supérieur droit de la boîte de bordure.

--------------------

> ```
> Exemple:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```


Barre du coin supérieur gauche au coin inférieur droit (false par défaut). Spécifie l'état masqué ou affiché d'une ligne de barre diagonale du coin supérieur gauche au coin inférieur droit de la boîte de bordure.

--------------------

> ```
> Exemple:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Retour :**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```


Barre du coin supérieur gauche au coin inférieur droit (false par défaut). Spécifie l'état masqué ou affiché d'une ligne de barre diagonale du coin supérieur gauche au coin inférieur droit de la boîte de bordure.

--------------------

> ```
> Exemple:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |