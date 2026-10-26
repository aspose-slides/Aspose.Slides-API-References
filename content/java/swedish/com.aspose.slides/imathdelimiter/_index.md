---
title: IMathDelimiter
second_title: Aspose.Slides för Java API-referens
description: Specificerar delimiter-objektet bestående av öppnings- och avslutnings tecken såsom parenteser, klammerparenteser, hakparenteser och vertikala staplar samt ett eller flera matematiska element inuti som separeras av ett specificerat tecken.
type: docs
url: /sv/com.aspose.slides/imathdelimiter/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Specificerar delimiter-objektet, bestående av inledande och avslutande tecken (såsom parenteser, klammerparenteser, hakparenteser och vertikala staplar), samt ett eller flera matematiska element inuti, separerade av ett specificerat tecken. Exempel: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getArguments()](#getArguments--) | Ett eller flera matematiska element separerade av delimiter-tecken |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character specificerar början, eller öppning, delimiter-tecknet. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character specificerar början, eller öppning, delimiter-tecknet. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character specificerar tecknet som separerar argument i delimiter-objektet. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character specificerar tecknet som separerar argument i delimiter-objektet. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character specificerar slutet, eller stängning, delimiter-tecknet. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character specificerar slutet, eller stängning, delimiter-tecknet. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Specificerar tillväxten för BeginningCharacter, SeparatorCharacter, EndingCharacter. När true växer delimitrarna vertikalt för att matcha operandens höjd. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Specificerar tillväxten för BeginningCharacter, SeparatorCharacter, EndingCharacter. När true växer delimitrarna vertikalt för att matcha operandens höjd. |
| [getDelimiterShape()](#getDelimiterShape--) | Specificerar formen på delimitrar i delimiter-objektet. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Specificerar formen på delimitrar i delimiter-objektet. |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimiterar argument med det angivna delimiter-tecknet |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Ett eller flera matematiska element separerade av delimiter-tecken

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Returnerar:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public abstract char getBeginningCharacter()
```

Delimiter Beginning Character specificerar början, eller öppning, delimiter-tecknet. Matematiska delimitrar är inneslutande tecken såsom parenteser, hakparenteser och klammerparenteser. Standardvärdet: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Returnerar:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public abstract void setBeginningCharacter(char value)
```

Delimiter Beginning Character specificerar början, eller öppning, delimiter-tecknet. Matematiska delimitrar är inneslutande tecken såsom parenteser, hakparenteser och klammerparenteser. Standardvärdet: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```

Delimiter Separator Character specificerar tecknet som separerar argument i delimiter-objektet. Standard: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Returnerar:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public abstract void setSeparatorCharacter(char value)
```

Delimiter Separator Character specificerar tecknet som separerar argument i delimiter-objektet. Standard: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
```

Delimiter Ending Character specificerar slutet, eller stängning, delimiter-tecknet. Matematiska delimitrar är inneslutande tecken såsom parenteser, hakparenteser och klammerparenteser. Standardvärdet: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Returnerar:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public abstract void setEndingCharacter(char value)
```

Delimiter Ending Character specificerar slutet, eller stängning, delimiter-tecknet. Matematiska delimitrar är inneslutande tecken såsom parenteser, hakparenteser och klammerparenteser. Standardvärdet: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

Specificerar tillväxten för BeginningCharacter, SeparatorCharacter, EndingCharacter. När true växer delimitrarna vertikalt för att matcha operandens höjd. Standardvärdet är true

--------------------

> ```
> Exempel:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```


**Returnerar:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

Specificerar tillväxten för BeginningCharacter, SeparatorCharacter, EndingCharacter. När true växer delimitrarna vertikalt för att matcha operandens höjd. Standardvärdet är true

--------------------

> ```
> Exempel:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```

Specificerar formen på delimitrar i delimiter-objektet. När MathDelimiterShape.Centered är delimitrarna centrerade kring den matematiska axeln i den matematiska texten och kan fortfarande anpassas för att passa hela höjden på deras innehåll. När MathDelimiterShape.Match är deras höjd och form ändrade så att de exakt matchar deras innehåll.

--------------------

> ```
> Exempel:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Returnerar:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public abstract void setDelimiterShape(int value)
```

Specificerar formen på delimitrar i delimiter-objektet. När MathDelimiterShape.Centered är delimitrarna centrerade kring den matematiska axeln i den matematiska texten och kan fortfarande anpassas för att passa hela höjden på deras innehåll. När MathDelimiterShape.Match är deras höjd och form ändrade så att de exakt matchar deras innehåll.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Delimiterar argument med det angivna delimiter-tecknet

--------------------

> ```
> Exempel:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separatorCharacter | char | delimiter-tecken |

**Returnerar:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Detta objekt efter att ha applicerat delimiter-tecknet