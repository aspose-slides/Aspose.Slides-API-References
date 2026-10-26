---
title: MathematicalText
second_title: Aspose.Slides Java API referencia
description: Matematikai szöveg
type: docs
url: /hu/com.aspose.slides/mathematicaltext/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Minden megvalósított interfész:**
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
| [MathematicalText()](#MathematicalText--) | Alapértelmezett konstruktor (String.Empty érték létrehozása) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | MathText létrehozása egyetlen szimbólummal |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | MathematicalText létrehozása szövegből |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | MathematicalText létrehozása szövegből és formátumbeállításokkal |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getValue()](#getValue--) | Szöveg értéke |
| [setValue(String value)](#setValue-java.lang.String-) | Szöveg értéke |
| [getFormat()](#getFormat--) | Szövegformázási tulajdonságok |
| [getChildren()](#getChildren--) | Gyermekelemek lekérése |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```

Alapértelmezett konstruktor (String.Empty érték létrehozása)

--------------------

> ```
> Példa:
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
| mathText | java.lang.String | szöveg értéke |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```

MathematicalText létrehozása szövegből és formátumbeállításokkal

--------------------

> ```
> Példa:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathText | java.lang.String | szöveg értéke |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | szövegformátum beállítások |

### getValue() {#getValue--}
```
public final String getValue()
```

Szöveg értéke

--------------------

> ```
> Példa:
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

Szöveg értéke

--------------------

> ```
> Példa:
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
> Példa:
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