---
title: IMathematicalText
second_title: Aspose.Slides dla Androida - odwołanie API Java
description: Tekst matematyczny
type: docs
url: /pl/com.aspose.slides/imathematicaltext/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

Tekst matematyczny

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```

## Metody

| Metoda | Opis |
| --- | --- |
| [getValue()](#getValue--) | Wartość tekstowa |
| [setValue(String value)](#setValue-java.lang.String-) | Wartość tekstowa |
| [getFormat()](#getFormat--) | Właściwości formatowania tekstu |
### getValue() {#getValue--}
```
public abstract String getValue()
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
public abstract void setValue(String value)
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
public abstract IPortionFormat getFormat()
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