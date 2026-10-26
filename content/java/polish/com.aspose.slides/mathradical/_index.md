---
title: MathRadical
second_title: Aspose.Slides dla Java – odniesienie API
description: Określa funkcję pierwiastka składającą się z podstawy i opcjonalnego stopnia.
type: docs
url: /pl/com.aspose.slides/mathradical/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathRadical](../../com.aspose.slides/imathradical), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathRadical extends MathElementBase implements IMathRadical, IHasControlCharacterProperties
```

Określa funkcję pierwiastka, składającą się z podstawy i opcjonalnego stopnia. Przykładem obiektu radical jest \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicjalizuje nową instancję klasy MathRadical. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getBase()](#getBase--) | Argument podstawy |
| [getDegree()](#getDegree--) | Argument stopnia |
| [getHideDegree()](#getHideDegree--) | Ukryj stopień. Gdy wartość jest true, stopień nie jest wyświetlany, tak jak w \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Ukryj stopień. Gdy wartość jest true, stopień nie jest wyświetlany, tak jak w \\u221a\\ud835\\udc65 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Właściwości znaków kontrolnych |
| [getChildren()](#getChildren--) | Pobierz elementy potomne |
### MathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```


Inicjalizuje nową instancję klasy MathRadical.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Podstawa |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | Stopień |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argument podstawy

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement baseElem = radical.getBase();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public final IMathElement getDegree()
```


Argument stopnia

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement degreeElem = radical.getDegree();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public final boolean getHideDegree()
```


Ukryj stopień. Gdy wartość jest true, stopień nie jest wyświetlany, tak jak w \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**Zwraca:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public final void setHideDegree(boolean value)
```


Ukryj stopień. Gdy wartość jest true, stopień nie jest wyświetlany, tak jak w \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Właściwości znaków kontrolnych

**Zwraca:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Pobierz elementy potomne

**Zwraca:**
com.aspose.slides.IMathElement[]