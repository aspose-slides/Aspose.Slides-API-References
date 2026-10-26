---
title: IMathDelimiter
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert het delimiter-object dat bestaat uit openings- en sluitingskarakters zoals haakjes, accolades, vierkante haken en verticale strepen, en één of meer wiskundige elementen daarin, gescheiden door een opgegeven teken.
type: docs
url: /nl/com.aspose.slides/imathdelimiter/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Specificeert het delimiter-object, bestaande uit openings- en sluitingskarakters (zoals haakjes, accolades, vierkante haken en verticale strepen), en één of meer wiskundige elementen erin, gescheiden door een opgegeven teken. Voorbeelden: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## Methoden

| Methode | Omschrijving |
| --- | --- |
| [getArguments()](#getArguments--) | Een of meer wiskundige elementen gescheiden door delimitatortekens |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character specificeert het beginnende, of openingscharacter, van de delimiter. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character specificeert het beginnende, of openingscharacter, van de delimiter. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character specificeert het teken dat argumenten scheidt in het delimiter-object. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character specificeert het teken dat argumenten scheidt in het delimiter-object. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character specificeert het eindende, of sluitingscharacter, van de delimiter. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character specificeert het eindende, of sluitingscharacter, van de delimiter. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeien de delimiters verticaal om de operand-hoogte te evenaren. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeien de delimiters verticaal om de operand-hoogte te evenaren. |
| [getDelimiterShape()](#getDelimiterShape--) | Specificeert de vorm van delimiters in het delimiter-object. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Specificeert de vorm van delimiters in het delimiter-object. |
| [delimit(char separatorCharacter)](#delimit-char-) | Scheidt argumenten met het opgegeven delimitatorteken |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```


Een of meer wiskundige elementen gescheiden door delimitatortekens

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
public abstract char getBeginningCharacter()
```


Delimiter Beginning Character specificeert het beginnende, of openingscharacter, van de delimiter. Wiskundige delimiters zijn omsluitende karakters zoals haakjes, vierkante haken en accolades. De standaardwaarde: '('.

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
public abstract void setBeginningCharacter(char value)
```


Delimiter Beginning Character specificeert het beginnende, of openingscharacter, van de delimiter. Wiskundige delimiters zijn omsluitende karakters zoals haakjes, vierkante haken en accolades. De standaardwaarde: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |
### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```


Delimiter Separator Character specificeert het teken dat argumenten scheidt in het delimiter-object. De standaard: '|'.

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
public abstract void setSeparatorCharacter(char value)
```


Delimiter Separator Character specificeert het teken dat argumenten scheidt in het delimiter-object. De standaard: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |
### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
```


Delimiter Ending Character specificeert het eindende, of sluitingscharacter, van de delimiter. Wiskundige delimiters zijn omsluitende karakters zoals haakjes, vierkante haken en accolades. De standaardwaarde: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Retour:**  
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public abstract void setEndingCharacter(char value)
```


Delimiter Ending Character specificeert het eindende, of sluitingscharacter, van de delimiter. Wiskundige delimiters zijn omsluitende karakters zoals haakjes, vierkante haken en accolades. De standaardwaarde: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |
### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeien de delimiters verticaal om de operand-hoogte te evenaren. De standaardwaarde is true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Retour:**  
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeien de delimiters verticaal om de operand-hoogte te evenaren. De standaardwaarde is true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```


Specificeert de vorm van delimiters in het delimiter-object. Wanneer MathDelimiterShape.Centered, worden delimiters gecentreerd rond de wiskunde-as van de tekst en kunnen ze nog steeds worden aangepast om de volledige hoogte van hun inhoud te passen. Wanneer MathDelimiterShape.Match, wordt hun hoogte en vorm exact aangepast aan hun inhoud.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Retour:**  
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public abstract void setDelimiterShape(int value)
```


Specificeert de vorm van delimiters in het delimiter-object. Wanneer MathDelimiterShape.Centered, worden delimiters gecentreerd rond de wiskunde-as van de tekst en kunnen ze nog steeds worden aangepast om de volledige hoogte van hun inhoud te passen. Wanneer MathDelimiterShape.Match, wordt hun hoogte en vorm exact aangepast aan hun inhoud.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```


Scheidt argumenten met het opgegeven delimitatorteken

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| separatorCharacter | char | delimiter-character |
**Retour:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - dit object na het toepassen van het delimiter-character