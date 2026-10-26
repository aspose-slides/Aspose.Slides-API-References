---
title: IMathematicalText
second_title: Aspose.Slides जावा के लिए API संदर्भ
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

| विधि | विवरण |
| --- | --- |
| [getValue()](#getValue--) | टेक्स्ट मान |
| [setValue(String value)](#setValue-java.lang.String-) | टेक्स्ट मान |
| [getFormat()](#getFormat--) | टेक्स्ट फ़ॉर्मेटिंग गुण |
### getValue() {#getValue--}
```
public abstract String getValue()
```


टेक्स्ट मान

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


टेक्स्ट मान

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IPortionFormat getFormat()
```


टेक्स्ट फ़ॉर्मेटिंग गुण

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**वापसी:**
[IPortionFormat](../../com.aspose.slides/iportionformat)