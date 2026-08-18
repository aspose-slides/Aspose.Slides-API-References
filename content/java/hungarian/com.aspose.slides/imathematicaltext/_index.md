---
title: IMathematicalText
second_title: Aspose.Slides a Java API referencia
description: Matematikai szöveg
type: docs
url: /hu/com.aspose.slides/imathematicaltext/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

Matematikai szöveg

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getValue()](#getValue--) | Szövegérték |
| [setValue(String value)](#setValue-java.lang.String-) | Szövegérték |
| [getFormat()](#getFormat--) | Szövegformázási tulajdonságok |
### getValue() {#getValue--}
```
public abstract String getValue()
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
public abstract void setValue(String value)
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
public abstract IPortionFormat getFormat()
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