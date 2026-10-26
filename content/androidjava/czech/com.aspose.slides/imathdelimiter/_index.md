---
title: IMathDelimiter
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Specifikuje objekt oddělovače skládající se z otevíracích a uzavíracích znaků, jako jsou závorky, složené závorky, hranaté závorky a svislé čáry, a jednoho nebo více matematických prvků uvnitř, oddělených specifikovaným znakem.
type: docs
url: /cs/com.aspose.slides/imathdelimiter/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Specifikuje objekt oddělovače, který se skládá z otevíracích a uzavíracích znaků (například závorky, složené závorky, hranaté závorky a svislé čáry) a jeden nebo více matematických prvků uvnitř, oddělených určeným znakem. Příklady: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## Metody

| Metoda | Popis |
| --- | --- |
| [getArguments()](#getArguments--) | Jeden nebo více matematických prvků oddělených znakem oddělovače |
| [getBeginningCharacter()](#getBeginningCharacter--) | Znak začátku oddělovače určuje počáteční, tedy otevírací, znak oddělovače. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Znak začátku oddělovače určuje počáteční, tedy otevírací, znak oddělovače. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Znak oddělovače určuje znak, který odděluje argumenty v objektu oddělovače. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Znak oddělovače určuje znak, který odděluje argumenty v objektu oddělovače. |
| [getEndingCharacter()](#getEndingCharacter--) | Znak konce oddělovače určuje koncový, tedy uzavírací, znak oddělovače. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Znak konce oddělovače určuje koncový, tedy uzavírací, znak oddělovače. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Určuje růst znaků BeginningCharacter, SeparatorCharacter, EndingCharacter. Když je true, oddělovače rostou svisle tak, aby odpovídaly výšce operandu. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Určuje růst znaků BeginningCharacter, SeparatorCharacter, EndingCharacter. Když je true, oddělovače rostou svisle tak, aby odpovídaly výšce operandu. |
| [getDelimiterShape()](#getDelimiterShape--) | Určuje tvar oddělovačů v objektu oddělovače. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Určuje tvar oddělovačů v objektu oddělovače. |
| [delimit(char separatorCharacter)](#delimit-char-) | Odděluje argumenty pomocí určeného znaku oddělovače |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Jeden nebo více matematických prvků oddělených znakem oddělovače

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
public abstract char getBeginningCharacter()
```

Znak začátku oddělovače určuje počáteční, tedy otevírací, znak oddělovače. Matematické oddělovače jsou uzavírací znaky, jako jsou závorky, hranaté závorky a složené závorky. Výchozí hodnota: '('.

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
public abstract void setBeginningCharacter(char value)
```

Znak začátku oddělovače určuje počáteční, tedy otevírací, znak oddělovače. Matematické oddělovače jsou uzavírací znaky, jako jsou závorky, hranaté závorky a složené závorky. Výchozí hodnota: '('.

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
public abstract char getSeparatorCharacter()
```

Znak oddělovače určuje znak, který odděluje argumenty v objektu oddělovače. Výchozí: '|'.

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
public abstract void setSeparatorCharacter(char value)
```

Znak oddělovače určuje znak, který odděluje argumenty v objektu oddělovače. Výchozí: '|'.

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
public abstract char getEndingCharacter()
```

Znak konce oddělovače určuje koncový, tedy uzavírací, znak oddělovače. Matematické oddělovače jsou uzavírací znaky, jako jsou závorky, hranaté závorky a složené závorky. Výchozí hodnota: ')'.

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
public abstract void setEndingCharacter(char value)
```

Znak konce oddělovače určuje koncový, tedy uzavírací, znak oddělovače. Matematické oddělovače jsou uzavírací znaky, jako jsou závorky, hranaté závorky a složené závorky. Výchozí hodnota: ')'.

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
public abstract boolean getGrowToMatchOperandHeight()
```

Určuje růst znaků BeginningCharacter, SeparatorCharacter, EndingCharacter. Když je true, oddělovače rostou svisle tak, aby odpovídaly výšce operandu. Výchozí hodnota je true

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
public abstract void setGrowToMatchOperandHeight(boolean value)
```

Určuje růst znaků BeginningCharacter, SeparatorCharacter, EndingCharacter. Když je true, oddělovače rostou svisle tak, aby odpovídaly výšce operandu. Výchozí hodnota je true

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
public abstract int getDelimiterShape()
```

Určuje tvar oddělovačů v objektu oddělovače. Když je MathDelimiterShape.Centered, jsou oddělovače vycentrovány kolem matematické osy matematického textu a přesto jsou přizpůsobeny tak, aby odpovídaly celé výšce jejich obsahu. Když je MathDelimiterShape.Match, jejich výška a tvar jsou změněny tak, aby přesně odpovídaly jejich obsahu.

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
public abstract void setDelimiterShape(int value)
```

Určuje tvar oddělovačů v objektu oddělovače. Když je MathDelimiterShape.Centered, jsou oddělovače vycentrovány kolem matematické osy matematického textu a přesto jsou přizpůsobeny tak, aby odpovídaly celé výšce jejich obsahu. Když je MathDelimiterShape.Match, jejich výška a tvar jsou změněny tak, aby přesně odpovídaly jejich obsahu.

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
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Odděluje argumenty pomocí určeného znaku oddělovače

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| separatorCharacter | char | znak oddělovače |

**Vrací:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Tento objekt po aplikaci znaku oddělovače