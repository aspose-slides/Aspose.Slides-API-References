---
title: IMathFunction
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: एक तर्क का फ़ंक्शन निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/imathfunction/
---
**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

एक तर्क का फ़ंक्शन निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getName()](#getName--) | फ़ंक्शन नाम, उदाहरण के लिए, फ़ंक्शन नाम sin और cos हैं |
| [getBase()](#getBase--) | फ़ंक्शन तर्क |
### getName() {#getName--}
```
public abstract IMathElement getName()
```


फ़ंक्शन नाम, उदाहरण के लिए, फ़ंक्शन नाम sin और cos हैं

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


फ़ंक्शन तर्क

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)