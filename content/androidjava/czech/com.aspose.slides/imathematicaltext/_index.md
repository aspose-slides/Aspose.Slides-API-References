---
title: IMathematicalText
second_title: Aspose.Slides pro Android pomocí dokumentace Java API
description: Matematický text
type: docs
url: /cs/com.aspose.slides/imathematicaltext/
---

**Všechny implementované rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

Matematický text

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```
## Metody

| Metoda | Popis |
| --- | --- |
| [getValue()](#getValue--) | Textová hodnota |
| [setValue(String value)](#setValue-java.lang.String-) | Textová hodnota |
| [getFormat()](#getFormat--) | Vlastnosti formátování textu |
### getValue() {#getValue--}
```
public abstract String getValue()
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
public abstract void setValue(String value)
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
public abstract IPortionFormat getFormat()
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