---
title: MathGroupingCharacter
second_title: Aspose.Slides Java के लिए API संदर्भ
description: एक अभिव्यक्ति के ऊपर या नीचे समूह चिन्ह को निर्दिष्ट करता है, आमतौर पर तत्वों के बीच संबंध को उजागर करने के लिए
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

एक समूह चिन्ह को अभिव्यक्ति के ऊपर या नीचे निर्दिष्ट करता है, आमतौर पर तत्वों के बीच संबंध को उजागर करने के लिए

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | डिफ़ॉल्ट समूह अक्षर U+23DF (BOTTOM CURLY BRACKET) के साथ MathGroupingCharacter क्लास का नया उदाहरण आरंभ करता है |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | MathGroupingCharacter क्लास का नया उदाहरण आरंभ करता है |
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getBase()](#getBase--) | आधार तर्क |
| [getCharacter()](#getCharacter--) | समूह अक्षर डिफ़ॉल्ट मान: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | समूह अक्षर डिफ़ॉल्ट मान: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | समूह अक्षर की स्थिति। |
| [setPosition(int value)](#setPosition-int-) | समूह अक्षर की स्थिति। |
| [getVerticalJustification()](#getVerticalJustification--) | समूह अक्षर की लंबवत उचितता। |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | समूह अक्षर की लंबवत उचितता। |
| [getChildren()](#getChildren--) | संतान तत्व प्राप्त करें |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | नियंत्रण अक्षर गुण |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```

डिफ़ॉल्ट समूह अक्षर U+23DF (BOTTOM CURLY BRACKET) के साथ MathGroupingCharacter क्लास का नया उदाहरण आरंभ करता है

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | वह आधार तत्व जिससे बार लागू किया जाता है |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

MathGroupingCharacter क्लास का नया उदाहरण आरंभ करता है।

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | वह आधार तत्व जिससे बार लागू किया जाता है |
| character | char | समूह अक्षर |
| position | int | समूह अक्षर की स्थिति |
| verticalJustification | int | समूह अक्षर की लंबवत उचितता |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

आधार तर्क

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**वापसी मान:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

समूह अक्षर डिफ़ॉल्ट मान: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // निचला कोष्ठक
> ```

**वापसी मान:**  
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

समूह अक्षर डिफ़ॉल्ट मान: U+23DF (BOTTOM CURLY BRACKET)

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

समूह अक्षर की स्थिति। डिफ़ॉल्ट: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**वापसी मान:**  
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

समूह अक्षर की स्थिति। डिफ़ॉल्ट: Bottom

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

समूह अक्षर की लंबवत उचितता। वस्तु का बेसलाइन के सापेक्ष संरेखण निर्दिष्ट करता है। उदाहरण के लिए, जब समूह अक्षर वस्तु के ऊपर होता है, तब VerticalJustification का Top दर्शाता है कि वस्तु का शीर्ष बेसलाइन पर रहता है; जब VerticalJustification को Bottom पर सेट किया जाता है, तो वस्तु का निचला भाग बेसलाइन पर रहता है। डिफ़ॉल्ट: Bottom जब Position=Top, और Top जब Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**वापसी मान:**  
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```

समूह अक्षर की लंबवत उचितता। वस्तु का बेसलाइन के सापेक्ष संरेखण निर्दिष्ट करता है। उदाहरण के लिए, जब समूह अक्षर वस्तु के ऊपर होता है, तब VerticalJustification का Top दर्शाता है कि वस्तु का शीर्ष बेसलाइन पर रहता है; जब VerticalJustification को Bottom पर सेट किया जाता है, तो वस्तु का निचला भाग बेसलाइन पर रहता है। डिफ़ॉल्ट: Bottom जब Position=Top, और Top जब Position=Bottom

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

**वापसी मान:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

नियंत्रण अक्षर गुण

**वापसी मान:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps