---
title: IMathematicalText
second_title: Aspose.Slides für Android über die Java API Referenz
description: Mathematischer Text
type: docs
url: /de/com.aspose.slides/imathematicaltext/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

Mathematischer Text

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  ```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getValue()](#getValue--) | Textwert |
| [setValue(String value)](#setValue-java.lang.String-) | Textwert |
| [getFormat()](#getFormat--) | Textformatierungseigenschaften |
### getValue() {#getValue--}
```
public abstract String getValue()
```

Textwert

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
>  ```

**Rückgabe:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public abstract void setValue(String value)
```

Textwert

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
>  ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IPortionFormat getFormat()
```

Textformatierungseigenschaften

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
>  ```

**Rückgabe:**
[IPortionFormat](../../com.aspose.slides/iportionformat)