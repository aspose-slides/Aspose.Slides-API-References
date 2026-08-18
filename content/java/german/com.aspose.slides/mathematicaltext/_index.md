---
title: MathematicalText
second_title: Aspose.Slides für Java API Referenz
description: Mathematischer Text
type: docs
url: /de/com.aspose.slides/mathematicaltext/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

Mathematischer Text

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | Standardkonstruktor (erstellt String.Empty-Wert) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | Erstellt MathText mit einem einzelnen Symbol |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | Erstellt MathematicalText aus Text |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Erstellt MathematicalText aus Text und Formatierungseinstellungen |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getValue()](#getValue--) | Textwert |
| [setValue(String value)](#setValue-java.lang.String-) | Textwert |
| [getFormat()](#getFormat--) | Eigenschaften der Textformatierung |
| [getChildren()](#getChildren--) | Kinder-Elemente abrufen |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```


Standardkonstruktor (erstellt String.Empty-Wert)

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


Erstellt MathText mit einem einzelnen Symbol

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathSymbol | char | einzelnes Symbol |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```


Erstellt MathematicalText aus Text

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathText | java.lang.String | Textwert |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```


Erstellt MathematicalText aus Text und Formatierungseinstellungen

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathText | java.lang.String | Textwert |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | Textformatierungseinstellungen |

### getValue() {#getValue--}
```
public final String getValue()
```


Textwert

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Rückgabewert:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


Textwert

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```


Eigenschaften der Textformatierung

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**Rückgabewert:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Kinder-Elemente abrufen

**Rückgabewert:**
com.aspose.slides.IMathElement[]