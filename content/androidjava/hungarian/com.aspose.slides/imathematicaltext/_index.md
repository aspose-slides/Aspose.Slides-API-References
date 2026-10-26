---
title: IMathematicalText
second_title: Aspose.Slides Androidhoz Java API hivatkozásként
description: Matematikai szöveg
type: docs
url: /hu/com.aspose.slides/imathematicaltext/
---
**Az összes megvalósított interfész:**
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

| Metódus | Leírás |
| --- | --- |
| [getValue()](#getValue--) | Szöveges érték |
| [setValue(String value)](#setValue-java.lang.String-) | Szöveges érték |
| [getFormat()](#getFormat--) | Szövegformázási tulajdonságok |
### getValue() {#getValue--}
```
public abstract String getValue()
```


Szöveges érték

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


Szöveges érték

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