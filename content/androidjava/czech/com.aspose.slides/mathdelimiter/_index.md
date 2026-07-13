---
title: MathDelimiter
second_title: Aspose.Slides pro Android - reference Java API
description: Specifikuje objekt oddělovače skládající se z otevíracích a uzavíracích znaků, jako jsou závorky, složené závorky, hranaté závorky a svislé čáry, a jednoho nebo více matematických prvků uvnitř, oddělených zadaným znakem.
type: docs
url: /cs/com.aspose.slides/mathdelimiter/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Specifikuje objekt oddělovače, který se skládá z otevíracích a uzavíracích znaků (například závorky, složené závorky, hranaté závorky a svislé čáry) a jednoho nebo více matematických prvků uvnitř, oddělených zadaným znakem. Příklady: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Inicializuje MathDelimiter se zadaným prvkem jako jediným základním argumentem |
## Metody

| Metoda | Popis |
| --- | --- |
| [getArguments()](#getArguments--) | Jeden nebo více matematických prvků oddělených znaky oddělovače |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character určuje počáteční, tj. otevírací znak oddělovače. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character určuje počáteční, tj. otevírací znak oddělovače. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character určuje znak, který odděluje argumenty v objektu oddělovače. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character určuje znak, který odděluje argumenty v objektu oddělovače. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character určuje koncový, tj. uzavírací znak oddělovače. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character určuje koncový, tj. uzavírací znak oddělovače. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter When true, the delimiters grows vertically to match its operand height. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter When true, the delimiters grows vertically to match its operand height. |
| [getDelimiterShape()](#getDelimiterShape--) | Určuje tvar oddělovačů v objektu oddělovače. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Určuje tvar oddělovačů v objektu oddělovače. |
| [delimit(char separatorCharacter)](#delimit-char-) | Odděluje argumenty pomocí zadaného znaku oddělovače |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Obaluje matematický prvek ve specifikovaných znacích, jako jsou závorky nebo jiné znaky jako rámování |
| [getChildren()](#getChildren--) | Získá podřízené prvky |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

Inicializuje MathDelimiter se zadaným prvkem jako jediným základním argumentem

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Základní prvek, na který je aplikován oddělovač. Může být null. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Jeden nebo více matematických prvků oddělených znaky oddělovače

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Vrací:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```

Delimiter Beginning Character určuje počáteční, tj. otevírací znak oddělovače. Matematiké oddělovače jsou uzavírací znaky jako závorky, hranaté závorky a složené závorky. Výchozí: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Vrací:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```

Delimiter Beginning Character určuje počáteční, tj. otevírací znak oddělovače. Matematiké oddělovače jsou uzavírací znaky jako závorky, hranaté závorky a složené závorky. Výchozí: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public final char getSeparatorCharacter()
```

Delimiter Separator Character určuje znak, který odděluje argumenty v objektu oddělovače. Výchozí: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Vrací:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```

Delimiter Separator Character určuje znak, který odděluje argumenty v objektu oddělovače. Výchozí: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public final char getEndingCharacter()
```

Delimiter Ending Character určuje koncový, tj. uzavírací znak oddělovače. Matematiké oddělovače jsou uzavírací znaky jako závorky, hranaté závorky a složené závorky. Výchozí: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Vrací:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```

Delimiter Ending Character určuje koncový, tj. uzavírací znak oddělovače. Matematiké oddělovače jsou uzavírací znaky jako závorky, hranaté závorky a složené závorky. Výchozí: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter When true, the delimiters grows vertically to match its operand height. Výchozí hodnota je true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Vrací:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter When true, the delimiters grows vertically to match its operand height. Výchozí hodnota je true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public final int getDelimiterShape()
```

Určuje tvar oddělovačů v objektu oddělovače. Když je MathDelimiterShape.Centered, jsou oddělovače centrovány kolem matematické osy textu a stále se přizpůsobí celé výšce jejich obsahu. Když je MathDelimiterShape.Match, jejich výška a tvar jsou změněny tak, aby přesně odpovídaly jejich obsahu.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Vrací:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```

Určuje tvar oddělovačů v objektu oddělovače. Když je MathDelimiterShape.Centered, jsou oddělovače centrovány kolem matematické osy textu a stále se přizpůsobí celé výšce jejich obsahu. Když je MathDelimiterShape.Match, jejich výška a tvar jsou změněny tak, aby přesně odpovídaly jejich obsahu.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Odděluje argumenty pomocí zadaného znaku oddělovače

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| separatorCharacter | char | znak oddělovače |

**Vrací:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Tento objekt po aplikaci znaku oddělovače
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Obaluje matematický prvek ve specifikovaných znacích, jako jsou závorky nebo jiné znaky jako rámování

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| beginningCharacter | char | Počáteční znak (obvykle levá závorka) |
| endingCharacter | char | Koncový znak (obvykle pravá závorka) |

**Vrací:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Pokud jsou beginningCharacter a endingCharacter null, přiřadí se odpovídajícím vlastnostem hodnoty a nevytvoří se nový objekt (vrací tuto instanci). Jinak vrací nový matematický prvek typu Delimiter, který obsahuje specifikované znaky jako rámování a tuto instanci [MathDelimiter](../../com.aspose.slides/mathdelimiter) vnořené uvnitř.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Získá podřízené prvky

**Vrací:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**Vrací:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps