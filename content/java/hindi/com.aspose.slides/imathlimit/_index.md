---
title: IMathLimit
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: सीमा वस्तु को निर्दिष्ट करता है, जिसमें बेसलाइन पर पाठ और उसके ठीक ऊपर या नीचे छोटा आकार का पाठ शामिल है।
type: docs
url: /hi/com.aspose.slides/imathlimit/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLimit extends IMathElement
```

सीमा वस्तु को निर्दिष्ट करता है, जिसमें बेसलाइन पर पाठ और उसके ठीक ऊपर या नीचे छोटा आकार का पाठ शामिल है।

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
```
## विधियां

| विधि | विवरण |
| --- | --- |
| [getBase()](#getBase--) | बेस तर्क |
| [getLimit()](#getLimit--) | लिमिट तर्क |
| [getUpperLimit()](#getUpperLimit--) | ऊपरी या निचली सीमा निर्दिष्ट करता है |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | ऊपरी या निचली सीमा निर्दिष्ट करता है |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

बेस तर्क

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement baseArg = limitElement.getBase();
> ```

**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)
### getLimit() {#getLimit--}
```
public abstract IMathElement getLimit()
```

लिमिट तर्क

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement limitArg = limitElement.getLimit();
> ```

**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)
### getUpperLimit() {#getUpperLimit--}
```
public abstract boolean getUpperLimit()
```

ऊपरी या निचली सीमा निर्दिष्ट करता है

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**वापसी:**
boolean
### setUpperLimit(boolean value) {#setUpperLimit-boolean-}
```
public abstract void setUpperLimit(boolean value)
```

ऊपरी या निचली सीमा निर्दिष्ट करता है

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**परामीटर:**
| परिमिति | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |