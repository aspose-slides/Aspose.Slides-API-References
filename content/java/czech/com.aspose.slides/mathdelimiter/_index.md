---
title: MathDelimiter
second_title: Aspose.Slides pro Java API Reference
description: Určuje objekt oddělovače, který se skládá z otevíracích a uzavíracích znaků, jako jsou závorky, složené závorky, hranaté závorky a svislé čáry, a z jednoho nebo více matematických prvků uvnitř, oddělených zadaným znakem.
type: docs
url: /cs/com.aspose.slides/mathdelimiter/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Všechny implementované rozhraní:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Určuje objekt oddělovače, který se skládá z otevíracích a uzavíracích znaků (např. závorky, složené závorky, hranaté závorky a svislé čáry) a jednoho nebo více matematických prvků uvnitř, oddělených zadaným znakem. Příklady: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

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
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Inicializuje MathDelimiter s určeným prvkem jako jediným základním argumentem |
## Metody

| Metoda | Popis |
| --- | --- |
| [getArguments()](#getArguments--) | Jeden nebo více matematických prvků oddělených znaky oddělovače |
| [getBeginningCharacter()](#getBeginningCharacter--) | Znak začátku oddělovače určuje počáteční, nebo otevírací, znak oddělovače. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Znak začátku oddělovače určuje počáteční, nebo otevírací, znak oddělovače. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Znak oddělovače oddělovače určuje znak, který odděluje argumenty v objektu oddělovače. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Znak oddělovače oddělovače určuje znak, který odděluje argumenty v objektu oddělovače. |
| [getEndingCharacter()](#getEndingCharacter--) | Znak konce oddělovače určuje koncový, nebo uzavírací, znak oddělovače. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Znak konce oddělovače určuje koncový, nebo uzavírací, znak oddělovače. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Určuje růst BeginningCharacter, SeparatorCharacter, EndingCharacter. Když je true, oddělovače rostou svisle, aby odpovídaly výšce operandů. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Určuje růst BeginningCharacter, SeparatorCharacter, EndingCharacter. Když je true, oddělovače rostou svisle, aby odpovídaly výšce operandů. |
| [getDelimiterShape()](#getDelimiterShape--) | Určuje tvar oddělovačů v objektu oddělovače. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Určuje tvar oddělovačů v objektu oddělovače. |
| [delimit(char separatorCharacter)](#delimit-char-) | Odděluje argumenty pomocí zadaného znaku oddělovače |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Zahrnuje matematický prvek do určených znaků, jako jsou závorky nebo jiné znaky jako rámování |
| [getChildren()](#getChildren--) | Získá podřízené prvky |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vlastnosti řídícího znaku |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

Inicializuje MathDelimiter s určeným prvkem jako jediným základním argumentem

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
| element | [IMathElement](../../com.aspose.slides/imathelement) | Základní prvek, na který se aplikuje oddělovač. Může být null. |

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

**Návratová hodnota:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```

Znak začátku oddělovače určuje počáteční, nebo otevírací, znak oddělovače. Matematické oddělovače jsou ohraničující znaky, jako jsou závorky, hranaté závorky a složené závorky. Výchozí: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
>```

**Návratová hodnota:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```

Znak začátku oddělovače určuje počáteční, nebo otevírací, znak oddělovače. Matematické oddělovače jsou ohraničující znaky, jako jsou závorky, hranaté závorky a složené závorky. Výchozí: '('.

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

Znak oddělovače oddělovače určuje znak, který odděluje argumenty v objektu oddělovače. Výchozí: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Návratová hodnota:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```

Znak oddělovače oddělovače určuje znak, který odděluje argumenty v objektu oddělovače. Výchozí: '|'.

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

Znak konce oddělovače určuje koncový, nebo uzavírací, znak oddělovače. Matematické oddělovače jsou ohraničující znaky, jako jsou závorky, hranaté závorky a složené závorky. Výchozí: ')'.

--------------------

> ```
> Příklad:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Návratová hodnota:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```

Znak konce oddělovače určuje koncový, nebo uzavírací, znak oddělovače. Matematické oddělovače jsou ohraničující znaky, jako jsou závorky, hranaté závorky a složené závorky. Výchozí: ')'.

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

Určuje růst BeginningCharacter, SeparatorCharacter, EndingCharacter. Když je true, oddělovače rostou svisle, aby odpovídaly výšce operandů. Výchozí hodnota je true

--------------------

> ```
> Příklad:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Návratová hodnota:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

Určuje růst BeginningCharacter, SeparatorCharacter, EndingCharacter. Když je true, oddělovače rostou svisle, aby odpovídaly výšce operandů. Výchozí hodnota je true

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

Určuje tvar oddělovačů v objektu oddělovače. Když je MathDelimiterShape.Centered, oddělovače jsou centrovány kolem matematické osy textu a stále se přizpůsobí celé výšce jejich obsahu. Když je MathDelimiterShape.Match, jejich výška a tvar jsou upraveny tak, aby přesně odpovídaly jejich obsahu.

--------------------

> ```
> Příklad:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Návratová hodnota:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```

Určuje tvar oddělovačů v objektu oddělovače. Když je MathDelimiterShape.Centered, oddělovače jsou centrovány kolem matematické osy textu a stále se přizpůsobí celé výšce jejich obsahu. Když je MathDelimiterShape.Match, jejich výška a tvar jsou upraveny tak, aby přesně odpovídaly jejich obsahu.

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

**Návratová hodnota:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Tento objekt po aplikaci znaku oddělovače
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Zahrnuje matematický prvek do určených znaků, jako jsou závorky nebo jiné znaky jako rámování

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

**Návratová hodnota:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Pokud jsou beginningCharacter a endingCharacter null, příslušné vlastnosti jsou jen přiřazeny a není vytvořen nový objekt (vrací tuto instanci). V opačném případě vrací nový matematický prvek typu Delimiter, který obsahuje zadané znaky jako rámování a tuto instanci [MathDelimiter](../../com.aspose.slides/mathdelimiter) vloženou dovnitř.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Získá podřízené prvky

**Návratová hodnota:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Vlastnosti řídících znaků

**Návratová hodnota:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps