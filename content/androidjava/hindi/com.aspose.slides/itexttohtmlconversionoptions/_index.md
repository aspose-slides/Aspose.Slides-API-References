---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Pptx टेक्स्ट से HTML निकालने के विकल्प।
type: docs
url: /hi/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Pptx टेक्स्ट से HTML निकालने के विकल्प।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | वैल्यू को लौटाता या सेट करता है, जो यह दर्शाता है कि क्लिपबोर्ड शीर्षकों को जोड़ा जाना चाहिए। |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | वैल्यू को लौटाता या सेट करता है, जो यह दर्शाता है कि क्लिपबोर्ड शीर्षकों को जोड़ा जाना चाहिए। |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | टेक्स्ट प्रॉपर्टी के लिए इनहेरिटिंग गहराई को लौटाता या सेट करता है। |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | टेक्स्ट प्रॉपर्टी के लिए इनहेरिटिंग गहराई को लौटाता या सेट करता है। |
| [getLinkEmbedController()](#getLinkEmbedController--) | एक कॉलबैक ऑब्जेक्ट को लौटाता या सेट करता है जो नियंत्रित करता है कि बाहरी ऑब्जेक्ट कैसे संग्रहीत किया जाएगा। |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | एक कॉलबैक ऑब्जेक्ट को लौटाता या सेट करता है जो नियंत्रित करता है कि बाहरी ऑब्जेक्ट कैसे संग्रहीत किया जाएगा। |
| [getEncodingName()](#getEncodingName--) | HTML एन्कोडिंग नाम को लौटाता या सेट करता है। |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | HTML एन्कोडिंग नाम को लौटाता या सेट करता है। |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

वैल्यू को लौटाता या सेट करता है, जो यह दर्शाता है कि क्लिपबोर्ड शीर्षकों को जोड़ा जाना चाहिए। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

वैल्यू को लौटाता या सेट करता है, जो यह दर्शाता है कि क्लिपबोर्ड शीर्षकों को जोड़ा जाना चाहिए। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

टेक्स्ट प्रॉपर्टी के लिए इनहेरिटिंग गहराई को लौटाता या सेट करता है। पढ़ें/लिखें [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**रिटर्न:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

टेक्स्ट प्रॉपर्टी के लिए इनहेरिटिंग गहराई को लौटाता या सेट करता है। पढ़ें/लिखें [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

एक कॉलबैक ऑब्जेक्ट को लौटाता या सेट करता है जो नियंत्रित करता है कि बाहरी ऑब्जेक्ट कैसे संग्रहीत किया जाएगा। पढ़ें/लिखें [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**रिटर्न:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

एक कॉलबैक ऑब्जेक्ट को लौटाता या सेट करता है जो नियंत्रित करता है कि बाहरी ऑब्जेक्ट कैसे संग्रहीत किया जाएगा। पढ़ें/लिखें [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

HTML एन्कोडिंग नाम को लौटाता या सेट करता है। यह मान उत्पन्न HTML फ़ाइल में सहेजा जाएगा, लेकिन यह कॉलर की जिम्मेदारी है कि फ़ाइल इस एन्कोडिंग में सहेजी जाए। पढ़ें/लिखें String.

**रिटर्न:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

HTML एन्कोडिंग नाम को लौटाता या सेट करता है। यह मान उत्पन्न HTML फ़ाइल में सहेजा जाएगा, लेकिन यह कॉलर की जिम्मेदारी है कि फ़ाइल इस एन्कोडिंग में सहेजी जाए। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |