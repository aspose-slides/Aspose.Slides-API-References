---
title: MathRadical
second_title: Aspose.Slides pro Java API Reference
description: Určuje radikální funkci, která se skládá ze základu a volitelného stupně.
type: docs
url: /cs/com.aspose.slides/mathradical/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Všechny implementované rozhraní:**
[com.aspose.slides.IMathRadical](../../com.aspose.slides/imathradical), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathRadical extends MathElementBase implements IMathRadical, IHasControlCharacterProperties
```

Specifikuje radikální funkci, skládající se ze základu a volitelného exponentu. Příklad radikálního objektu je \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicializuje novou instanci třídy MathRadical. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Argument základu |
| [getDegree()](#getDegree--) | Argument exponentu |
| [getHideDegree()](#getHideDegree--) | Skryje exponent. Když je true, exponent není zobrazen, například \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Skryje exponent. Když je true, exponent není zobrazen, například \\u221a\\ud835\\udc65 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vlastnosti řídících znaků |
| [getChildren()](#getChildren--) | Získá podřízené prvky |
### MathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```


Inicializuje novou instanci třídy MathRadical.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Základ |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | Exponent |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argument základu

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement baseElem = radical.getBase();
> ```

**Návratová hodnota:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public final IMathElement getDegree()
```


Argument exponentu

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement degreeElem = radical.getDegree();
> ```

**Návratová hodnota:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public final boolean getHideDegree()
```


Skryje exponent. Když je true, exponent není zobrazen, například \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**Návratová hodnota:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public final void setHideDegree(boolean value)
```


Skryje exponent. Když je true, exponent není zobrazen, například \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Vlastnosti řídících znaků

**Návratová hodnota:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Získá podřízené prvky

**Návratová hodnota:**
com.aspose.slides.IMathElement[]