---
title: MathematicalText
second_title: Aspose.Slides voor Java API-referentie
description: Wiskundige tekst
type: docs
url: /nl/com.aspose.slides/mathematicaltext/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

Wiskundige tekst

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | Standaardconstructor (maak String.Empty-waarde) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | Maak MathText met één symbool |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | Maak MathematicalText van tekst |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Maak MathematicalText van tekst en opmaakinstellingen |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getValue()](#getValue--) | Tekstwaarde |
| [setValue(String value)](#setValue-java.lang.String-) | Tekstwaarde |
| [getFormat()](#getFormat--) | Tekstopmaak-eigenschappen |
| [getChildren()](#getChildren--) | Kinderelementen ophalen |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```


Standaardconstructor (maak String.Empty-waarde)

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText();
> ```

### MathematicalText(char mathSymbol) {#MathematicalText-char-}
```
public MathematicalText(char mathSymbol)
```


Maak MathText met één symbool

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathSymbol | char | enkel symbool |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```


Maak MathematicalText van tekst

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathText | java.lang.String | tekstwaarde |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```


Maak MathematicalText van tekst en opmaakinstellingen

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathText | java.lang.String | tekstwaarde |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | tekstopmaakinstellingen |

### getValue() {#getValue--}
```
public final String getValue()
```


Tekstwaarde

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Retourwaarde:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


Tekstwaarde

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```


Tekstopmaak-eigenschappen

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**Retourwaarde:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Kinderelementen ophalen

**Retourwaarde:**
com.aspose.slides.IMathElement[]