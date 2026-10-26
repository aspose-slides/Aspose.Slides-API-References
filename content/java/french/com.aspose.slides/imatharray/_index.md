---
title: IMathArray
second_title: Référence de l'API Aspose.Slides pour Java
description: Spécifie un tableau vertical d'équations ou tout objet mathématique
type: docs
url: /fr/com.aspose.slides/imatharray/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Spécifie un tableau vertical d'équations ou tout objet mathématique

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [getArguments()](#getArguments--) | Ensemble d'éléments du tableau |
| [getBaseJustification()](#getBaseJustification--) | Spécifie l'alignement de l'array par rapport au Text environnant. Le Text à l'extérieur de l'array peut être aligné avec le bas, le haut ou le centre d'un objet array. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Spécifie l'alignement de l'array par rapport au Text environnant. Le Text à l'extérieur de l'array peut être aligné avec le bas, le haut ou le centre d'un objet array. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Distribution maximale Lorsqu'il est vrai, l'array est espacé à la largeur maximale de l'élément contenant (page, column, cell, etc.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Distribution maximale Lorsqu'il est vrai, l'array est espacé à la largeur maximale de l'élément contenant (page, column, cell, etc.). |
| [getObjectDistribution()](#getObjectDistribution--) | Distribution d'objet Lorsqu'il est vrai, le contenu de l'array est espacé à la largeur maximale de l'objet array. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Distribution d'objet Lorsqu'il est vrai, le contenu de l'array est espacé à la largeur maximale de l'objet array. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Le type d'espacement vertical entre les éléments de l'array |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Le type d'espacement vertical entre les éléments de l'array |
| [getRowSpacing()](#getRowSpacing--) | Espacement entre les lignes d'un array. Il n'est utilisé que lorsque RowSpacingRule est réglé à 3 Exactly, auquel cas l'unité de mesure est points ou Multiple, auquel cas l'unité de mesure est demi-lignes. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Espacement entre les lignes d'un array. Il n'est utilisé que lorsque RowSpacingRule est réglé à 3 Exactly, auquel cas l'unité de mesure est points ou Multiple, auquel cas l'unité de mesure est demi-lignes. |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Ensemble d'éléments du tableau

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Retour :**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

Spécifie l'alignement de l'array par rapport au Text environnant. Le Text à l'extérieur de l'array peut être aligné avec le bas, le haut ou le centre d'un objet array. Valeur par défaut : Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Retour :**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Spécifie l'alignement de l'array par rapport au Text environnant. Le Text à l'extérieur de l'array peut être aligné avec le bas, le haut ou le centre d'un objet array. Valeur par défaut : Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```

Distribution maximale Lorsqu'il est vrai, l'array est espacé à la largeur maximale de l'élément contenant (page, column, cell, etc.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Retour :**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

Distribution maximale Lorsqu'il est vrai, l'array est espacé à la largeur maximale de l'élément contenant (page, column, cell, etc.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```

Distribution d'objet Lorsqu'il est vrai, le contenu de l'array est espacé à la largeur maximale de l'objet array.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Retour :**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```

Distribution d'objet Lorsqu'il est vrai, le contenu de l'array est espacé à la largeur maximale de l'objet array.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public abstract int getRowSpacingRule()
```

Le type d'espacement vertical entre les éléments de l'array

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Retour :**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public abstract void setRowSpacingRule(int value)
```

Le type d'espacement vertical entre les éléments de l'array

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public abstract long getRowSpacing()
```

Espacement entre les lignes d'un array. Il n'est utilisé que lorsque RowSpacingRule est réglé à 3 Exactly, auquel cas l'unité de mesure est points ou Multiple, auquel cas l'unité de mesure est demi-lignes. Valeur par défaut : 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Retour :**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```

Espacement entre les lignes d'un array. Il n'est utilisé que lorsque RowSpacingRule est réglé à 3 Exactly, auquel cas l'unité de mesure est points ou Multiple, auquel cas l'unité de mesure est demi-lignes. Valeur par défaut : 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |