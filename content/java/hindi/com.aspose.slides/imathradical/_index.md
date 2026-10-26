---
title: IMathRadical
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एक आधार और वैकल्पिक डिग्री से बनी रेडिकल फ़ंक्शन को निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/imathradical/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

आधार और वैकल्पिक डिग्री से बनी रेडिकल फ़ंक्शन को निर्दिष्ट करता है। रेडिकल ऑब्जेक्ट का उदाहरण है \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // घन मूल
```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBase()](#getBase--) | आधार तर्क |
| [getDegree()](#getDegree--) | डिग्री तर्क |
| [getHideDegree()](#getHideDegree--) | जब Hide degree true हो, डिग्री नहीं दिखाया जाता, जैसे \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | जब Hide degree true हो, डिग्री नहीं दिखाया जाता, जैसे \\u221a\\ud835\\udc65 |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

आधार तर्क

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // घन मूल
>  IMathElement baseElem = radical.getBase();
>```

**रिटर्न:**  
[IMathElement](../../com.aspose.slides/imathelement)

### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```

डिग्री तर्क

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // घन मूल
>  IMathElement degreeElem = radical.getDegree();
> ```

**रिटर्न:**  
[IMathElement](../../com.aspose.slides/imathelement)

### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```

जब Hide degree true हो, डिग्री नहीं दिखाया जाता, जैसे \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // घन मूल
>  radical.setHideDegree(true);
> ```

**रिटर्न:**  
boolean

### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```

जब Hide degree true हो, डिग्री नहीं दिखाया जाता, जैसा कि \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // घन मूल
>  radical.setHideDegree(true);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |