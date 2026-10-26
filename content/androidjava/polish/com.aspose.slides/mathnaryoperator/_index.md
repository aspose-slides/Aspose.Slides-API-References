---
title: MathNaryOperator
second_title: Aspose.Slides dla Androida – odniesienie do API Java
description: Określa obiekt matematyczny N-ary, taki jak sumowanie i całka.
type: docs
url: /pl/com.aspose.slides/mathnaryoperator/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

Określa obiekt matematyczny N-ary, taki jak sumowanie i całka. Składa się z operatora, bazy (lub operandów) oraz opcjonalnych górnych i dolnych granic. Przykłady operatorów N-ary to: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicjalizuje nową instancję klasy MathNaryOperator. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicjalizuje nową instancję klasy MathNaryOperator. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | Inicjalizuje nową instancję klasy MathNaryOperator. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getBase()](#getBase--) | Argument podstawowy |
| [getSubscript()](#getSubscript--) | Określa argument indeksu dolnego, który na przykład w przypadku całki ustawia granicę dolną |
| [getSuperscript()](#getSuperscript--) | Określa argument indeksu górnego, który na przykład w przypadku całki ustawia granicę górną |
| [getOperator()](#getOperator--) | Znak operatora N-ary, na przykład: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Znak operatora N-ary, na przykład: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Położenie granic (indeks dolny i górny) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Położenie granic (indeks dolny i górny) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Znak operatora rośnie pionowo, aby dopasować się do wysokości operandów |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Znak operatora rośnie pionowo, aby dopasować się do wysokości operandów |
| [getHideSubscript()](#getHideSubscript--) | Ukryj indeks dolny |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Ukryj indeks dolny |
| [getHideSuperscript()](#getHideSuperscript--) | Ukryj indeks górny |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Ukryj indeks górny |
| [getChildren()](#getChildren--) | Pobierz elementy potomne |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Właściwości znaków kontrolnych |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

Inicjalizuje nową instancję klasy MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| operatorSymbol | char | Symbol operatora N-ary |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument podstawowy |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Granica dolna |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Granica górna |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

Inicjalizuje nową instancję klasy MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| operatorSymbol | char | Symbol operatora N-ary |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument podstawowy |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Granica dolna |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

Inicjalizuje nową instancję klasy MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| operatorSymbol | char | Symbol operatora N-ary |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument podstawowy |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argument podstawowy

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

Określa argument indeksu dolnego, który na przykład w przypadku całki ustawia granicę dolną

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

Określa argument indeksu górnego, który na przykład w przypadku całki ustawia granicę górną

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```

Znak operatora N-ary, na przykład: '\\u2211', '\\u222b'

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Zwraca:**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```

Znak operatora N-ary, na przykład: '\\u2211', '\\u222b'

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```

Położenie granic (indeks dolny i górny)

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Zwraca:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```

Położenie granic (indeks dolny i górny)

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

Znak operatora rośnie pionowo, aby dopasować się do wysokości operandów

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Zwraca:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

Znak operatora rośnie pionowo, aby dopasować się do wysokości operandów

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public final boolean getHideSubscript()
```

Ukryj indeks dolny

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Zwraca:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```

Ukryj indeks dolny

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```

Ukryj indeks górny

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Zwraca:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```

Ukryj indeks górny

--------------------

> ```
> Przykład:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Pobierz elementy potomne

**Zwraca:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Właściwości znaków kontrolnych

**Zwraca:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps