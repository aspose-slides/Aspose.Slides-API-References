---
title: MathDelimiter
second_title: Aspose.Slides för Android via Java API-referens
description: Specificerar delimiter-objektet som består av inledande och avslutande tecken såsom parenteser, klammerparenteser, hakparenteser och vertikala streck samt ett eller flera matematiska element inuti, separerade av ett specificerat tecken.
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

Specificerar delimiter-objektet, bestående av inledande och avslutande tecken (såsom parenteser, klammerparenteser, hakparenteser och vertikala streck), samt ett eller flera matematiska element inuti, separerade av ett specificerat tecken. Exempel: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Exempel:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Initialiserar MathDelimiter med det specificerade elementet som enda grundargument |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getArguments()](#getArguments--) | Ett eller flera matematiska element separerade av delimiter-tecken |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character anger början, eller det inledande, delimiter-tecknet. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character anger början, eller det inledande, delimiter-tecknet. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character anger tecknet som separerar argument i delimiter-objektet. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character anger tecknet som separerar argument i delimiter-objektet. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character anger slutet, eller det avslutande, delimiter-tecknet. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character anger slutet, eller det avslutande, delimiter-tecknet. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Anger tillväxten av BeginningCharacter, SeparatorCharacter, EndingCharacter. När true växer delimitrarna vertikalt för att matcha operandens höjd. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Anger tillväxten av BeginningCharacter, SeparatorCharacter, EndingCharacter. När true växer delimitrarna vertikalt för att matcha operandens höjd. |
| [getDelimiterShape()](#getDelimiterShape--) | Anger formen på delimitrarna i delimiter-objektet. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Anger formen på delimitrarna i delimiter-objektet. |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimiterar argument med det specificerade delimiter-tecknet |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Omsluter ett matematiskt element i specificerade tecken såsom parenteser eller andra tecken som ram |
| [getChildren()](#getChildren--) | Hämtar barn-element |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrollteckensegenskaper |

### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

Initialiserar MathDelimiter med det specificerade elementet som enda grundargument

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

### Parametrar:
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Basiselementet som delimitteringen tillämpas på. Kan vara null. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Ett eller flera matematiska element separerade av delimiter-tecken

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

### Returnerar:
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```

Delimiter Beginning Character anger början, eller det inledande, delimiter-tecknet. Matematiska delimitrar är omslutande tecken såsom parenteser, hakparenteser och klammerparenteser. Standardvärdet: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

### Returnerar:
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```

Delimiter Beginning Character anger början, eller det inledande, delimiter-tecknet. Matematiska delimitrar är omslutande tecken såsom parenteser, hakparenteser och klammerparenteser. Standardvärdet: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

### Parametrar:
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public final char getSeparatorCharacter()
```

Delimiter Separator Character anger tecknet som separerar argument i delimiter-objektet. Standardvärdet: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

### Returnerar:
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```

Delimiter Separator Character anger tecknet som separerar argument i delimiter-objektet. Standardvärdet: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

### Parametrar:
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public final char getEndingCharacter()
```

Delimiter Ending Character anger slutet, eller det avslutande, delimiter-tecknet. Matematiska delimitrar är omslutande tecken såsom parenteser, hakparenteser och klammerparenteser. Standardvärdet: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

### Returnerar:
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```

Delimiter Ending Character anger slutet, eller det avslutande, delimiter-tecknet. Matematiska delimitrar är omslutande tecken såsom parenteser, hakparenteser och klammerparenteser. Standardvärdet: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

### Parametrar:
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

Anger tillväxten av BeginningCharacter, SeparatorCharacter, EndingCharacter. När true växer delimitrarna vertikalt för att matcha operandens höjd. Standardvärdet är true

--------------------

> ```
> Exempel:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

### Returnerar:
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

Anger tillväxten av BeginningCharacter, SeparatorCharacter, EndingCharacter. När true växer delimitrarna vertikalt för att matcha operandens höjd. Standardvärdet är true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

### Parametrar:
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public final int getDelimiterShape()
```

Anger formen på delimitrarna i delimiter-objektet. När värdet är MathDelimiterShape.Centered är delimitrarna centrerade kring den matematiska axeln i den matematiska texten och kan fortfarande anpassas för att passa hela höjden på deras innehåll. När värdet är MathDelimiterShape.Match ändras deras höjd och form för att exakt matcha deras innehåll.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

### Returnerar:
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```

Anger formen på delimitrarna i delimiter-objektet. När värdet är MathDelimiterShape.Centered är delimitrarna centrerade kring den matematiska axeln i den matematiska texten och kan fortfarande anpassas för att passa hela höjden på deras innehåll. När värdet är MathDelimiterShape.Match ändras deras höjd och form för att exakt matcha deras innehåll.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

### Parametrar:
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Delimiterar argument med det specificerade delimiter-tecknet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separatorCharacter | char | delimiter-tecken |

**Returnerar:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Detta objekt efter att delimiter-tecknet har tillämpats
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Omsluter ett matematiskt element i specificerade tecken såsom parenteser eller andra tecken som ram

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

### Parametrar:
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| beginningCharacter | char | Begynnelse-tecken (vanligtvis vänster hakparentes) |
| endingCharacter | char | Slut-tecken (vanligtvis höger hakparentes) |

**Returnerar:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Om beginningCharacter och endingCharacter är null, tilldelas motsvarande egenskaper bara värden och inget nytt objekt skapas (returnerar detta objekt). Annars returneras ett nytt matematiskt element av typen Delimiter som inkluderar specificerade tecken som ram och detta exempel av [MathDelimiter](../../com.aspose.slides/mathdelimiter) ramad inuti.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Hämtar barn-element

**Returnerar:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Kontrollteckensegenskaper

**Returnerar:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps