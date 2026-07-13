---
title: MathFunction
second_title: Aspose.Slides dla Androida poprzez odniesienie do API Java
description: Określa funkcję argumentu.
type: docs
url: /pl/com.aspose.slides/mathfunction/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathFunction](../../com.aspose.slides/imathfunction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFunction extends MathElementBase implements IMathFunction, IHasControlCharacterProperties
```

Określa funkcję argumentu.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathFunction(IMathElement funcName, IMathElement baseArgument)](#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicjalizuje nową instancję klasy MathFunction. |
| [MathFunction(String funcName, IMathElement baseArgument)](#MathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Inicjalizuje nową instancję klasy MathFunction. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getName()](#getName--) | Nazwa funkcji Na przykład nazwy funkcji to sin i cos |
| [getBase()](#getBase--) | Argument funkcji |
| [getChildren()](#getChildren--) | Pobiera elementy potomne |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Właściwości znaków kontrolnych |
### MathFunction(IMathElement funcName, IMathElement baseArgument) {#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFunction(IMathElement funcName, IMathElement baseArgument)
```


Inicjalizuje nową instancję klasy MathFunction.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction(new MathematicalText("sin"), new MathematicalText("x"));
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### MathFunction(String funcName, IMathElement baseArgument) {#MathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public MathFunction(String funcName, IMathElement baseArgument)
```


Inicjalizuje nową instancję klasy MathFunction.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| funcName | java.lang.String |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getName() {#getName--}
```
public final IMathElement getName()
```


Nazwa funkcji Na przykład nazwy funkcji to sin i cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argument funkcji

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Pobiera elementy potomne

**Zwraca:**
com.aspose.slides.IMathElement[] - Tablica [IMathElement](../../com.aspose.slides/imathelement)
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Właściwości znaków kontrolnych

**Zwraca:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps