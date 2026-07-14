---
title: IMathematicalText
second_title: Aspose.Slides for Android के माध्यम से Java API रेफ़रेंस
description: गणितीय पाठ
type: docs
url: /hi/com.aspose.slides/imathematicaltext/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

गणितीय पाठ

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getValue()](#getValue--) | पाठ मान |
| [setValue(String value)](#setValue-java.lang.String-) | पाठ मान |
| [getFormat()](#getFormat--) | पाठ स्वरूपण गुण |
### getValue() {#getValue--}
```
public abstract String getValue()
```

पाठ मान

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**वापसी:**  
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public abstract void setValue(String value)
```

पाठ मान

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IPortionFormat getFormat()
```

पाठ स्वरूपण गुण

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**वापसी:**  
[IPortionFormat](../../com.aspose.slides/iportionformat)