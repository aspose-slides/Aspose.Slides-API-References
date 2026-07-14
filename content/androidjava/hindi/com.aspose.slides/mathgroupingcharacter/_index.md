---
title: MathGroupingCharacter
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक अभिव्यक्ति के ऊपर या नीचे समूह चिन्ह निर्दिष्ट करता है, आमतौर पर तत्वों के बीच संबंध को उजागर करने के लिए
type: docs
url: /hi/com.aspose.slides/mathgroupingcharacter/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

एक अभिव्यक्ति के ऊपर या नीचे समूह चिन्ह निर्दिष्ट करता है, आमतौर पर तत्वों के बीच संबंध को उजागर करने के लिए  

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## कंस्ट्रक्टर

| निर्माता | विवरण |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | MathGroupingCharacter क्लास का एक नया उदाहरण डिफ़ॉल्ट ग्रुपिंग कैरेक्टर U+23DF (BOTTOM CURLY BRACKET) के साथ आरंभ करता है |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | MathGroupingCharacter क्लास का एक नया उदाहरण आरंभ करता है |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBase()](#getBase--) | मूल तर्क |
| [getCharacter()](#getCharacter--) | ग्रुपिंग कैरेक्टर डिफ़ॉल्ट मान: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | ग्रुपिंग कैरेक्टर डिफ़ॉल्ट मान: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | ग्रुपिंग कैरेक्टर की स्थिति। |
| [setPosition(int value)](#setPosition-int-) | ग्रुपिंग कैरेक्टर की स्थिति। |
| [getVerticalJustification()](#getVerticalJustification--) | ग्रुप कैरेक्टर का वर्टिकल जस्टिफिकेशन। |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | ग्रुप कैरेक्टर का वर्टिकल जस्टिफिकेशन। |
| [getChildren()](#getChildren--) | संतान तत्व प्राप्त करें |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | कंट्रोल कैरेक्टर गुण |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```

MathGroupingCharacter क्लास का एक नया उदाहरण डिफ़ॉल्ट ग्रुपिंग कैरेक्टर U+23DF (BOTTOM CURLY BRACKET) के साथ आरंभ करता है

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | बार लागू किए जाने वाला मूल तत्व |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

MathGroupingCharacter क्लास का एक नया उदाहरण आरंभ करता है।

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | बार लागू किए जाने वाला मूल तत्व |
| character | char | ग्रुपिंग कैरेक्टर |
| position | int | ग्रुपिंग कैरेक्टर की स्थिति |
| verticalJustification | int | ग्रुप कैरेक्टर का वर्टिकल जस्टिफिकेशन |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

मूल तर्क

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**रिटर्न:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

ग्रुपिंग कैरेक्टर डिफ़ॉल्ट मान: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // निचला कोष्ठक
> ```

**रिटर्न:**  
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

ग्रुपिंग कैरेक्टर डिफ़ॉल्ट मान: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // निचला कोष्ठक
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

ग्रुपिंग कैरेक्टर की स्थिति। डिफ़ॉल्ट: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**रिटर्न:**  
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

ग्रुपिंग कैरेक्टर की स्थिति। डिफ़ॉल्ट: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public final int getVerticalJustification()
```

ग्रुप कैरेक्टर का वर्टिकल जस्टिफिकेशन। यह वस्तु को बेसलाइन के सापेक्ष संरेखित करता है। उदाहरण के लिए, जब ग्रुप कैरेक्टर वस्तु के ऊपर होता है, तो Top का VerticalJustification दर्शाता है कि वस्तु का शीर्ष बेसलाइन पर स्थित है; जब VerticalJustification Bottom पर सेट किया जाता है, तो वस्तु का निचला भाग बेसलाइन पर रहता है। डिफ़ॉल्ट: Position=Top के लिए Bottom, और Position=Bottom के लिए Top

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**रिटर्न:**  
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```

ग्रुप कैरेक्टर का वर्टिकल जस्टिफिकेशन। यह वस्तु को बेसलाइन के सापेक्ष संरेखित करता है। उदाहरण के लिए, जब ग्रुप कैरेक्टर वस्तु के ऊपर होता है, तो Top का VerticalJustification दर्शाता है कि वस्तु का शीर्ष बेसलाइन पर स्थित है; जब VerticalJustification Bottom पर सेट किया जाता है, तो वस्तु का निचला भाग बेसलाइन पर रहता है। डिफ़ॉल्ट: Position=Top के लिए Bottom, और Position=Bottom के लिए Top

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
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

**रिटर्न:**  
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

नियंत्रण कैरेक्टर गुण

**रिटर्न:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps