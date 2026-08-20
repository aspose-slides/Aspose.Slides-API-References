---
title: IMathDelimiter
second_title: Aspose.Slides for Java API संदर्भ
description: डिलिमीटर वस्तु को निर्दिष्ट करता है जिसमें कोष्ठक, कर्ली ब्रैकेट, ब्रैकेट और वर्टिकल बार जैसे खोलने और बंद करने वाले अक्षर होते हैं और एक या अधिक गणितीय तत्व अंदर होते हैं, जिन्हें निर्दिष्ट अक्षर द्वारा अलग किया जाता है।
type: docs
url: /hi/com.aspose.slides/imathdelimiter/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

विलंबक (delimiter) वस्तु को निर्धारित करता है, जिसमें खुलने और बंद होने वाले अक्षर (जैसे कोष्ठक, कर्ली ब्रैकेट, ब्रैकेट और वर्टिकल बार) होते हैं, तथा एक या अधिक गणितीय तत्व अंदर होते हैं, जिन्हें निर्दिष्ट अक्षर द्वारा अलग किया जाता है। उदाहरण: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getArguments()](#getArguments--) | एक या अधिक गणितीय तत्व जो delimiter अक्षरों द्वारा अलग किए गए हैं |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character शुरूआती, अर्थात् खोलने वाले delimiter अक्षर को निर्धारित करता है। |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character शुरूआती, अर्थात् खोलने वाले delimiter अक्षर को निर्धारित करता है। |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character delimiter वस्तु में तर्कों को अलग करने वाले अक्षर को निर्धारित करता है। |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character delimiter वस्तु में तर्कों को अलग करने वाले अक्षर को निर्धारित करता है। |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character समाप्ति, अर्थात् बंद करने वाले delimiter अक्षर को निर्धारित करता है। |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character समाप्ति, अर्थात् बंद करने वाले delimiter अक्षर को निर्धारित करता है। |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि को निर्दिष्ट करता है। जब true हो, तो delimiter ऊर्ध्वाधर रूप से अपने operand की ऊँचाई के अनुसार बढ़ता है। |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि को निर्दिष्ट करता है। जब true हो, तो delimiter ऊर्ध्वाधर रूप से अपने operand की ऊँचाई के अनुसार बढ़ता है। |
| [getDelimiterShape()](#getDelimiterShape--) | delimiter वस्तु में delimiters के आकार को निर्दिष्ट करता है। |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | delimiter वस्तु में delimiters के आकार को निर्दिष्ट करता है। |
| [delimit(char separatorCharacter)](#delimit-char-) | निर्दिष्ट delimiter अक्षर का उपयोग करके तर्कों को सीमित करता है |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```


एक या अधिक गणितीय तत्व जो delimiter अक्षरों द्वारा अलग किए गए हैं

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**वापसी:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public abstract char getBeginningCharacter()
```


Delimiter Beginning Character शुरूआती, अर्थात् खोलने वाले delimiter अक्षर को निर्धारित करता है। गणितीय delimiters वे घेरने वाले अक्षर होते हैं जैसे कोष्ठक, ब्रैकेट और कर्ली ब्रैकेट। डिफ़ॉल्ट मान: '('।

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**वापसी:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public abstract void setBeginningCharacter(char value)
```


Delimiter Beginning Character शुरूआती, अर्थात् खोलने वाले delimiter अक्षर को निर्धारित करता है। गणितीय delimiters वे घेरने वाले अक्षर होते हैं जैसे कोष्ठक, ब्रैकेट और कर्ली ब्रैकेट। डिफ़ॉल्ट मान: '('।

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```


Delimiter Separator Character delimiter वस्तु में तर्कों को अलग करने वाले अक्षर को निर्धारित करता है। डिफ़ॉल्ट: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**वापसी:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public abstract void setSeparatorCharacter(char value)
```


Delimiter Separator Character delimiter वस्तु में तर्कों को अलग करने वाले अक्षर को निर्धारित करता है। डिफ़ॉल्ट: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
```


Delimiter Ending Character समाप्ति, अर्थात् बंद करने वाले delimiter अक्षर को निर्धारित करता है। गणितीय delimiters वे घेरने वाले अक्षर होते हैं जैसे कोष्ठक, ब्रैकेट और कर्ली ब्रैकेट। डिफ़ॉल्ट मान: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**वापसी:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public abstract void setEndingCharacter(char value)
```


Delimiter Ending Character समाप्ति, अर्थात् बंद करने वाले delimiter अक्षर को निर्धारित करता है। गणितीय delimiters वे घेरने वाले अक्षर होते हैं जैसे कोष्ठक, ब्रैकेट और कर्ली ब्रैकेट। डिफ़ॉल्ट मान: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि को निर्दिष्ट करता है। जब true हो, तो delimiter ऊर्ध्वाधर रूप से अपने operand की ऊँचाई के अनुसार बढ़ता है। डिफ़ॉल्ट मान true है

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**वापसी:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि को निर्दिष्ट करता है। जब true हो, तो delimiter ऊर्ध्वाधर रूप से अपने operand की ऊँचाई के अनुसार बढ़ता है। डिफ़ॉल्ट मान true है

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```


delimiter वस्तु में delimiters के आकार को निर्दिष्ट करता है। जब MathDelimiterShape.Centered हो, तो delimiters गणितीय पाठ की अक्ष के चारों ओर केंद्रित होते हैं और उनकी सामग्री की पूरी ऊँचाई में फिट करने के लिए समायोजित किए जा सकते हैं। जब MathDelimiterShape.Match हो, तो उनकी ऊँचाई और आकार को ठीक उनके सामग्री के अनुसार बदला जाता है।

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**वापसी:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public abstract void setDelimiterShape(int value)
```


delimiter वस्तु में delimiters के आकार को निर्दिष्ट करता है। जब MathDelimiterShape.Centered हो, तो delimiters गणितीय पाठ की अक्ष के चारों ओर केंद्रित होते हैं और उनकी सामग्री की पूरी ऊँचाई में फिट करने के लिए समायोजित किए जा सकते हैं। जब MathDelimiterShape.Match हो, तो उनकी ऊँचाई और आकार को ठीक उनके सामग्री के अनुसार बदला जाता है।

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```


निर्दिष्ट delimiter अक्षर का उपयोग करके तर्कों को सीमित करता है

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| separatorCharacter | char | delimiter अक्षर |

**वापसी:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - delimiter अक्षर लागू करने के बाद यह वस्तु