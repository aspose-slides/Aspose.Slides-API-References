---
title: MathematicalText
second_title: Aspose.Slides Androidra a Java API referenciája
description: Matematikai szöveg
type: docs
url: /hu/com.aspose.slides/mathematicaltext/
---
**Öröklődés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Minden Megvalósított Interfész:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

Matematikai szöveg

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | Alapértelmezett konstruktor (létrehozza a String.Empty értéket) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | MathText létrehozása egyetlen szimbólummal |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | MathematicalText létrehozása szövegből |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | MathematicalText létrehozása szövegből és formázási beállításokkal |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getValue()](#getValue--) | Szövegérték |
| [setValue(String value)](#setValue-java.lang.String-) | Szövegérték |
| [getFormat()](#getFormat--) | Szövegformázási tulajdonságok |
| [getChildren()](#getChildren--) | Gyermekelemek lekérése |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```


Alapértelmezett konstruktor (létrehozza a String.Empty értéket)

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


MathText létrehozása egyetlen szimbólummal

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathSymbol | char | egyetlen szimbólum |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```


MathematicalText létrehozása szövegből

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathText | java.lang.String | szövegérték |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```


MathematicalText létrehozása szövegből és formázási beállításokkal

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathText | java.lang.String | szövegérték |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | szövegformázási beállítások |

### getValue() {#getValue--}
```
public final String getValue()
```


Szövegérték

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Visszatérési érték:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


Szövegérték

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```


Szövegformázási tulajdonságok

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**Visszatérési érték:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Gyermekelemek lekérése

**Visszatérési érték:**
com.aspose.slides.IMathElement[]