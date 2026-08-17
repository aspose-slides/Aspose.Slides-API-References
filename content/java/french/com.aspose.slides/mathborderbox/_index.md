---
title: MathBorderBox
second_title: Référence de l'API Aspose.Slides pour Java
description: Dessine un bord rectangulaire ou autre autour de l'IMathElement.
type: docs
url: /fr/com.aspose.slides/mathborderbox/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

Dessine un bord rectangulaire ou autre autour de l'IMathElement.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Crée un élément MathBorderBox avec un bord rectangulaire |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Crée un élément MathBorderBox |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBase()](#getBase--) | Argument de base |
| [getHideTop()](#getHideTop--) | Masquer le bord supérieur (par défaut false) - spécifie l'état masqué ou affiché du bord supérieur de la boîte de bordure. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Masquer le bord supérieur (par défaut false) - spécifie l'état masqué ou affiché du bord supérieur de la boîte de bordure. |
| [getHideBottom()](#getHideBottom--) | Masquer le bord inférieur (par défaut false) - spécifie l'état masqué ou affiché du bord inférieur de la boîte de bordure. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Masquer le bord inférieur (par défaut false) - spécifie l'état masqué ou affiché du bord inférieur de la boîte de bordure. |
| [getHideLeft()](#getHideLeft--) | Masquer le bord gauche (par défaut false) - spécifie l'état masqué ou affiché du bord gauche de la boîte de bordure. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Masquer le bord gauche (par défaut false) - spécifie l'état masqué ou affiché du bord gauche de la boîte de bordure. |
| [getHideRight()](#getHideRight--) | Masquer le bord droit (par défaut false) - spécifie l'état masqué ou affiché du bord droit de la boîte de bordure. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Masquer le bord droit (par défaut false) - spécifie l'état masqué ou affiché du bord droit de la boîte de bordure. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Barrer horizontalement (par défaut false) - spécifie l'état masqué ou affiché d'une ligne horizontale barrée. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Barrer horizontalement (par défaut false) - spécifie l'état masqué ou affiché d'une ligne horizontale barrée. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Barrer verticalement (par défaut false) - spécifie l'état masqué ou affiché d'une ligne verticale barrée. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Barrer verticalement (par défaut false) - spécifie l'état masqué ou affiché d'une ligne verticale barrée. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Barrer du coin inférieur gauche au coin supérieur droit (par défaut false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Barrer du coin inférieur gauche au coin supérieur droit (par défaut false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Barrer du coin supérieur gauche au coin inférieur droit (par défaut false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Barrer du coin supérieur gauche au coin inférieur droit (par défaut false). |
| [getChildren()](#getChildren--) | Obtenir les éléments enfants |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propriétés des caractères de contrôle |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```

Crée un élément MathBorderBox avec un bord rectangulaire

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'élément de base auquel la boîte de bordure est appliquée. Peut être null. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Crée un élément MathBorderBox

--------------------

> ```
> Exemple:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'élément de base auquel la boîte de bordure est appliquée |
| hideTop | boolean | Masquer le bord supérieur |
| hideBottom | boolean | Masquer le bord inférieur |
| hideLeft | boolean | Masquer le bord gauche |
| hideRight | boolean | Masquer le bord droit |
| strikethroughHorizontal | boolean | Barrer horizontalement |
| strikethroughVertical | boolean | Barrer verticalement |
| strikethroughBottomLeftToTopRight | boolean | Barrer du coin inférieur gauche au coin supérieur droit |
| strikethroughTopLeftToBottomRight | boolean | Barrer du coin supérieur gauche au coin inférieur droit |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argument de base

--------------------

> ```
> Exemple:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**Retour :**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```

Masquer le bord supérieur (par défaut false) - spécifie l'état masqué ou affiché du bord supérieur de la boîte de bordure.

--------------------

> ```
> Exemple:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Retour :**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```

Masquer le bord supérieur (par défaut false) - spécifie l'état masqué ou affiché du bord supérieur de la boîte de bordure.

--------------------

> ```
> Exemple:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```

Masquer le bord inférieur (par défaut false) - spécifie l'état masqué ou affiché du bord inférieur de la boîte de bordure.

--------------------

> ```
> Exemple:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Retour :**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```

Masquer le bord inférieur (par défaut false) - spécifie l'état masqué ou affiché du bord inférieur de la boîte de bordure.

--------------------

> ```
> Exemple:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```

Masquer le bord gauche (par défaut false) - spécifie l'état masqué ou affiché du bord gauche de la boîte de bordure.

--------------------

> ```
> Exemple:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Retour :**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```

Masquer le bord gauche (par défaut false) - spécifie l'état masqué ou affiché du bord gauche de la boîte de bordure.

--------------------

> ```
> Exemple:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```

Masquer le bord droit (par défaut false) - spécifie l'état masqué ou affiché du bord droit de la boîte de bordure.

--------------------

> ```
> Exemple:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Retour :**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```

Masquer le bord droit (par défaut false) - spécifie l'état masqué ou affiché du bord droit de la boîte de bordure.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```

Barrer horizontalement (par défaut false) - spécifie l'état masqué ou affiché d'une ligne horizontale barrée.

--------------------

> ```
> Exemple:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Retour :**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```

Barrer horizontalement (par défaut false) - spécifie l'état masqué ou affiché d'une ligne horizontale barrée.

--------------------

> ```
> Exemple:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```

Barrer verticalement (par défaut false) - spécifie l'état masqué ou affiché d'une ligne verticale barrée.

--------------------

> ```
> Exemple:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Retour :**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```

Barrer verticalement (par défaut false) - spécifie l'état masqué ou affiché d'une ligne verticale barrée.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```

Barrer du coin inférieur gauche au coin supérieur droit (par défaut false). Spécifie l'état masqué ou affiché d'une ligne diagonale barrée du coin inférieur gauche au coin supérieur droit de la boîte de bordure.

--------------------

> ```
> Exemple:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Retour :**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```

Barrer du coin inférieur gauche au coin supérieur droit (par défaut false). Spécifie l'état masqué ou affiché d'une ligne diagonale barrée du coin inférieur gauche au coin supérieur droit de la boîte de bordure.

--------------------

> ```
> Exemple:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```

Barrer du coin supérieur gauche au coin inférieur droit (par défaut false). Spécifie l'état masqué ou affiché d'une ligne diagonale barrée du coin supérieur gauche au coin inférieur droit de la boîte de bordure.

--------------------

> ```
> Exemple:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Retour :**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```

Barrer du coin supérieur gauche au coin inférieur droit (par défaut false). Spécifie l'état masqué ou affiché d'une ligne diagonale barrée du coin supérieur gauche au coin inférieur droit de la boîte de bordure.

--------------------

> ```
> Exemple:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Obtient les éléments enfants

**Retour :**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Propriétés des caractères de contrôle

**Retour :**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps