---
title: MathNaryOperator
second_title: Référence de l'API Aspose.Slides pour Java
description: Spécifie un objet mathématique N-aire tel que la sommation et l'intégrale.
type: docs
url: /fr/com.aspose.slides/mathnaryoperator/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

Spécifie un objet mathématique N-aire, tel que la sommation et l'intégrale. Il se compose d'un opérateur, d'une base (ou opérande) et de limites supérieures et inférieures facultatives. Des exemples d'opérateurs N-aires sont : sommation, union, intersection, intégrale

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialise une nouvelle instance de la classe MathNaryOperator. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialise une nouvelle instance de la classe MathNaryOperator. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | Initialise une nouvelle instance de la classe MathNaryOperator. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBase()](#getBase--) | Argument de base |
| [getSubscript()](#getSubscript--) | Spécifie un argument d'indice qui, par exemple, dans le cas d'une intégrale, définit la limite inférieure |
| [getSuperscript()](#getSuperscript--) | Spécifie un argument d'exposant qui, par exemple, dans le cas d'une intégrale, définit la limite supérieure |
| [getOperator()](#getOperator--) | Caractère d'opérateur N-aire Par exemple : '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Caractère d'opérateur N-aire Par exemple : '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | L'emplacement des limites (indice et exposant) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | L'emplacement des limites (indice et exposant) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Le caractère d'opérateur s'étend verticalement pour correspondre à la hauteur de son opérande |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Le caractère d'opérateur s'étend verticalement pour correspondre à la hauteur de son opérande |
| [getHideSubscript()](#getHideSubscript--) | Masquer l'indice |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Masquer l'indice |
| [getHideSuperscript()](#getHideSuperscript--) | Masquer l'exposant |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Masquer l'exposant |
| [getChildren()](#getChildren--) | Obtenir les éléments enfants |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propriétés du caractère de contrôle |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Initialise une nouvelle instance de la classe MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | Symbole de l'opérateur N-aire |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument de base |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inférieure |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite supérieure |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Initialise une nouvelle instance de la classe MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | Symbole de l'opérateur N-aire |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument de base |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inférieure |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Initialise une nouvelle instance de la classe MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | Symbole de l'opérateur N-aire |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument de base |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argument de base

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**Renvoie :**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


Spécifie un argument d'indice qui, par exemple, dans le cas d'une intégrale, définit la limite inférieure

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Renvoie :**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


Spécifie un argument d'exposant qui, par exemple, dans le cas d'une intégrale, définit la limite supérieure

--------------------

> ```
> Exemple:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Renvoie :**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```


Caractère d'opérateur N-aire Par exemple : '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Renvoie :**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```


Caractère d'opérateur N-aire Par exemple : '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```


L'emplacement des limites (indice et exposant)

--------------------

> ```
> Exemple:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Renvoie :**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```


L'emplacement des limites (indice et exposant)

--------------------

> ```
> Exemple:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```


Le caractère d'opérateur s'étend verticalement pour correspondre à la hauteur de son opérande

--------------------

> ```
> Exemple:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Renvoie :**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```


Le caractère d'opérateur s'étend verticalement pour correspondre à la hauteur de son opérande

--------------------

> ```
> Exemple:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public final boolean getHideSubscript()
```


Masquer l'indice

--------------------

> ```
> Exemple:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Renvoie :**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```


Masquer l'indice

--------------------

> ```
> Exemple:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```


Masquer l'exposant

--------------------

> ```
> Exemple:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Renvoie :**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```


Masquer l'exposant

--------------------

> ```
> Exemple:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Obtenir les éléments enfants

**Renvoie :**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Propriétés du caractère de contrôle

**Renvoie :**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps