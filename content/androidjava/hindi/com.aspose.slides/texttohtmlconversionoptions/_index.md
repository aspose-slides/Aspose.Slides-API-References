---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: Pptx पाठ से HTML निकालने के विकल्प।
type: docs
url: /hi/com.aspose.slides/texttohtmlconversionoptions/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

Pptx पाठ से HTML निकालने के विकल्प।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | मान लौटाता या सेट करता है, जो यह दर्शाता है कि Clipboard हेडर जोड़ें जाएँ या नहीं। |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | मान लौटाता या सेट करता है, जो यह दर्शाता है कि Clipboard हेडर जोड़ें जाएँ या नहीं। |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | पाठ गुणों के लिए विरासत गहराई लौटाता या सेट करता है। |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | पाठ गुणों के लिए विरासत गहराई लौटाता या सेट करता है। |
| [getLinkEmbedController()](#getLinkEmbedController--) | एक कॉलबैक ऑब्जेक्ट लौटाता या सेट करता है जो नियंत्रित करता है कि बाहरी ऑब्जेक्ट कैसे संग्रहीत किया जाएगा। |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | एक कॉलबैक ऑब्जेक्ट लौटाता या सेट करता है जो नियंत्रित करता है कि बाहरी ऑब्जेक्ट कैसे संग्रहीत किया जाएगा। |
| [getEncodingName()](#getEncodingName--) | HTML एन्कोडिंग नाम लौटाता या सेट करता है। |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | HTML एन्कोडिंग नाम लौटाता या सेट करता है। |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


मान लौटाता या सेट करता है, जो यह दर्शाता है कि Clipboard हेडर जोड़ें जाएँ या नहीं। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


मान लौटाता या सेट करता है, जो यह दर्शाता है कि Clipboard हेडर जोड़ें जाएँ या नहीं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


पाठ गुणों के लिए विरासत गहराई लौटाता या सेट करता है। पढ़ने/लिखने योग्य [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)।

**रिटर्न:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


पाठ गुणों के लिए विरासत गहराई लौटाता या सेट करता है। पढ़ने/लिखने योग्य [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


एक कॉलबैक ऑब्जेक्ट लौटाता या सेट करता है जो नियंत्रित करता है कि बाहरी ऑब्जेक्ट कैसे संग्रहीत किया जाएगा। पढ़ने/लिखने योग्य [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)।

**रिटर्न:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


एक कॉलबैक ऑब्जेक्ट लौटाता या सेट करता है जो नियंत्रित करता है कि बाहरी ऑब्जेक्ट कैसे संग्रहीत किया जाएगा। पढ़ने/लिखने योग्य [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


HTML एन्कोडिंग नाम लौटाता या सेट करता है। यह मान उत्पन्न HTML फ़ाइल में सहेजा जाएगा, लेकिन फ़ाइल को इस एन्कोडिंग में सहेजने की जिम्मेदारी कॉलर की होगी। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


HTML एन्कोडिंग नाम लौटाता या सेट करता है। यह मान उत्पन्न HTML फ़ाइल में सहेजा जाएगा, लेकिन फ़ाइल को इस एन्कोडिंग में सहेजने की जिम्मेदारी कॉलर की होगी। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |