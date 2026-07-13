---
title: MathDelimiter
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert het delimiter-object dat bestaat uit openings- en sluitings-tekens, zoals haakjes, accolades, vierkante haken en verticale strepen, en een of meer wiskundige elementen binnen, gescheiden door een opgegeven teken.
type: docs
url: /nl/com.aspose.slides/mathdelimiter/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle Geïmplementeerde Interfaces:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Specificeert het scheidingstekenobject, bestaande uit openings- en sluitingstekens (zoals haakjes, accolades, vierkante haken en verticale strepen), en een of meer wiskundige elementen binnen, gescheiden door een opgegeven teken. Voorbeelden: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Initialiseert MathDelimiter met het opgegeven element als enkel basisargument |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getArguments()](#getArguments--) | Een of meer wiskundige elementen gescheiden door scheidingstekenkarakters |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character specificeert het beginnende, of openings-, scheidingstekenkarakter. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character specificeert het beginnende, of openings-, scheidingstekenkarakter. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character specificeert het teken dat argumenten scheidt in het delimiter object. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character specificeert het teken dat argumenten scheidt in het delimiter object. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character specificeert het eindende, of sluitings-, scheidingstekenkarakter. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character specificeert het eindende, of sluitings-, scheidingstekenkarakter. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeien de delimiters verticaal om de hoogte van hun operand te evenaren. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeien de delimiters verticaal om de hoogte van hun operand te evenaren. |
| [getDelimiterShape()](#getDelimiterShape--) | Specificeert de vorm van delimiters in het delimiter object. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Specificeert de vorm van delimiters in het delimiter object. |
| [delimit(char separatorCharacter)](#delimit-char-) | Scheidt argumenten met het opgegeven delimiter teken |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Omvat een wiskundig element in opgegeven tekens zoals haakjes of andere tekens als omlijsting |
| [getChildren()](#getChildren--) | Haal kindelementen op |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

Initialiseert MathDelimiter met het opgegeven element als enkel basisargument

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Het basiselement waarop het delimiter wordt toegepast. Kan null zijn. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Een of meer wiskundige elementen gescheiden door scheidingstekenkarakters

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Return:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```

Delimiter Beginning Character specificeert het beginnende, of openings-, scheidingstekenkarakter. Wiskundige delimiters zijn omvattende tekens zoals haakjes, vierkante haken en accolades. Standaard: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Return:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```

Delimiter Beginning Character specificeert het beginnende, of openings-, scheidingstekenkarakter. Wiskundige delimiters zijn omvattende tekens zoals haakjes, vierkante haken en accolades. Standaard: '('.

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
public final char getSeparatorCharacter()
```

Delimiter Separator Character specificeert het teken dat argumenten scheidt in het delimiter object. Standaard: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Return:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```

Delimiter Separator Character specificeert het teken dat argumenten scheidt in het delimiter object. Standaard: '|'.

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
public final char getEndingCharacter()
```

Delimiter Ending Character specificeert het eindende, of sluitings-, scheidingstekenkarakter. Wiskundige delimiters zijn omvattende tekens zoals haakjes, vierkante haken en accolades. Standaard: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Return:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```

Delimiter Ending Character specificeert het eindende, of sluitings-, scheidingstekenkarakter. Wiskundige delimiters zijn omvattende tekens zoals haakjes, vierkante haken en accolades. Standaard: ')'.

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
public final boolean getGrowToMatchOperandHeight()
```

Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeien de delimiters verticaal om de hoogte van hun operand te evenaren. Standaardwaarde is true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Return:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeien de delimiters verticaal om de hoogte van hun operand te evenaren. Standaardwaarde is true

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
public final int getDelimiterShape()
```

Specificeert de vorm van delimiters in het delimiter object. Wanneer MathDelimiterShape.Centered, worden delimiters gecentreerd rond de wiskundige as van de wiskundige tekst en passen ze zich aan de volledige hoogte van hun inhoud aan. Wanneer MathDelimiterShape.Match, worden hun hoogte en vorm aangepast om precies op hun inhoud te passen.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Return:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```

Specificeert de vorm van delimiters in het delimiter object. Wanneer MathDelimiterShape.Centered, worden delimiters gecentreerd rond de wiskundige as van de wiskundige tekst en passen ze zich aan de volledige hoogte van hun inhoud aan. Wanneer MathDelimiterShape.Match, worden hun hoogte en vorm aangepast om precies op hun inhoud te passen.

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
public final IMathDelimiter delimit(char separatorCharacter)
```

Scheidt argumenten met het opgegeven delimiter teken

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separatorCharacter | char | delimiter teken |

**Return:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Dit object na het toepassen van het delimiter teken
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Omvat een wiskundig element in opgegeven tekens zoals haakjes of andere tekens als omlijsting

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| beginningCharacter | char | Beginteken (meestal linker haak) |
| endingCharacter | char | Eindteken (meestal rechter haak) |

**Return:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Als beginningCharacter en endingCharacter null zijn, worden bijbehorende eigenschappen alleen toegewezen en wordt geen nieuw object gecreëerd (retourneert deze instance). Anders wordt een nieuw wiskundig element van type Delimiter geretourneerd dat de opgegeven tekens als omlijsting bevat en deze instance van [MathDelimiter](../../com.aspose.slides/mathdelimiter) er omheen.

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Haal kindelementen op

**Return:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**Return:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps