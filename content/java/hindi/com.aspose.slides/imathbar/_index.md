---
title: IMathBar
second_title: Aspose.Slides for Java API संदर्भ
description: बेस तर्क और ओवरबार या अंडरबार वाले बार फ़ंक्शन को निर्दिष्ट करता है
type: docs
url: /hi/com.aspose.slides/imathbar/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

बार फ़ंक्शन को निर्दिष्ट करता है, जिसमें एक बेस तर्क और ओवरबार या अंडरबार शामिल है

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  ```
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getBase()](#getBase--) | बेस तर्क |
| [getPosition()](#getPosition--) | बार लाइन की स्थिति। |
| [setPosition(int value)](#setPosition-int-) | बार लाइन की स्थिति। |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


बेस तर्क

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
>  ```

**रिटर्न:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


बार लाइन की स्थिति। डिफ़ॉल्ट: शीर्ष

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
>  ```

**रिटर्न:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


बार लाइन की स्थिति। डिफ़ॉल्ट: शीर्ष

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
>  ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |