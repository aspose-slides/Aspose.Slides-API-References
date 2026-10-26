---
title: MathFunction
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: एक तर्क का फ़ंक्शन निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/mathfunction/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IMathFunction](../../com.aspose.slides/imathfunction), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathFunction extends MathElementBase implements IMathFunction, IHasControlCharacterProperties
```

एक तर्क का फ़ंक्शन निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```
## निर्माता

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MathFunction(IMathElement funcName, IMathElement baseArgument)](#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathFunction class की नई इंस्टेंस को आरंभ करता है। |
| [MathFunction(String funcName, IMathElement baseArgument)](#MathFunction-java.lang.String-com.aspose.slides.IMathElement-) | MathFunction class की नई इंस्टेंस को आरंभ करता है। |

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getName()](#getName--) | फ़ंक्शन का नाम उदाहरण के लिए, फ़ंक्शन नाम sin और cos हैं |
| [getBase()](#getBase--) | फ़ंक्शन तर्क |
| [getChildren()](#getChildren--) | संतान तत्व प्राप्त करें |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | नियंत्रण वर्ण गुण |

### MathFunction(IMathElement funcName, IMathElement baseArgument) {#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFunction(IMathElement funcName, IMathElement baseArgument)
```

MathFunction class की नई इंस्टेंस को आरंभ करता है।

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction(new MathematicalText("sin"), new MathematicalText("x"));
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### MathFunction(String funcName, IMathElement baseArgument) {#MathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public MathFunction(String funcName, IMathElement baseArgument)
```

MathFunction class की नई इंस्टेंस को आरंभ करता है।

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| funcName | java.lang.String |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getName() {#getName--}
```
public final IMathElement getName()
```

फ़ंक्शन का नाम उदाहरण के लिए, फ़ंक्शन नाम sin और cos हैं

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**रिटर्न:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public final IMathElement getBase()
```

फ़ंक्शन तर्क

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**रिटर्न:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

संतान तत्व प्राप्त करें

**रिटर्न:**  
com.aspose.slides.IMathElement[] - [IMathElement](../../com.aspose.slides/imathelement) का एरे

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

नियंत्रण वर्ण गुण

**रिटर्न:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps