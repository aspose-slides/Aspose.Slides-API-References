---
title: MathematicalText
second_title: Aspose.Slides för Android via Java API-referens
description: Matematisk text
type: docs
url: /sv/com.aspose.slides/mathematicaltext/
---
**Arv:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

Matematisk text

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | Standardkonstruktor (skapa String.Empty Value) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | Skapa MathText med en enda symbol |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | Skapa MathematicalText från text |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Skapa MathematicalText från text och formatinställningar |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getValue()](#getValue--) | Textvärde |
| [setValue(String value)](#setValue-java.lang.String-) | Textvärde |
| [getFormat()](#getFormat--) | Egenskaper för textformatering |
| [getChildren()](#getChildren--) | Hämta barn-element |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```


Standardkonstruktor (skapa String.Empty Value)

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


Skapa MathText med en enda symbol

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathSymbol | char | en enda symbol |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```


Skapa MathematicalText från text

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathText | java.lang.String | textvärde |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```


Skapa MathematicalText från text och formatinställningar

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathText | java.lang.String | textvärde |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | textformatinställningar |

### getValue() {#getValue--}
```
public final String getValue()
```


Textvärde

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Returnerar:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


Textvärde

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```


Egenskaper för textformatering

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**Returnerar:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Hämta barn-element

**Returnerar:**
com.aspose.slides.IMathElement[]