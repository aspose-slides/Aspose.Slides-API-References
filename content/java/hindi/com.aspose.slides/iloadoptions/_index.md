---
title: ILoadOptions
second_title: Aspose.Slides for Java API Reference
description: Allows to specify additional options such as format or default font when loading a presentation.
type: docs
url: /hi/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

प्रेजेंटेशन लोड करते समय अतिरिक्त विकल्प (जैसे फ़ॉर्मेट या डिफ़ॉल्ट फ़ॉन्ट) निर्दिष्ट करने की अनुमति देता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | लोड करने के लिए प्रेजेंटेशन के फ़ॉर्मेट को प्राप्त करता है या सेट करता है। |
| [setLoadFormat(int value)](#setLoadFormat-int-) | लोड करने के लिए प्रेजेंटेशन के फ़ॉर्मेट को प्राप्त करता है या सेट करता है। |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले नियमित फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले नियमित फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले सिम्बॉल फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले सिम्बॉल फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले एशियन फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले एशियन फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| [getPassword()](#getPassword--) | पासवर्ड को प्राप्त करता है या सेट करता है। |
| [setPassword(String value)](#setPassword-java.lang.String-) | पासवर्ड को प्राप्त करता है या सेट करता है। |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | यदि प्रेजेंटेशन फ़ाइल पासवर्ड संरक्षित है, तो यह प्रॉपर्टी मायने रखती है। |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | यदि प्रेजेंटेशन फ़ाइल पासवर्ड संरक्षित है, तो यह प्रॉपर्टी मायने रखती है। |
| [getWarningCallback()](#getWarningCallback--) | एक ऑब्जेक्ट को प्राप्त करता है या सेट करता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त की जाएगी। |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | एक ऑब्जेक्ट को प्राप्त करता है या सेट करता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त की जाएगी। |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | विकल्पों का प्रतिनिधित्व करता है जो बाइनरी बड़े ऑब्जेक्ट्स (BLOBs) को संभालने के व्यवहार को प्रबंधित करने के लिए उपयोग किए जा सकते हैं, जैसे कि अस्थायी फ़ाइलों का उपयोग या मेमोरी में अधिकतम BLOB बाइट्स। |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | विकल्पों का प्रतिनिधित्व करता है जो बाइनरी बड़े ऑब्जेक्ट्स (BLOBs) को संभालने के व्यवहार को प्रबंधित करने के लिए उपयोग किए जा सकते हैं, जैसे कि अस्थायी फ़ाइलों का उपयोग या मेमोरी में अधिकतम BLOB बाइट्स। |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | प्रेजेंटेशन द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्ट्स के स्रोत निर्दिष्ट करता है। |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | प्रेजेंटेशन द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्ट्स के स्रोत निर्दिष्ट करता है। |
| [getInterruptionToken()](#getInterruptionToken--) | इंटरप्शन अनुरोधों की निगरानी के लिए टोकन। |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | इंटरप्शन अनुरोधों की निगरानी के लिए टोकन। |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | एक कॉलबैक इंटरफ़ेस को प्राप्त करता है या सेट करता है जो बाहरी संसाधनों के लोडिंग को प्रबंधित करता है। |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | एक कॉलबैक इंटरफ़ेस को प्राप्त करता है या सेट करता है जो बाहरी संसाधनों के लोडिंग को प्रबंधित करता है। |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | विकल्पों का प्रतिनिधित्व करता है जो अतिरिक्त स्प्रेडशीट व्यवहार को निर्दिष्ट करने के लिए उपयोग किए जा सकते हैं। |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | विकल्पों का प्रतिनिधित्व करता है जो अतिरिक्त स्प्रेडशीट व्यवहार को निर्दिष्ट करने के लिए उपयोग किए जा सकते हैं। |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | प्रेजेंटेशन पाठ के लिए डिफ़ॉल्ट भाषा को प्राप्त करता है या सेट करता है। |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | प्रेजेंटेशन पाठ के लिए डिफ़ॉल्ट भाषा को प्राप्त करता है या सेट करता है। |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | निर्धारित करता है कि Aspose.Slides प्रेजेंटेशन लोड करते समय सभी एम्बेडेड बाइनरी ऑब्जेक्ट्स को डिलीट करेगा या नहीं। |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | निर्धारित करता है कि Aspose.Slides प्रेजेंटेशन लोड करते समय सभी एम्बेडेड बाइनरी ऑब्जेक्ट्स को डिलीट करेगा या नहीं। |

### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

लोड करने के लिए प्रेजेंटेशन के फ़ॉर्मेट को प्राप्त करता है या सेट करता है। Read/write [LoadFormat](../../com.aspose.slides/loadformat).

**रिटर्न:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

लोड करने के लिए प्रेजेंटेशन के फ़ॉर्मेट को प्राप्त करता है या सेट करता है। Read/write [LoadFormat](../../com.aspose.slides/loadformat).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले नियमित फ़ॉन्ट को प्राप्त करता है या सेट करता है। Read-write String.

**रिटर्न:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले नियमित फ़ॉन्ट को प्राप्त करता है या सेट करता है। Read-write String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले सिम्बॉल फ़ॉन्ट को प्राप्त करता है या सेट करता है। Read-write String.

**रिटर्न:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले सिम्बॉल फ़ॉन्ट को प्राप्त करता है या सेट करता है। Read-write String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले एशियन फ़ॉन्ट को प्राप्त करता है या सेट करता है। Read-write String.

**रिटर्न:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले एशियन फ़ॉन्ट को प्राप्त करता है या सेट करता है। Read-write String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

पासवर्ड को प्राप्त करता है या सेट करता है। Read-write String.

मान: पासवर्ड।

**रिटर्न:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

पासवर्ड को प्राप्त करता है या सेट करता है। Read-write String.

मान: पासवर्ड।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

यदि प्रेजेंटेशन फ़ाइल पासवर्ड संरक्षित है, तो यह प्रॉपर्टी मायने रखती है। true का मान मतलब है कि एन्क्रिप्टेड फ़ाइल से केवल दस्तावेज़ गुण लोड किए जाएंगे और पासवर्ड को अनदेखा किया जाएगा। false का मान मतलब है कि सही पासवर्ड का उपयोग करके पूरा एन्क्रिप्टेड प्रेजेंटेशन लोड किया जाएगा। यदि प्रेजेंटेशन एन्क्रिप्टेड नहीं है तो यह प्रॉपर्टी हमेशा अनदेखी की जाती है। यदि एन्क्रिप्टेड फ़ाइल के दस्तावेज़ गुण सार्वजनिक नहीं हैं और प्रॉपर्टी का मान true है तो दस्तावेज़ गुण लोड नहीं किए जा सकते और अपवाद फेंका जाएगा। Read-write boolean।

**रिटर्न:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

यदि प्रेजेंटेशन फ़ाइल पासवर्ड संरक्षित है, तो यह प्रॉपर्टी मायने रखती है। true का मान मतलब है कि एन्क्रिप्टेड फ़ाइल से केवल दस्तावेज़ गुण लोड किए जाएंगे और पासवर्ड को अनदेखा किया जाएगा। false का मान मतलब है कि सही पासवर्ड का उपयोग करके पूरा एन्क्रिप्टेड प्रेजेंटेशन लोड किया जाएगा। यदि प्रेजेंटेशन एन्क्रिप्टेड नहीं है तो यह प्रॉपर्टी हमेशा अनदेखी की जाती है। यदि एन्क्रिप्टेड फ़ाइल के दस्तावेज़ गुण सार्वजनिक नहीं हैं और प्रॉपर्टी का मान true है तो दस्तावेज़ गुण लोड नहीं किए जा सकते और अपवाद फेंका जाएगा। Read-write boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

एक ऑब्जेक्ट को प्राप्त करता है या सेट करता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त की जाएगी। Read/write [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**रिटर्न:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

एक ऑब्जेक्ट को प्राप्त करता है या सेट करता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त की जाएगी। Read/write [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

विकल्पों का प्रतिनिधित्व करता है जो बाइनरी बड़े ऑब्जेक्ट्स (BLOBs) को संभालने के व्यवहार को प्रबंधित करने के लिए उपयोग किए जा सकते हैं, जैसे कि अस्थायी फ़ाइलों का उपयोग या मेमोरी में अधिकतम BLOB बाइट्स। ये विकल्प विशेष वातावरण या आवश्यकताओं के लिए सर्वोत्तम प्रदर्शन/मेमोरी उपयोग अनुपात स्थापित करने के लिए अभिप्रेत हैं।

--------------------

एक बाइनरी बड़ा ऑब्जेक्ट (BLOB) एक बाइनरी डेटा है जो एक ही इकाई के रूप में संग्रहीत होता है - यानी BLOB ऑडियो, वीडियो या स्वयं प्रेजेंटेशन हो सकता है।

**रिटर्न:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

विकल्पों का प्रतिनिधित्व करता है जो बाइनरी बड़े ऑब्जेक्ट्स (BLOBs) को संभालने के व्यवहार को प्रबंधित करने के लिए उपयोग किए जा सकते हैं, जैसे कि अस्थायी फ़ाइलों का उपयोग या मेमोरी में अधिकतम BLOB बाइट्स। ये विकल्प विशेष वातावरण या आवश्यकताओं के लिए सर्वोत्तम प्रदर्शन/मेमोरी उपयोग अनुपात स्थापित करने के लिए अभिप्रेत हैं।

--------------------

एक बाइनरी बड़ा ऑब्जेक्ट (BLOB) एक बाइनरी डेटा है जो एक ही इकाई के रूप में संग्रहीत होता है - यानी BLOB ऑडियो, वीडियो या स्वयं प्रेजेंटेशन हो सकता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

प्रेजेंटेशन द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्ट्स के स्रोत निर्दिष्ट करता है। ये फ़ॉन्ट्स प्रेजेंटेशन के पूरा जीवनकाल में उपलब्ध रहते हैं और अन्य प्रेजेंटेशनों के साथ साझा नहीं होते।

**रिटर्न:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

प्रेजेंटेशन द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्ट्स के स्रोत निर्दिष्ट करता है। ये फ़ॉन्ट्स प्रेजेंटेशन के पूरा जीवनकाल में उपलब्ध रहते हैं और अन्य प्रेजेंटेशनों के साथ साझा नहीं होते।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

इंटरप्शन अनुरोधों की निगरानी के लिए टोकन।

--------------------

यह टोकन पूरे [IPresentation](../../com.aspose.slides/ipresentation) इंस्टेंस जीवनकाल का प्रबंधन करता है। कोई भी दीर्घकालिक ऑपरेशन, जैसे प्रेजेंटेशन लोडिंग या सेविंग, [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) मेथड को [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) के माध्यम से कॉल करके बाधित किया जाएगा।

**रिटर्न:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

इंटरप्शन अनुरोधों की निगरानी के लिए टोकन।

--------------------

यह टोकन पूरे [IPresentation](../../com.aspose.slides/ipresentation) इंस्टेंस जीवनकाल का प्रबंधन करता है। कोई भी दीर्घकालिक ऑपरेशन, जैसे प्रेजेंटेशन लोडिंग या सेविंग, [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) मेथड को [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) के माध्यम से कॉल करके बाधित किया जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

एक कॉलबैक इंटरफ़ेस को प्राप्त करता है या सेट करता है जो बाहरी संसाधनों के लोडिंग को प्रबंधित करता है। Read/write [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**रिटर्न:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

एक कॉलबैक इंटरफ़ेस को प्राप्त करता है या सेट करता है जो बाहरी संसाधनों के लोडिंग को प्रबंधित करता है। Read/write [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

विकल्पों का प्रतिनिधित्व करता है जो अतिरिक्त स्प्रेडशीट व्यवहार को निर्दिष्ट करने के लिए उपयोग किए जा सकते हैं।

**रिटर्न:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

विकल्पों का प्रतिनिधित्व करता है जो अतिरिक्त स्प्रेडशीट व्यवहार को निर्दिष्ट करने के लिए उपयोग किए जा सकते हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

प्रेजेंटेशन पाठ के लिए डिफ़ॉल्ट भाषा को प्राप्त करता है या सेट करता है। Read/write String.

--------------------

> ```
> Example:
>   
>  // लोड विकल्पों का उपयोग करके डिफ़ॉल्ट टेक्स्ट संस्कृति निर्धारित करें
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // नया आयताकार आकार टेक्स्ट के साथ जोड़ें
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // पहले भाग की भाषा जांचें
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```

प्रेजेंटेशन पाठ के लिए डिफ़ॉल्ट भाषा को प्राप्त करता है या सेट करता है। Read/write String.

--------------------

> ```
> Example:
>   
>  // लोड विकल्पों का उपयोग करके डिफ़ॉल्ट टेक्स्ट संस्कृति निर्धारित करें
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // नया आयताकार आकार टेक्स्ट के साथ जोड़ें
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // पहले भाग की भाषा जांचें
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

निर्धारित करता है कि Aspose.Slides प्रेजेंटेशन लोड करते समय सभी एम्बेडेड बाइनरी ऑब्जेक्ट्स को डिलीट करेगा या नहीं।

एम्बेडेड बाइनरी ऑब्जेक्ट्स के प्रकार:

 *  
 *  
 *  

Read/write boolean .

--------------------

> ```
> निम्न उदाहरण दिखाता है कि कैसे प्रेज़ेंटेशन को बिना किसी एम्बेडेड बाइनरी ऑब्जेक्ट्स के लोड किया जाए।
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

डिफ़ॉल्ट **false** है।

**रिटर्न:**
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

निर्धारित करता है कि Aspose.Slides प्रेजेंटेशन लोड करते समय सभी एम्बेडेड बाइनरी ऑब्जेक्ट्स को डिलीट करेगा या नहीं।

एम्बेडेड बाइनरी ऑब्जेक्ट्स के प्रकार:

 *  
 *  
 *  

Read/write boolean .

--------------------

> ```
> निम्न उदाहरण दिखाता है कि कैसे प्रेज़ेंटेशन को बिना किसी एम्बेडेड बाइनरी ऑब्जेक्ट्स के लोड किया जाए।
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

डिफॉल्ट **false** है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |