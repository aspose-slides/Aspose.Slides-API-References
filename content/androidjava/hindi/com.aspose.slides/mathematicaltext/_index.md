---
title: MathematicalText
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: गणितीय पाठ
type: docs
url: /hi/com.aspose.slides/mathematicaltext/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

गणितीय टेक्स्ट

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | डिफ़ॉल्ट कंस्ट्रक्टर (बनाएँ String.Empty Value) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | एकल प्रतीक के साथ MathText बनाएँ |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | टेक्स्ट से MathematicalText बनाएँ |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | टेक्स्ट और फ़ॉर्मेट सेटिंग्स से MathematicalText बनाएँ |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getValue()](#getValue--) | टेक्स्ट मान |
| [setValue(String value)](#setValue-java.lang.String-) | टेक्स्ट मान |
| [getFormat()](#getFormat--) | टेक्स्ट फ़ॉर्मेटिंग गुण |
| [getChildren()](#getChildren--) | संतान तत्व प्राप्त करें |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```


डिफ़ॉल्ट कंस्ट्रक्टर (बनाएँ String.Empty Value)

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


एकल प्रतीक के साथ MathText बनाएँ

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```


**परामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mathSymbol | char | एकल प्रतीक |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```


टेक्स्ट से MathematicalText बनाएँ

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**परामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mathText | java.lang.String | टेक्स्ट मान |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```


टेक्स्ट और फ़ॉर्मेट सेटिंग्स से MathematicalText बनाएँ

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**परामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mathText | java.lang.String | टेक्स्ट मान |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | टेक्स्ट फ़ॉर्मेट सेटिंग्स |

### getValue() {#getValue--}
```
public final String getValue()
```


टेक्स्ट मान

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**रिटर्न:**  
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


टेक्स्ट मान

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**परामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```


टेक्स्ट फ़ॉर्मेटिंग गुण

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**रिटर्न:**  
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


संतान तत्व प्राप्त करें

**रिटर्न:**  
com.aspose.slides.IMathElement[]