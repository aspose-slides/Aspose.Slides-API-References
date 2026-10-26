---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Java API संदर्भ
description: Pptx पाठ से HTML निकालने के विकल्प।
type: docs
url: /hi/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Pptx पाठ से HTML निकालने के विकल्प।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | कॉपीबोर्ड हेडर को जोड़ा जाए या नहीं यह दर्शाते हुए मान को प्राप्त या सेट करता है। |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | कॉपीबोर्ड हेडर को जोड़ा जाए या नहीं यह दर्शाते हुए मान को प्राप्त या सेट करता है। |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | टेक्स्ट गुणों के लिए विरासत गहराई को प्राप्त या सेट करता है। |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | टेक्स्ट गुणों के लिए विरासत गहराई को प्राप्त या सेट करता है। |
| [getLinkEmbedController()](#getLinkEmbedController--) | बाहरी वस्तु को कैसे संग्रहीत किया जाएगा, इसे नियंत्रित करने वाला कॉलबैक ऑब्जेक्ट प्राप्त या सेट करता है। |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | बाहरी वस्तु को कैसे संग्रहीत किया जाएगा, इसे नियंत्रित करने वाला कॉलबैक ऑब्जेक्ट प्राप्त या सेट करता है। |
| [getEncodingName()](#getEncodingName--) | HTML एन्कोडिंग नाम को प्राप्त या सेट करता है। |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | HTML एन्कोडिंग नाम को प्राप्त या सेट करता है। |

### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

कॉपीबोर्ड हेडर को जोड़ा जाए या नहीं यह दर्शाते हुए मान को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean

### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

कॉपीबोर्ड हेडर को जोड़ा जाए या नहीं यह दर्शाते हुए मान को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

टेक्स्ट गुणों के लिए विरासत गहराई को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int))।

**रिटर्न:**
int

### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

टेक्स्ट गुणों के लिए विरासत गहराई को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int))।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

बाहरी वस्तु को कैसे संग्रहीत किया जाएगा, इसे नियंत्रित करने वाला कॉलबैक ऑब्जेक्ट प्राप्त या सेट करता है। पढ़ने/लिखने योग्य [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)।

**रिटर्न:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)

### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

बाहरी वस्तु को कैसे संग्रहीत किया जाएगा, इसे नियंत्रित करने वाला कॉलबैक ऑब्जेक्ट प्राप्त या सेट करता है। पढ़ने/लिखने योग्य [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

HTML एन्कोडिंग नाम को प्राप्त या सेट करता है। यह मान जेनरेटेड HTML फ़ाइल में सहेजा जाएगा, लेकिन इसे इस एन्कोडिंग में फ़ाइल को सहेजने की ज़िम्मेदारी कॉलर की है। पढ़ने/लिखने योग्य स्ट्रिंग।

**रिटर्न:**
java.lang.String

### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

HTML एन्कोडिंग नाम को प्राप्त या सेट करता है। यह मान जेनरेटेड HTML फ़ाइल में सहेजा जाएगा, लेकिन इसे इस एन्कोडिंग में फ़ाइल को सहेजने की ज़िम्मेदारी कॉलर की है। पढ़ने/लिखने योग्य स्ट्रिंग।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |