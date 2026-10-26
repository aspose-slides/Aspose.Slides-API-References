---
title: IMathDelimiter
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: डिलिमिटर ऑब्जेक्ट को निर्दिष्ट करता है जिसमें उद्घाटन और समापन अक्षर शामिल होते हैं जैसे कोष्ठक, कर्ली ब्रेसेस, ब्रैकेट और ऊर्ध्वाधर बार, और एक या अधिक गणितीय तत्व अंदर होते हैं जिन्हें निर्दिष्ट अक्षर से विभाजित किया जाता है।
type: docs
url: /hi/com.aspose.slides/imathdelimiter/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

डिलिमिटर ऑब्जेक्ट को निर्दिष्ट करता है, जो उद्घाटन और समापन अक्षरों (जैसे कोष्ठक, कर्ली ब्रेसेस, ब्रैकेट्स, और वर्टिकल बार) से बना होता है, और एक या अधिक गणितीय तत्वों को निर्दिष्ट अक्षर द्वारा अलग किया जाता है। उदाहरण: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getArguments()](#getArguments--) | डिलिमिटर अक्षरों द्वारा अलग किए गए एक या अधिक गणितीय तत्व |
| [getBeginningCharacter()](#getBeginningCharacter--) | डिलिमिटर शुरूआत अक्षर प्रारंभ या खोलने वाले डिलिमिटर अक्षर को निर्दिष्ट करता है। |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | डिलिमिटर शुरूआत अक्षर प्रारंभ या खोलने वाले डिलिमिटर अक्षर को निर्दिष्ट करता है। |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | डिलिमिटर विभाजक अक्षर उस अक्षर को निर्दिष्ट करता है जो डिलिमिटर ऑब्जेक्ट में तर्कों को अलग करता है। |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | डिलिमिटर विभाजक अक्षर उस अक्षर को निर्दिष्ट करता है जो डिलिमिटर ऑब्जेक्ट में तर्कों को अलग करता है। |
| [getEndingCharacter()](#getEndingCharacter--) | डिलिमिटर समाप्ति अक्षर अंत या बंद करने वाले डिलिमिटर अक्षर को निर्दिष्ट करता है। |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | डिलिमिटर समाप्ति अक्षर अंत या बंद करने वाले डिलिमिटर अक्षर को निर्दिष्ट करता है। |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | शुरुआत अक्षर, विभाजक अक्षर, समाप्ति अक्षर की वृद्धि को निर्दिष्ट करता है। जब true हो, तो डिलिमिटर ऊँचाई के अनुसार लंबवत रूप से बढ़ता है। |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | शुरुआत अक्षर, विभाजक अक्षर, समाप्ति अक्षर की वृद्धि को निर्दिष्ट करता है। जब true हो, तो डिलिमिटर ऊँचाई के अनुसार लंबवत रूप से बढ़ता है। |
| [getDelimiterShape()](#getDelimiterShape--) | डिलिमिटर ऑब्जेक्ट में डिलिमिटर के आकार को निर्दिष्ट करता है। |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | डिलिमिटर ऑब्जेक्ट में डिलिमिटर के आकार को निर्दिष्ट करता है। |
| [delimit(char separatorCharacter)](#delimit-char-) | निर्दिष्ट डिलिमिटर अक्षर का उपयोग करके तर्कों को सीमित करता है। |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```


डिलिमिटर अक्षरों द्वारा अलग किए गए एक या अधिक गणितीय तत्व

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**रिटर्न:**  
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public abstract char getBeginningCharacter()
```


डिलिमिटर शुरूआत अक्षर प्रारंभ या खोलने वाले डिलिमिटर अक्षर को निर्दिष्ट करता है। गणितीय डिलिमिटर वे अक्षर होते हैं जैसे कोष्ठक, ब्रैकेट, और कर्ली ब्रेसेस। डिफ़ॉल्ट मान: '('।

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**रिटर्न:**  
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public abstract void setBeginningCharacter(char value)
```


डिलिमिटर शुरूआत अक्षर प्रारंभ या खोलने वाले डिलिमिटर अक्षर को निर्दिष्ट करता है। गणितीय डिलिमिटर वे अक्षर होते हैं जैसे कोष्ठक, ब्रैकेट, और कर्ली ब्रेसेस। डिफ़ॉल्ट मान: '('।

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```


डिलिमिटर विभाजक अक्षर उस अक्षर को निर्दिष्ट करता है जो डिलिमिटर ऑब्जेक्ट में तर्कों को अलग करता है। डिफ़ॉल्ट: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**रिटर्न:**  
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public abstract void setSeparatorCharacter(char value)
```


डिलिमिटर विभाजक अक्षर उस अक्षर को निर्दिष्ट करता है जो डिलिमिटर ऑब्जेक्ट में तर्कों को अलग करता है। डिफ़ॉल्ट: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
```


डिलिमिटर समाप्ति अक्षर अंत या बंद करने वाले डिलिमिटर अक्षर को निर्दिष्ट करता है। गणितीय डिलिमिटर वे अक्षर होते हैं जैसे कोष्ठक, ब्रैकेट और कर्ली ब्रेसेस। डिफ़ॉल्ट मान: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**रिटर्न:**  
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public abstract void setEndingCharacter(char value)
```


डिलिमिटर समाप्ति अक्षर अंत या बंद करने वाले डिलिमिटर अक्षर को निर्दिष्ट करता है। गणितीय डिलिमिटर वे अक्षर होते हैं जैसे कोष्ठक, ब्रैकेट और कर्ली ब्रेसेस। डिफ़ॉल्ट मान: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


शुरुआत अक्षर, विभाजक अक्षर, समाप्ति अक्षर की वृद्धि को निर्दिष्ट करता है। जब true हो, तो डिलिमिटर ऊँचाई के अनुसार लंबवत रूप से बढ़ता है। डिफ़ॉल्ट मान true है।

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**रिटर्न:**  
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


शुरुआत अक्षर, विभाजक अक्षर, समाप्ति अक्षर की वृद्धि को निर्दिष्ट करता है। जब true हो, तो डिलिमिटर ऊँचाई के अनुसार लंबवत रूप से बढ़ता है। डिफ़ॉल्ट मान true है।

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```


डिलिमिटर ऑब्जेक्ट में डिलिमिटर के आकार को निर्दिष्ट करता है। जब MathDelimiterShape.Centered हो, तो डिलिमिटर गणितीय टेक्स्ट के अक्ष के चारों ओर केंद्रित होते हैं और अपनी सामग्री की पूरी ऊँचाई में फिट रहने के लिये समायोजित किए जाते हैं। जब MathDelimiterShape.Match हो, तो उनकी ऊँचाई और आकार बिलकुल उनकी सामग्री से मेल खाने के लिये बदल दिए जाते हैं।

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**रिटर्न:**  
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public abstract void setDelimiterShape(int value)
```


डिलिमिटर ऑब्जेक्ट में डिलिमिटर के आकार को निर्दिष्ट करता है। जब MathDelimiterShape.Centered हो, तो डिलिमिटर गणितीय टेक्स्ट के अक्ष के चारों ओर केंद्रित होते हैं और अपनी सामग्री की पूरी ऊँचाई में फिट रहने के लिये समायोजित किए जाते हैं। जब MathDelimiterShape.Match हो, तो उनकी ऊँचाई और आकार बिलकुल उनकी सामग्री से मेल खाने के लिये बदल दिए जाते हैं।

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```


निर्दिष्ट डिलिमिटर अक्षर का उपयोग करके तर्कों को सीमित करता है।

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| separatorCharacter | char | डिलिमिटर अक्षर |

**रिटर्न:** [IMathDelimiter](../../com.aspose.slides/imathdelimiter) - डिलिमिटर अक्षर लागू करने के बाद यह ऑब्जेक्ट