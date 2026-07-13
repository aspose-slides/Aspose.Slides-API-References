---
title: MathematicalText
second_title: Aspose.Slides dla Androida poprzez odwołanie API Java
description: Tekst matematyczny
type: docs
url: /pl/com.aspose.slides/mathematicaltext/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

Tekst matematyczny

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | Konstruktor domyślny (tworzy wartość String.Empty) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | Tworzy MathText z pojedynczym symbolem |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | Tworzy MathematicalText z tekstu |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Tworzy MathematicalText z tekstu i ustawień formatowania |
## Metody

| Metoda | Opis |
| --- | --- |
| [getValue()](#getValue--) | Wartość tekstowa |
| [setValue(String value)](#setValue-java.lang.String-) | Wartość tekstowa |
| [getFormat()](#getFormat--) | Właściwości formatowania tekstu |
| [getChildren()](#getChildren--) | Pobiera elementy potomne |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```


Konstruktor domyślny (tworzy wartość String.Empty)

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


Tworzy MathText z pojedynczym symbolem

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| mathSymbol | char | pojedynczy symbol |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```


Tworzy MathematicalText z tekstu

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| mathText | java.lang.String | wartość tekstowa |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```


Tworzy MathematicalText z tekstu i ustawień formatowania

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| mathText | java.lang.String | wartość tekstowa |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | ustawienia formatu tekstu |

### getValue() {#getValue--}
```
public final String getValue()
```


Wartość tekstowa

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Zwraca:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


Wartość tekstowa

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```


Właściwości formatowania tekstu

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**Zwraca:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Pobiera elementy potomne

**Zwraca:**
com.aspose.slides.IMathElement[]