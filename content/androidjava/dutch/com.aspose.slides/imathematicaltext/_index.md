---
title: IMathematicalText
second_title: Aspose.Slides voor Android via Java API-referentie
description: Wiskundige tekst
type: docs
url: /nl/com.aspose.slides/imathematicaltext/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

Wiskundige tekst

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getValue()](#getValue--) | Tekstwaarde |
| [setValue(String value)](#setValue-java.lang.String-) | Tekstwaarde |
| [getFormat()](#getFormat--) | Tekstopmaak eigenschappen |
### getValue() {#getValue--}
```
public abstract String getValue()
```

Tekstwaarde

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Retourwaarde:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public abstract void setValue(String value)
```

Tekstwaarde

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IPortionFormat getFormat()
```

Tekstopmaak eigenschappen

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**Retourwaarde:**
[IPortionFormat](../../com.aspose.slides/iportionformat)