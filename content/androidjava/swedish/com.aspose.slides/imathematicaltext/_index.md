---
title: IMathematicalText
second_title: Aspose.Slides för Android via Java API-referens
description: Matematisk text
type: docs
url: /sv/com.aspose.slides/imathematicaltext/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

Matematisk text

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getValue()](#getValue--) | Textvärde |
| [setValue(String value)](#setValue-java.lang.String-) | Textvärde |
| [getFormat()](#getFormat--) | Egenskaper för textformatering |
### getValue() {#getValue--}
```
public abstract String getValue()
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
public abstract void setValue(String value)
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
public abstract IPortionFormat getFormat()
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