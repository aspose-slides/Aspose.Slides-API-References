---
title: MathArray
second_title: Référence de l'API Aspose.Slides pour Java
description: Spécifie un tableau vertical d'équations ou de tout objet mathématique
type: docs
url: /fr/com.aspose.slides/matharray/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Toutes les interfaces implémentées :**
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
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Crée un tableau mathématique et place l’élément spécifié dans celui-ci |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Crée un tableau mathématique et place les éléments spécifiés dans celui-ci |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getArguments()](#getArguments--) | L’ensemble des éléments du tableau |
| [getBaseJustification()](#getBaseJustification--) | Spécifie l’alignement du tableau par rapport au texte environnant. Le texte extérieur au tableau peut être aligné avec le bas, le haut ou le centre d’un objet tableau. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Spécifie l’alignement du tableau par rapport au texte environnant. Le texte extérieur au tableau peut être aligné avec le bas, le haut ou le centre d’un objet tableau. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum Distribution When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum Distribution When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.). |
| [getObjectDistribution()](#getObjectDistribution--) | Object Distribution When true, the contents of the array are spaced to the maximum width of the array object. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Object Distribution When true, the contents of the array are spaced to the maximum width of the array object. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Le type d’espacement vertical entre les éléments du tableau. Valeur par défaut : SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Le type d’espacement vertical entre les éléments du tableau. Valeur par défaut : SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | Espacement entre les rangées du tableau. Utilisé uniquement lorsque RowSpacingRule vaut 3. Dans ce cas, l’unité de mesure est le point ou Multiple, auquel cas l’unité est la demi-ligne. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Espacement entre les rangées du tableau. Utilisé uniquement lorsque RowSpacingRule vaut 3. Dans ce cas, l’unité de mesure est le point ou Multiple, auquel cas l’unité est la demi-ligne. |
| [getChildren()](#getChildren--) | Obtient les éléments enfants |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```


Crée un tableau mathématique et place l’élément spécifié dans celui-ci

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L’élément à placer dans le tableau |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```


Crée un tableau mathématique et place les éléments spécifiés dans celui-ci

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Éléments à placer dans le tableau |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```


L’ensemble des éléments du tableau

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Valeur de retour :**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```


Spécifie l’alignement du tableau par rapport au texte environnant. Le texte extérieur au tableau peut être aligné avec le bas, le haut ou le centre d’un objet tableau. Valeur par défaut : Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Valeur de retour :**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```


Spécifie l’alignement du tableau par rapport au texte environnant. Le texte extérieur au tableau peut être aligné avec le bas, le haut ou le centre d’un objet tableau. Valeur par défaut : Center

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
public final boolean getMaximumDistribution()
```


Maximum Distribution When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.).

--------------------

> ```
> Exemple:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Valeur de retour :**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```


Maximum Distribution When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.).

--------------------

> ```
> Exemple:
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
public final boolean getObjectDistribution()
```


Object Distribution When true, the contents of the array are spaced to the maximum width of the array object.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Valeur de retour :**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```


Object Distribution When true, the contents of the array are spaced to the maximum width of the array object.

--------------------

> ```
> Exemple:
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
public final int getRowSpacingRule()
```


Le type d’espacement vertical entre les éléments du tableau. Valeur par défaut : SingleLineGap

--------------------

> ```
> Exemple:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Valeur de retour :**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```


Le type d’espacement vertical entre les éléments du tableau. Valeur par défaut : SingleLineGap

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
public final long getRowSpacing()
```


Espacement entre les rangées du tableau. Utilisé uniquement lorsque RowSpacingRule vaut 3. Dans ce cas, l’unité de mesure est le point ou Multiple, auquel cas l’unité est la demi-ligne. Valeur par défaut : 0

--------------------

> ```
> Exemple:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Valeur de retour :**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```


Espacement entre les rangées du tableau. Utilisé uniquement lorsque RowSpacingRule vaut 3. Dans ce cas, l’unité de mesure est le point ou Multiple, auquel cas l’unité est la demi-ligne. Valeur par défaut : 0

--------------------

> ```
> Exemple:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Obtient les éléments enfants

**Valeur de retour :**
com.aspose.slides.IMathElement[]