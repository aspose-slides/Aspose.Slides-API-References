---
title: IMathDelimiter
second_title: Aspose.Slides voor Java API-referentie
description: Specificeert het delimiter-object dat bestaat uit openings- en sluittekens zoals haakjes, accolades, vierkante haken en verticale strepen, en één of meer wiskundige elementen erin die gescheiden worden door een opgegeven teken.
type: docs
url: /nl/com.aspose.slides/imathdelimiter/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Specificeert het delimiter-object, bestaande uit opening- en sluittekens (zoals haakjes, accolades, vierkante haken en verticale strepen), en een of meer wiskundige elementen erin, gescheiden door een opgegeven teken. Voorbeelden: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getArguments()](#getArguments--) | Een of meer wiskundige elementen gescheiden door delimitertekens |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character geeft het beginnende, of openings-, delimiterteken aan. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character geeft het beginnende, of openings-, delimiterteken aan. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character geeft het teken aan dat argumenten scheidt in het delimiter-object. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character geeft het teken aan dat argumenten scheidt in het delimiter-object. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character geeft het eindende, of sluit-, delimiterteken aan. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character geeft het eindende, of sluit-, delimiterteken aan. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeien de delimiters verticaal om de hoogte van hun operand te evenaren. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeien de delimiters verticaal om de hoogte van hun operand te evenaren. |
| [getDelimiterShape()](#getDelimiterShape--) | Specificeert de vorm van delimiters in het delimiter-object. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Specificeert de vorm van delimiters in het delimiter-object. |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimiteert argumenten met het opgegeven delimiterteken |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Een of meer wiskundige elementen gescheiden door delimitertekens

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Retourneert:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public abstract char getBeginningCharacter()
```

Delimiter Beginning Character geeft het beginnende, of openings-, delimiterteken aan. Wiskundige delimiters zijn omsluitende tekens zoals haakjes, vierkante haken en accolades. De standaardwaarde: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Retourneert:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public abstract void setBeginningCharacter(char value)
```

Delimiter Beginning Character geeft het beginnende, of openings-, delimiterteken aan. Wiskundige delimiters zijn omsluitende tekens zoals haakjes, vierkante haken en accolades. De standaardwaarde: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```

Delimiter Separator Character geeft het teken aan dat argumenten scheidt in het delimiter-object. De standaard: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Retourneert:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public abstract void setSeparatorCharacter(char value)
```

Delimiter Separator Character geeft het teken aan dat argumenten scheidt in het delimiter-object. De standaard: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
```

Delimiter Ending Character geeft het eindende, of sluit-, delimiterteken aan. Wiskundige delimiters zijn omsluitende tekens zoals haakjes, vierkante haken en accolades. De standaardwaarde: ')'.

--------------------

> ```
> Voorbeeld:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Retourneert:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public abstract void setEndingCharacter(char value)
```

Delimiter Ending Character geeft het eindende, of sluit-, delimiterteken aan. Wiskundige delimiters zijn omsluitende tekens zoals haakjes, vierkante haken en accolades. De standaardwaarde: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeien de delimiters verticaal om de hoogte van hun operand te evenaren. De standaardwaarde is true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Retourneert:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeien de delimiters verticaal om de hoogte van hun operand te evenaren. De standaardwaarde is true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```

Specificeert de vorm van delimiters in het delimiter-object. Wanneer MathDelimiterShape.Centered, worden delimiters gecentreerd rond de wiskunde-as van de wiskundige tekst en kunnen ze nog steeds worden aangepast om de volledige hoogte van hun inhoud te passen. Wanneer MathDelimiterShape.Match, worden hun hoogte en vorm aangepast om precies hun inhoud te evenaren.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Retourneert:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public abstract void setDelimiterShape(int value)
```

Specificeert de vorm van delimiters in het delimiter-object. Wanneer MathDelimiterShape.Centered, worden delimiters gecentreerd rond de wiskunde-as van de wiskundige tekst en kunnen ze nog steeds worden aangepast om de volledige hoogte van hun inhoud te passen. Wanneer MathDelimiterShape.Match, worden hun hoogte en vorm aangepast om precies hun inhoud te evenaren.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Delimiteert argumenten met het opgegeven delimiterteken

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separatorCharacter | char | delimiterteken |

**Retourneert:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Dit object na het toepassen van het delimiterteken