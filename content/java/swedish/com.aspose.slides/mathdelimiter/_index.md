---
title: MathDelimiter
second_title: Aspose.Slides för Java API-referens
description: Specificerar delimiterobjektet bestående av öppnings- och stängningstecken såsom parenteser, klammerparenteser, hakparenteser och vertikala streck samt ett eller flera matematiska element inuti, separerade av ett specificerat tecken.
type: docs
url: /sv/com.aspose.slides/mathdelimiter/
---
**Arv:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Anger delimiterobjektet, bestående av öppnings- och stängningskaraktärer (såsom parenteser, klammer, hakparenteser och vertikala streck), och ett eller flera matematiska element inuti, separerade av ett specificerat tecken. Exempel: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Initierar MathDelimiter med det specificerade elementet som enda basargument |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getArguments()](#getArguments--) | Ett eller flera matematiska element separerade av delimitertecken |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character specificerar början, eller öppnings-, delimitertecknet. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character specificerar början, eller öppnings-, delimitertecknet. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character specificerar tecknet som separerar argument i delimiterobjektet. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character specificerar tecknet som separerar argument i delimiterobjektet. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character specificerar slutet, eller stängnings-, delimitertecknet. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character specificerar slutet, eller stängnings-, delimitertecknet. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Specificerar tillväxten för BeginningCharacter, SeparatorCharacter, EndingCharacter. När true växer delimitrarna vertikalt för att matcha operandens höjd. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Specificerar tillväxten för BeginningCharacter, SeparatorCharacter, EndingCharacter. När true växer delimitrarna vertikalt för att matcha operandens höjd. |
| [getDelimiterShape()](#getDelimiterShape--) | Specificerar formen på delimitrar i delimiterobjektet. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Specificerar formen på delimitrar i delimiterobjektet. |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimitarar argument med det specificerade delimitertecknet |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Omsluter ett math-element i specificerade tecken såsom parenteser eller andra tecken som ram |
| [getChildren()](#getChildren--) | Hämtar underordnade element |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

Initierar MathDelimiter med det specificerade elementet som enda basargument

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Bas-elementet som delimitern appliceras på. Kan vara null. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Ett eller flera matematiska element separerade av delimitertecken

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
public final char getBeginningCharacter()
```

Delimiter Beginning Character specificerar början, eller öppnings-, delimitertecknet. Matematiska delimitrar är inneslutande tecken såsom parenteser, hakparenteser och klammer. Standardvärdet: '('.

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
public final void setBeginningCharacter(char value)
```

Delimiter Beginning Character specificerar början, eller öppnings-, delimitertecknet. Matematiska delimitrar är inneslutande tecken såsom parenteser, hakparenteser och klammer. Standardvärdet: '('.

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
public final char getSeparatorCharacter()
```

Delimiter Separator Character specificerar tecknet som separerar argument i delimiterobjektet. Standardvärdet: '|'.

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
public final void setSeparatorCharacter(char value)
```

Delimiter Separator Character specificerar tecknet som separerar argument i delimiterobjektet. Standardvärdet: '|'.

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
public final char getEndingCharacter()
```

Delimiter Ending Character specificerar slutet, eller stängnings-, delimitertecknet. Matematiska delimitrar är inneslutande tecken såsom parenteser, hakparenteser och klammer. Standardvärdet: ')'.

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
public final void setEndingCharacter(char value)
```

Delimiter Ending Character specificerar slutet, eller stängnings-, delimitertecknet. Matematiska delimitrar är inneslutande tecken såsom parenteser, hakparenteser och klammer. Standardvärdet: ')'.

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
public final boolean getGrowToMatchOperandHeight()
```

Specificerar tillväxten för BeginningCharacter, SeparatorCharacter, EndingCharacter. När true växer delimitrarna vertikalt för att matcha operandens höjd. Standardvärdet är true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Returnerar:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

Specificerar tillväxten för BeginningCharacter, SeparatorCharacter, EndingCharacter. När true växer delimitrarna vertikalt för att matcha operandens höjd. Standardvärdet är true

--------------------

> ```
> Example:
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
public final int getDelimiterShape()
```

Specificerar formen på delimitrar i delimiterobjektet. När MathDelimiterShape.Centered är delimitrarna centrerade kring den matematiska axeln i den matematiska texten och anpassas för att passa hela höjden på deras innehåll. När MathDelimiterShape.Match är deras höjd och form ändrad för att exakt matcha deras innehåll.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Returnerar:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```

Specificerar formen på delimitrar i delimiterobjektet. När MathDelimiterShape.Centered är delimitrarna centrerade kring den matematiska axeln i den matematiska texten och anpassas för att passa hela höjden på deras innehåll. När MathDelimiterShape.Match är deras höjd och form ändrad för att exakt matcha deras innehåll.

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
public final IMathDelimiter delimit(char separatorCharacter)
```

Delimitarar argument med det specificerade delimitertecknet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separatorCharacter | char | delimitertecken |

**Returnerar:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Detta objekt efter att delimitertecknet har tillämpats
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Omsluter ett math-element i specificerade tecken såsom parenteser eller andra tecken som ram

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| beginningCharacter | char | Inledande tecken (vanligtvis vänster hakparentes) |
| endingCharacter | char | Avslutande tecken (vanligtvis höger hakparentes) |

**Returnerar:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Om beginningCharacter och endingCharacter är null tilldelas motsvarande egenskaper värden endast och inget nytt objekt skapas (returnerar detta instance). Annars returneras ett nytt math-element av typ Delimiter som inkluderar specificerade tecken som ram och detta instance av [MathDelimiter](../../com.aspose.slides/mathdelimiter) inramat inuti.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Hämtar underordnade element

**Returnerar:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**Returnerar:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps