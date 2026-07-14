---
title: MathBar
second_title: Aspose.Slides Android के लिए Java API संदर्भ के माध्यम से
description: एक बेस तर्क और ओवरबार या अंडरबार से मिलकर बनी बार फ़ंक्शन को निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/mathbar/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी लागू किए गए इंटरफ़ेस:**
[com.aspose.slides.IMathBar](../../com.aspose.slides/imathbar), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBar extends MathElementBase implements IMathBar, IHasControlCharacterProperties
```

एक बुनियादी तर्क और एक ओवरबार या अंडरबार से मिलकर बनी बार फ़ंक्शन को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## कन्स्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | Initializes MathBar with overbar (Top position) |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | Initializes MathBar with specified position |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getPosition()](#getPosition--) | Position of the bar line. |
| [setPosition(int value)](#setPosition-int-) | Position of the bar line. |
| [getChildren()](#getChildren--) | Get children elements |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathBar(IMathElement element) {#MathBar-com.aspose.slides.IMathElement-}
```
public MathBar(IMathElement element)
```

MathBar को ओवरबार (ऊपरी स्थिति) के साथ प्रारंभ करता है।

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | The base element to which the bar is applied |

### MathBar(IMathElement element, int position) {#MathBar-com.aspose.slides.IMathElement-int-}
```
public MathBar(IMathElement element, int position)
```

MathBar को निर्दिष्ट स्थिति के साथ प्रारंभ करता है।

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"), MathTopBotPositions.Bottom);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | The base element to which the bar is applied |
| position | int | Position of the bar line. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

बेस तर्क

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**परिणाम:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

बार लाइन की स्थिति। डिफ़ॉल्ट: शीर्ष

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**परिणाम:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

बार लाइन की स्थिति। डिफ़ॉल्ट: शीर्ष

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

संतान तत्व प्राप्त करें

**परिणाम:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

नियंत्रण अक्षर गुण

**परिणाम:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps