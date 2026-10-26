---
title: MathematicalText
second_title: Java के लिए Aspose.Slides API संदर्भ
description: गणितीय पाठ
type: docs
url: /hi/com.aspose.slides/mathematicaltext/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

गणितीय पाठ

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## कंस्ट्रक्टर

| निर्माता | विवरण |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | Default constructor (create String.Empty Value) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | Create MathText with single symbol |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | Create MathematicalText from text |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Create MathematicalText from text and format settings |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getValue()](#getValue--) | Text value |
| [setValue(String value)](#setValue-java.lang.String-) | Text value |
| [getFormat()](#getFormat--) | Text formatting properties |
| [getChildren()](#getChildren--) | Get children elements |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```


Default constructor (create String.Empty Value)

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


Create MathText with single symbol

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mathSymbol | char | single symbol |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```


Create MathematicalText from text

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mathText | java.lang.String | text value |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```


Create MathematicalText from text and format settings

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mathText | java.lang.String | text value |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | text format settings |

### getValue() {#getValue--}
```
public final String getValue()
```


Text value

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
public final void setValue(String value)
```


Text value

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
public final IPortionFormat getFormat()
```


Text formatting properties

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**वापसी:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Get children elements

**वापसी:**
com.aspose.slides.IMathElement[]