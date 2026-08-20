---
title: MathDelimiter
second_title: Aspose.Slides for Java API संदर्भ
description: डिलिमिटर ऑब्जेक्ट को निर्दिष्ट करता है, जिसमें कोष्ठक, ब्रेसेस, ब्रैकेट और वर्टिकल बार जैसे खुलने और बंद होने वाले अक्षर होते हैं, और एक या अधिक गणितीय तत्व शामिल होते हैं जो एक निर्दिष्ट अक्षर द्वारा अलग किए जाते हैं।
type: docs
url: /hi/com.aspose.slides/mathdelimiter/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

डिलिमिटर ऑब्जेक्ट को निर्दिष्ट करता है, जिसमें खुलने और बंद होने वाले अक्षर शामिल होते हैं (जैसे कोष्ठक, कर्ली ब्रेसेस, ब्रेसेज़, और वर्टिकल बार), तथा एक या अधिक गणितीय तत्व होते हैं जो एक निर्धारित अक्षर द्वारा अलग होते हैं। उदाहरण: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | MathDelimiter को निर्दिष्ट तत्व को एकल बेस आर्ग्युमेंट के रूप में उपयोग करके प्रारम्भ करता है |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getArguments()](#getArguments--) | डिलिमिटर अक्षरों द्वारा अलग किए गए एक या अधिक गणितीय तत्व |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character प्रारम्भिक, अर्थात खुलने वाले, डिलिमिटर अक्षर को निर्दिष्ट करता है। |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character प्रारम्भिक, अर्थात खुलने वाले, डिलिमिटर अक्षर को निर्दिष्ट करता है। |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character डिलिमिटर ऑब्जेक्ट में आर्ग्युमेंट्स को अलग करने वाले अक्षर को निर्दिष्ट करता है। |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character डिलिमिटर ऑब्जेक्ट में आर्ग्युमेंट्स को अलग करने वाले अक्षर को निर्दिष्ट करता है। |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character समाप्ति, अर्थात बंद होने वाले, डिलिमिटर अक्षर को निर्दिष्ट करता है। |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character समाप्ति, अर्थात बंद होने वाले, डिलिमिटर अक्षर को निर्दिष्ट करता है। |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि निर्दिष्ट करता है। जब true हो, तो डिलिमिटर ऊँचाई के अनुसार वर्टिकली बढ़ते हैं। |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि निर्दिष्ट करता है। जब true हो, तो डिलिमिटर ऊँचाई के अनुसार वर्टिकली बढ़ते हैं। |
| [getDelimiterShape()](#getDelimiterShape--) | डिलिमिटर ऑब्जेक्ट में डिलिमिटर के आकार को निर्दिष्ट करता है। |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | डिलिमिटर ऑब्जेक्ट में डिलिमिटर के आकार को निर्दिष्ट करता है। |
| [delimit(char separatorCharacter)](#delimit-char-) | निर्दिष्ट डिलिमिटर अक्षर का उपयोग कर आर्ग्युमेंट्स को सीमित करता है |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | गणितीय तत्व को निर्दिष्ट अक्षरों जैसे कोष्ठक में या फ्रेमिंग के लिए अन्य अक्षरों में लपेटता है |
| [getChildren()](#getChildren--) | बच्चे तत्व प्राप्त करें |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | नियंत्रण अक्षर गुण |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```


MathDelimiter को निर्दिष्ट तत्व को एकल बेस आर्ग्युमेंट के रूप में उपयोग करके प्रारम्भ करता है

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | वह बेस तत्व जिससे डिलिमिटर लागू किया जाता है। null भी हो सकता है। |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
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
public final char getBeginningCharacter()
```


Delimiter Beginning Character प्रारम्भिक, अर्थात खुलने वाले, डिलिमिटर अक्षर को निर्दिष्ट करता है। गणितीय डिलिमिटर कोष्ठक, ब्रेसेज़, तथा कर्ली ब्रेसेस जैसे घेरा अक्षर होते हैं। डिफ़ॉल्ट: '('।

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
public final void setBeginningCharacter(char value)
```


Delimiter Beginning Character प्रारम्भिक, अर्थात खुलने वाले, डिलिमिटर अक्षर को निर्दिष्ट करता है। गणितीय डिलिमिटर कोष्ठक, ब्रेसेज़, तथा कर्ली ब्रेसेस जैसे घेरा अक्षर होते हैं। डिफ़ॉल्ट: '('।

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
public final char getSeparatorCharacter()
```


Delimiter Separator Character डिलिमिटर ऑब्जेक्ट में आर्ग्युमेंट्स को अलग करने वाले अक्षर को निर्दिष्ट करता है। डिफ़ॉल्ट: '|'.

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
public final void setSeparatorCharacter(char value)
```


Delimiter Separator Character डिलिमिटर ऑब्जेक्ट में आर्ग्युमेंट्स को अलग करने वाले अक्षर को निर्दिष्ट करता है। डिफ़ॉल्ट: '|'.

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
public final char getEndingCharacter()
```


Delimiter Ending Character समाप्ति, अर्थात बंद होने वाले, डिलिमिटर अक्षर को निर्दिष्ट करता है। गणितीय डिलिमिटर कोष्ठक, ब्रेसेज़, तथा कर्ली ब्रेसेस जैसे घेरा अक्षर होते हैं। डिफ़ॉल्ट: ')'.

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
public final void setEndingCharacter(char value)
```


Delimiter Ending Character समाप्ति, अर्थात बंद होने वाले, डिलिमिटर अक्षर को निर्दिष्ट करता है। गणितीय डिलिमिटर कोष्ठक, ब्रेसेज़, तथा कर्ली ब्रेसेस जैसे घेरा अक्षर होते हैं। डिफ़ॉल्ट: ')'.

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
public final boolean getGrowToMatchOperandHeight()
```


BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि निर्दिष्ट करता है। जब true हो, तो डिलिमिटर ऊँचाई के अनुसार वर्टिकली बढ़ते हैं। डिफ़ॉल्ट मान true है

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
public final void setGrowToMatchOperandHeight(boolean value)
```


BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि निर्दिष्ट करता है। जब true हो, तो डिलिमिटर ऊँचाई के अनुसार वर्टिकली बढ़ते हैं। डिफ़ॉल्ट मान true है

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
public final int getDelimiterShape()
```


डिलिमिटर ऑब्जेक्ट में डिलिमिटर के आकार को निर्दिष्ट करता है। जब MathDelimiterShape.Centered हो, तो डिलिमिटर गणितीय पाठ की अक्ष पर केंद्रित होते हैं और उनकी पूरी ऊँचाई में फिट होने के लिए समायोजित होते हैं। जब MathDelimiterShape.Match हो, तो उनकी ऊँचाई और आकार बिल्कुल उनके सामग्री के अनुरूप बदलते हैं।

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
public final void setDelimiterShape(int value)
```


डिलिमिटर ऑब्जेक्ट में डिलिमिटर के आकार को निर्दिष्ट करता है। जब MathDelimiterShape.Centered हो, तो डिलिमिटर गणितीय पाठ की अक्ष पर केंद्रित होते हैं और उनकी पूरी ऊँचाई में फिट होने के लिए समायोजित होते हैं। जब MathDelimiterShape.Match हो, तो उनकी ऊँचाई और आकार बिल्कुल उनके सामग्री के अनुरूप बदलते हैं।

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
public final IMathDelimiter delimit(char separatorCharacter)
```


निर्दिष्ट डिलिमिटर अक्षर का उपयोग कर आर्ग्युमेंट्स को सीमित करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| separatorCharacter | char | डिलिमिटर अक्षर |

**रिटर्न:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - डिलिमिटर अक्षर लागू करने के बाद यह ऑब्जेक्ट

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


गणितीय तत्व को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य फ्रेमिंग अक्षरों में लपेटता है

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| beginningCharacter | char | प्रारम्भिक अक्षर (आमतौर पर बायाँ कोष्ठक) |
| endingCharacter | char | समाप्ति अक्षर (आमतौर पर दायाँ कोष्ठक) |

**रिटर्न:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - यदि beginningCharacter और endingCharacter null हों, तो संबंधित गुण केवल मान सौंपे जाते हैं और नया ऑब्जेक्ट नहीं बनाया जाता (this instance लौटाता है)। अन्यथा, नया गणितीय तत्व Delimiter प्रकार का लौटाया जाता है जिसमें निर्दिष्ट अक्षर फ्रेमिंग के रूप में होते हैं और यह [MathDelimiter](../../com.aspose.slides/mathdelimiter) का फ्रेम्ड संस्करण होता है।

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


नियंत्रण अक्षर गुण

**रिटर्न:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps