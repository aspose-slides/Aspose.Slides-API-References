---
title: IMathBar
second_title: Java API रेफ़रेंस के माध्यम से Android के लिए Aspose.Slides
description: बेस आर्ग्यूमेंट और ओवरबार या अंडरबार से मिलकर बनी बार फ़ंक्शन को निर्दिष्ट करता है
type: docs
url: /hi/com.aspose.slides/imathbar/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

बार फ़ंक्शन को निर्दिष्ट करता है, जिसमें एक बेस आर्ग्यूमेंट और एक ओवरबार या अंडरबार शामिल है

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getBase()](#getBase--) | बेस आर्ग्यूमेंट |
| [getPosition()](#getPosition--) | बार लाइन की स्थिति। |
| [setPosition(int value)](#setPosition-int-) | बार लाइन की स्थिति। |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


बेस आर्ग्यूमेंट

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**रिटर्न्स:**
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
> ```

**रिटर्न्स:**
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
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |