---
title: MathDelimiter
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: उद्घाटन और समापन अक्षरों (जैसे कोष्ठक, ब्रेस, कोलन और वर्टिकल बार) तथा एक या अधिक गणितीय तत्वों से मिलकर बना डिलिमिटर ऑब्जेक्ट निर्दिष्ट करता है, जिसे एक निर्दिष्ट अक्षर द्वारा अलग किया जाता है।
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

डिलिमिटर ऑब्जेक्ट निर्दिष्ट करता है, जिसमें उद्घाटन और समापन अक्षर होते हैं (जैसे कोष्ठक, ब्रेस, ब्रैकेट, और वर्टिकल बार), और एक या अधिक गणितीय तत्वों को निर्दिष्ट अक्षर द्वारा अलग किया जाता है। उदाहरण: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | निर्दिष्ट तत्व को एकल बेस आर्ग्यूमेंट के रूप में लेकर MathDelimiter को इनिशियलाइज़ करता है |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getArguments()](#getArguments--) | एक या अधिक गणितीय तत्व डिलिमिटर अक्षरों द्वारा अलग किए गए |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character शुरुआती, अर्थात ओपनिंग, डिलिमिटर कैरेक्टर को निर्दिष्ट करता है। |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character शुरुआती, अर्थात ओपनिंग, डिलिमिटर कैरेक्टर को निर्दिष्ट करता है। |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character वह अक्षर निर्दिष्ट करता है जो डिलिमिटर ऑब्जेक्ट में आर्ग्यूमेंट्स को अलग करता है। |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character वह अक्षर निर्दिष्ट करता है जो डिलिमिटर ऑब्जेक्ट में आर्ग्यूमेंट्स को अलग करता है। |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character अंत, अर्थात क्लोजिंग, डिलिमिटर कैरेक्टर को निर्दिष्ट करता है। |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character अंत, अर्थात क्लोजिंग, डिलिमिटर कैरेक्टर को निर्दिष्ट करता है। |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि निर्दिष्ट करता है। जब true हो, तो डिलिमिटर ऊर्ध्वाधर रूप से अपने ऑपरेण्ड की ऊँचाई के अनुसार बढ़ता है। |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि निर्दिष्ट करता है। जब true हो, तो डिलिमिटर ऊर्ध्वाधर रूप से अपने ऑपरेण्ड की ऊँचाई के अनुसार बढ़ता है। |
| [getDelimiterShape()](#getDelimiterShape--) | डिलिमिटर ऑब्जेक्ट में डिलिमिटर के आकार को निर्दिष्ट करता है। |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | डिलिमिटर ऑब्जेक्ट में डिलिमिटर के आकार को निर्दिष्ट करता है। |
| [delimit(char separatorCharacter)](#delimit-char-) | निर्दिष्ट डिलिमिटर अक्षर का उपयोग करके आर्ग्यूमेंट्स को डिलिमिट करता है |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | गणितीय तत्व को निर्दिष्ट अक्षरों (जैसे कोष्ठक या अन्य फ्रेमिंग अक्षर) में लपेटता है |
| [getChildren()](#getChildren--) | चाइल्ड एलिमेंट्स प्राप्त करता है |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | कंट्रोल कैरेक्टर प्रॉपर्टीज़ |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

निर्दिष्ट तत्व को एकल बेस आर्ग्यूमेंट के रूप में लेकर MathDelimiter को इनिशियलाइज़ करता है

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
| element | [IMathElement](../../com.aspose.slides/imathelement) | वह बेस एलिमेंट जिसमें डिलिमिटर लागू किया जाता है। यह null हो सकता है। |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

एक या अधिक गणितीय तत्व डिलिमिटर अक्षरों द्वारा अलग किए गए

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

Delimiter Beginning Character शुरुआती, अर्थात ओपनिंग, डिलिमिटर कैरेक्टर को निर्दिष्ट करता है। गणितीय डिलिमिटर वे समापन अक्षर होते हैं जैसे कोष्ठक, ब्रैकेट, और ब्रेस। डिफ़ॉल्ट: '('।

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

Delimiter Beginning Character शुरुआती, अर्थात ओपनिंग, डिलिमिटर कैरेक्टर को निर्दिष्ट करता है। गणितीय डिलिमिटर वे समापन अक्षर होते हैं जैसे कोष्ठक, ब्रैकेट, और ब्रेस। डिफ़ॉल्ट: '('।

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

Delimiter Separator Character वह अक्षर निर्दिष्ट करता है जो डिलिमिटर ऑब्जेक्ट में आर्ग्यूमेंट्स को अलग करता है। डिफ़ॉल्ट: '|'।

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

Delimiter Separator Character वह अक्षर निर्दिष्ट करता है जो डिलिमिटर ऑब्जेक्ट में आर्ग्यूमेंट्स को अलग करता है। डिफ़ॉल्ट: '|'।

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

Delimiter Ending Character अंत, अर्थात क्लोजिंग, डिलिमिटर कैरेक्टर को निर्दिष्ट करता है। गणितीय डिलिमिटर वे समापन अक्षर होते हैं जैसे कोष्ठक, ब्रैकेट, और ब्रेस। डिफ़ॉल्ट: ')'।

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

Delimiter Ending Character अंत, अर्थात क्लोजिंग, डिलिमिटर कैरेक्टर को निर्दिष्ट करता है। गणितीय डिलिमिटर वे समापन अक्षर होते हैं जैसे कोष्ठक, ब्रैकेट, और ब्रेस। डिफ़ॉल्ट: ')'।

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

BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि निर्दिष्ट करता है। जब true हो, तो डिलिमिटर ऊर्ध्वाधर रूप से अपने ऑपरेण्ड की ऊँचाई के अनुसार बढ़ता है। डिफ़ॉल्ट मान true है

--------------------

> ```
> उदाहरण:
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

BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि निर्दिष्ट करता है। जब true हो, तो डिलिमिटर ऊर्ध्वाधर रूप से अपने ऑपरेण्ड की ऊँचाई के अनुसार बढ़ता है। डिफ़ॉल्ट मान true है

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

डिलिमिटर ऑब्जेक्ट में डिलिमिटर के आकार को निर्दिष्ट करता है। जब MathDelimiterShape.Centered हो, तो डिलिमिटर गणितीय टेक्स्ट के अक्ष के चारों ओर केंद्रित होते हैं और फिर भी उनकी सामग्री की पूरी ऊँचाई में फिट हो सकते हैं। जब MathDelimiterShape.Match हो, तो उनका आकार और ऊँचाई ठीक उनकी सामग्री के अनुसार बदलता है।

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

डिलिमिटर ऑब्जेक्ट में डिलिमिटर के आकार को निर्दिष्ट करता है। जब MathDelimiterShape.Centered हो, तो डिलिमिटर गणितीय टेक्स्ट के अक्ष के चारों ओर केंद्रित होते हैं और फिर भी उनकी सामग्री की पूरी ऊँचाई में फिट हो सकते हैं। जब MathDelimiterShape.Match हो, तो उनका आकार और ऊँचाई ठीक उनकी सामग्री के अनुसार बदलता है।

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

निर्दिष्ट डिलिमिटर अक्षर का उपयोग करके आर्ग्यूमेंट्स को डिलिमिट करता है

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

निर्दिष्ट अक्षरों (जैसे कोष्ठक या अन्य फ्रेमिंग अक्षर) में एक गणितीय तत्व को लपेटता है

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
| beginningCharacter | char | शुरुआती अक्षर (आमतौर पर बायाँ ब्रैकेट) |
| endingCharacter | char | समाप्ति अक्षर (आमतौर पर दायाँ ब्रैकेट) |

**रिटर्न:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - यदि beginningCharacter और endingCharacter null हैं, तो संबंधित प्रॉपर्टीज़ को केवल मान सौंपा जाता है और कोई नया ऑब्जेक्ट नहीं बनाया जाता (यह instance लौटाता है)। अन्यथा, यह नया गणितीय एलिमेंट Delimiter प्रकार का लौटाता है जिसमें निर्दिष्ट अक्षर फ्रेमिंग के रूप में होते हैं और यह [MathDelimiter](../../com.aspose.slides/mathdelimiter) इंस्टेंस इसमें फ्रेम किया हुआ होता है।

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

चाइल्ड एलिमेंट्स प्राप्त करता है

**रिटर्न:**  
com.aspose.slides.IMathElement[]

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

कंट्रोल कैरेक्टर प्रॉपर्टीज़

**रिटर्न:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps