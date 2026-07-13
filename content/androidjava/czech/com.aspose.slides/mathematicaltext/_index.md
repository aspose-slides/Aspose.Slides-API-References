---
title: MathematicalText
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Matematický text
type: docs
url: /cs/com.aspose.slides/mathematicaltext/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

Matematický text

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | Výchozí konstruktor (vytvoří prázdnou hodnotu String.Empty) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | Vytvoří MathText s jedním symbolem |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | Vytvoří MathematicalText z textu |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Vytvoří MathematicalText z textu a nastavení formátu |
## Metody

| Metoda | Popis |
| --- | --- |
| [getValue()](#getValue--) | Textová hodnota |
| [setValue(String value)](#setValue-java.lang.String-) | Textová hodnota |
| [getFormat()](#getFormat--) | Vlastnosti formátování textu |
| [getChildren()](#getChildren--) | Získá podřízené prvky |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```


Výchozí konstruktor (vytvoří prázdnou hodnotu String.Empty)

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


Vytvoří MathText s jedním symbolem

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| mathSymbol | char | jeden symbol |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```


Vytvoří MathematicalText z textu

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| mathText | java.lang.String | textová hodnota |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```


Vytvoří MathematicalText z textu a nastavení formátu

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| mathText | java.lang.String | textová hodnota |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | nastavení formátu textu |

### getValue() {#getValue--}
```
public final String getValue()
```


Textová hodnota

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Vrací:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


Textová hodnota

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```


Vlastnosti formátování textu

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```


**Vrací:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Získá podřízené prvky

**Vrací:**
com.aspose.slides.IMathElement[]