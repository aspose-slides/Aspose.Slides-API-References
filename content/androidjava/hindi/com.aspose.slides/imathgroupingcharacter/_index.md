---
title: IMathGroupingCharacter
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: आमतौर पर तत्वों के बीच संबंध को उजागर करने के लिए, अभिव्यक्ति के ऊपर या नीचे एक समूह चिन्ह निर्दिष्ट करता है
type: docs
url: /hi/com.aspose.slides/imathgroupingcharacter/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

एक अभिव्यक्ति के ऊपर या नीचे एक समूह चिन्ह निर्दिष्ट करता है, आमतौर पर तत्वों के बीच संबंध को उजागर करने के लिए

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBase()](#getBase--) | बेस तर्क |
| [getCharacter()](#getCharacter--) | समूह अक्षर का डिफ़ॉल्ट मान: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | समूह अक्षर का डिफ़ॉल्ट मान: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | समूह अक्षर की स्थिति। |
| [setPosition(int value)](#setPosition-int-) | समूह अक्षर की स्थिति। |
| [getVerticalJustification()](#getVerticalJustification--) | समूह अक्षर की लंबवत संरेखण। |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | समूह अक्षर की लंबवत संरेखण। |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

बेस तर्क

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**वापसी:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

समूह अक्षर का डिफ़ॉल्ट मान: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // निचला कोष्ठक
> ```

**वापसी:**  
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

समूह अक्षर का डिफ़ॉल्ट मान: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // निचला कोष्ठक
```

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | char |  |
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

समूह अक्षर की स्थिति। डिफ़ॉल्ट: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**वापसी:**  
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

समूह अक्षर की स्थिति। डिफ़ॉल्ट: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```

समूह अक्षर की लंबवत संरेखण। वस्तु को बेसलाइन के सापेक्ष संरेखित करने का तरीका निर्दिष्ट करता है। उदाहरण के लिए, जब समूह अक्षर वस्तु के ऊपर होता है, तो Top की VerticalJustification यह दर्शाता है कि वस्तु का शीर्ष बेसलाइन पर स्थित है; जब VerticalJustification को Bottom पर सेट किया जाता है, तो वस्तु का निचला भाग बेसलाइन पर रहता है। डिफ़ॉल्ट: Position=Top के लिए Bottom, और Position=Bottom के लिए Top

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**वापसी:**  
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```

समूह अक्षर की लंबवत संरेखण। वस्तु को बेसलाइन के सापेक्ष संरेखित करने का तरीका निर्दिष्ट करता है। उदाहरण के लिए, जब समूह अक्षर वस्तु के ऊपर होता है, तो Top की VerticalJustification यह दर्शाता है कि वस्तु का शीर्ष बेसलाइन पर स्थित है; जब VerticalJustification को Bottom पर सेट किया जाता है, तो वस्तु का निचला भाग बेसलाइन पर रहता है। डिफ़ॉल्ट: Position=Top के लिए Bottom, और Position=Bottom के लिए Top

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |