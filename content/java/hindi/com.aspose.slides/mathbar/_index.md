---
title: MathBar
second_title: Aspose.Slides जावा API संदर्भ
description: बार फ़ंक्शन को निर्दिष्ट करता है, जिसमें एक बेस आर्ग्युमेंट और एक ओवरबार या अंडरबार शामिल है
type: docs
url: /hi/com.aspose.slides/mathbar/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathBar](../../com.aspose.slides/imathbar), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBar extends MathElementBase implements IMathBar, IHasControlCharacterProperties
```

बार फ़ंक्शन को निर्दिष्ट करता है, जिसमें एक बेस आर्ग्युमेंट और एक ओवरबार या अंडरबार शामिल है

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | ओवरबार (शीर्ष स्थिति) के साथ MathBar को प्रारंभ करता है |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | निर्दिष्ट स्थिति के साथ MathBar को प्रारंभ करता है |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getBase()](#getBase--) | बेस आर्ग्युमेंट |
| [getPosition()](#getPosition--) | बार रेखा की स्थिति। |
| [setPosition(int value)](#setPosition-int-) | बार रेखा की स्थिति। |
| [getChildren()](#getChildren--) | चाइल्ड एलिमेंट प्राप्त करें |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | कंट्रोल कैरेक्टर प्रॉपर्टीज़ |
### MathBar(IMathElement element) {#MathBar-com.aspose.slides.IMathElement-}
```
public MathBar(IMathElement element)
```


ओवरबार (शीर्ष स्थिति) के साथ MathBar को प्रारंभ करता है

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | वह बेस एलिमेंट जिससे बार लागू किया जाता है |

### MathBar(IMathElement element, int position) {#MathBar-com.aspose.slides.IMathElement-int-}
```
public MathBar(IMathElement element, int position)
```


निर्दिष्ट स्थिति के साथ MathBar को प्रारंभ करता है

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"), MathTopBotPositions.Bottom);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | वह बेस एलिमेंट जिससे बार लागू किया जाता है |
| position | int | बार रेखा की स्थिति। |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


बेस आर्ग्युमेंट

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


बार रेखा की स्थिति। डिफ़ॉल्ट: शीर्ष

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**वापसी:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


बार रेखा की स्थिति। डिफ़ॉल्ट: शीर्ष

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


बच्चे तत्व प्राप्त करें

**वापसी:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


नियंत्रण अक्षर गुण

**वापसी:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps