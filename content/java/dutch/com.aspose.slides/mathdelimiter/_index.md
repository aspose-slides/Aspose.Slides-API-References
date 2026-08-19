---
title: MathDelimiter
second_title: Aspose.Slides voor Java API Referentie
description: Specificeert het scheidingstekenobject dat bestaat uit openings- en sluitingstekens zoals haakjes, accolades, vierkante haken en verticale strepen, en één of meer wiskundige elementen daarin, gescheiden door een opgegeven teken.
type: docs
url: /nl/com.aspose.slides/mathdelimiter/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Specificeert het scheidingstekenobject, bestaande uit openings- en sluitingstekens (zoals haakjes, accolades, vierkante haken en verticale strepen), en een of meer wiskundige elementen daarin, gescheiden door een opgegeven teken. Voorbeelden: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

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
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getArguments()](#getArguments--) | Een of meer wiskundige elementen gescheiden door scheidingsteken-tekens |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character specificeert het begin- of openings-scheidingsteken. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character specificeert het begin- of openings-scheidingsteken. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character specificeert het teken dat argumenten scheidt in het scheidingstekenobject. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character specificeert het teken dat argumenten scheidt in het scheidingstekenobject. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character specificeert het eind- of sluitings-scheidingsteken. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character specificeert het eind- of sluitings-scheidingsteken. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeien de scheidingstekens verticaal om hun operandhoogte te evenaren. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeien de scheidingstekens verticaal om hun operandhoogte te evenaren. |
| [getDelimiterShape()](#getDelimiterShape--) | Specificeert de vorm van scheidingstekens in het scheidingstekenobject. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Specificeert de vorm van scheidingstekens in het scheidingstekenobject. |
| [delimit(char separatorCharacter)](#delimit-char-) | Scheidt argumenten met behulp van het opgegeven scheidingsteken. |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Omvat een wiskundig element in opgegeven tekens zoals haakjes of andere tekens als kader. |
| [getChildren()](#getChildren--) | Haalt kindelementen op. |
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
| element | [IMathElement](../../com.aspose.slides/imathelement) | Het basiselement waarop het scheidingsteken wordt toegepast. Kan null zijn. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Een of meer wiskundige elementen gescheiden door scheidingsteken-tekens

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Retour:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```

Delimiter Beginning Character specificeert het begin- of openings-scheidingsteken. Wiskundige scheidingstekens zijn omvattende tekens zoals haakjes, vierkante haken en accolades. Standaard: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Retour:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```

Delimiter Beginning Character specificeert het begin- of openings-scheidingsteken. Wiskundige scheidingstekens zijn omvattende tekens zoals haakjes, vierkante haken en accolades. Standaard: '('.

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

Delimiter Separator Character specificeert het teken dat argumenten scheidt in het scheidingstekenobject. Standaard: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Retour:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```

Delimiter Separator Character specificeert het teken dat argumenten scheidt in het scheidingstekenobject. Standaard: '|'.

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

Delimiter Ending Character specificeert het eind- of sluitings-scheidingsteken. Wiskundige scheidingstekens zijn omvattende tekens zoals haakjes, vierkante haken en accolades. Standaard: ')'.

--------------------

> ```
> Voorbeeld:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Retour:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```

Delimiter Ending Character specificeert het eind- of sluitings-scheidingsteken. Wiskundige scheidingstekens zijn omvattende tekens zoals haakjes, vierkante haken en accolades. Standaard: ')'.

--------------------

> ```
> Voorbeeld:
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

Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeien de scheidingstekens verticaal om hun operandhoogte te evenaren. Standaardwaarde is true

--------------------

> ```
> Voorbeeld:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Retour:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeien de scheidingstekens verticaal om hun operandhoogte te evenaren. Standaardwaarde is true

--------------------

> ```
> Voorbeeld:
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

Specificeert de vorm van scheidingstekens in het scheidingstekenobject. Wanneer MathDelimiterShape.Centered, worden de scheidingstekens gecentreerd rond de wiskunde-as van de wiskundige tekst en passen ze zich aan om de volledige hoogte van hun inhoud te vullen. Wanneer MathDelimiterShape.Match, worden hun hoogte en vorm aangepast om precies overeen te komen met hun inhoud.

--------------------

> ```
> Voorbeeld:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Retour:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```

Specificeert de vorm van scheidingstekens in het scheidingstekenobject. Wanneer MathDelimiterShape.Centered, worden de scheidingstekens gecentreerd rond de wiskunde-as van de wiskundige tekst en passen ze zich aan om de volledige hoogte van hun inhoud te vullen. Wanneer MathDelimiterShape.Match, worden hun hoogte en vorm aangepast om precies overeen te komen met hun inhoud.

--------------------

> ```
> Voorbeeld:
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

Scheidt argumenten met behulp van het opgegeven scheidingsteken

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separatorCharacter | char | scheidingsteken-karakter |

**Retour:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - dit object na het toepassen van het scheidingsteken
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Omvat een wiskundig element in opgegeven tekens zoals haakjes of andere tekens als kader

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

**Retour:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Als beginningCharacter en endingCharacter null zijn, krijgen de overeenkomstige eigenschappen alleen waarden toe en wordt er geen nieuw object gemaakt (dit exemplaar wordt geretourneerd). Anders wordt een nieuw wiskundig element van het type Delimiter geretourneerd dat de opgegeven tekens als kader bevat en dit exemplaar van [MathDelimiter](../../com.aspose.slides/mathdelimiter) er binnen ingesloten.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Haalt kindelementen op

**Retour:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**Retour:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps