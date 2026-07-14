---
title: ILoadOptions
second_title: Aspose.Slides for Android via Java API Reference
description: प्रेज़ेंटेशन लोड करते समय फ़ॉर्मेट या डिफ़ॉल्ट फ़ॉन्ट जैसे अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।
type: docs
url: /hi/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

प्रेज़ेंटेशन लोड करते समय (जैसे फ़ॉर्मेट या डिफ़ॉल्ट फ़ॉन्ट) अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | लोड किए जाने वाले प्रेज़ेंटेशन के फ़ॉर्मेट को प्राप्त करता है या सेट करता है। |
| [setLoadFormat(int value)](#setLoadFormat-int-) | लोड किए जाने वाले प्रेज़ेंटेशन के फ़ॉर्मेट को प्राप्त करता है या सेट करता है। |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले रेगुलर फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले रेगुलर फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले सिंबल फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले सिंबल फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले एशियन फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले एशियन फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| [getPassword()](#getPassword--) | पासवर्ड को प्राप्त करता है या सेट करता है। |
| [setPassword(String value)](#setPassword-java.lang.String-) | पासवर्ड को प्राप्त करता है या सेट करता है। |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | यदि प्रेज़ेंटेशन फ़ाइल पासवर्ड-संरक्षित है तो यह प्रॉपर्टी उपयोगी होती है। |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | यदि प्रेज़ेंटेशन फ़ाइल पासवर्ड-संरक्षित है तो यह प्रॉपर्टी उपयोगी होती है। |
| [getWarningCallback()](#getWarningCallback--) | एक ऑब्जेक्ट को प्राप्त करता है या सेट करता है जो चेतावनियों को प्राप्त करता है और निर्णय लेता है कि लोडिंग प्रक्रिया जारी रहे या रद्द हो। |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | एक ऑब्जेक्ट को प्राप्त करता है या सेट करता है जो चेतावनियों को प्राप्त करता है और निर्णय लेता है कि लोडिंग प्रक्रिया जारी रहे या रद्द हो। |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | विकल्पों को दर्शाता है जो बाइनरी लैर्ज ऑब्जेक्ट्स (BLOBs) के हैंडलिंग व्यवहार को प्रबंधित करने के लिए उपयोग किए जा सकते हैं, जैसे अस्थायी फ़ाइलों का प्रयोग या मेमोरी में अधिकतम BLOB बाइट्स। |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | विकल्पों को दर्शाता है जो बाइनरी लैर्ज ऑब्जेक्ट्स (BLOBs) के हैंडलिंग व्यवहार को प्रबंधित करने के लिए उपयोग किए जा सकते हैं, जैसे अस्थायी फ़ाइलों का प्रयोग या मेमोरी में अधिकतम BLOB बाइट्स। |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | प्रेज़ेंटेशन द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्टों के स्रोत निर्दिष्ट करता है। |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | प्रेज़ेंटेशन द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्टों के स्रोत निर्दिष्ट करता है। |
| [getInterruptionToken()](#getInterruptionToken--) | इंटरप्शन अनुरोधों की निगरानी के लिए टोकन। |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | इंटरप्शन अनुरोधों की निगरानी के लिए टोकन। |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | एक कॉलबैक इंटरफ़ेस को प्राप्त करता है या सेट करता है जो बाहरी संसाधनों के लोडिंग का प्रबंधन करता है। |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | एक कॉलबैक इंटरफ़ेस को प्राप्त करता है या सेट करता है जो बाहरी संसाधनों के लोडिंग का प्रबंधन करता है। |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | विकल्पों को दर्शाता है जो अतिरिक्त स्प्रेडशीट व्यवहार को निर्दिष्ट करने के लिए उपयोग किए जा सकते हैं। |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | विकल्पों को दर्शाता है जो अतिरिक्त स्प्रेडशीट व्यवहार को निर्दिष्ट करने के लिए उपयोग किए जा सकते हैं। |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | प्रेज़ेंटेशन टेक्स्ट के लिए डिफ़ॉल्ट भाषा को प्राप्त करता है या सेट करता है। |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | प्रेज़ेंटेशन टेक्स्ट के लिए डिफ़ॉल्ट भाषा को प्राप्त करता है या सेट करता है। |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | निर्धारित करता है कि प्रेज़ेंटेशन लोड करते समय Aspose.Slides सभी एंबेडेड बाइनरी ऑब्जेक्ट्स को हटाएगा या नहीं। |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | निर्धारित करता है कि प्रेज़ेंटेशन लोड करते समय Aspose.Slides सभी एंबेडेड बाइनरी ऑब्जेक्ट्स को हटाएगा या नहीं। |

### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

लोड किए जाने वाले प्रेज़ेंटेशन के फ़ॉर्मेट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [LoadFormat](../../com.aspose.slides/loadformat)।

**वापसी:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

लोड किए जाने वाले प्रेज़ेंटेशन के फ़ॉर्मेट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [LoadFormat](../../com.aspose.slides/loadformat)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले रेगुलर फ़ॉन्ट को प्राप्त करता है या सेट करता है। पढ़ें-लिखें String।

**वापसी:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले रेगुलर फ़ॉन्ट को प्राप्त करता है या सेट करता है। पढ़ें-लिखें String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले सिंबल फ़ॉन्ट को प्राप्त करता है या सेट करता है। पढ़ें-लिखें String।

**वापसी:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले सिंबल फ़ॉन्ट को प्राप्त करता है या सेट करता है। पढ़ें-लिखें String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले एशियन फ़ॉन्ट को प्राप्त करता है या सेट करता है। पढ़ें-लिखें String।

**वापसी:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले एशियन फ़ॉन्ट को प्राप्त करता है या सेट करता है। पढ़ें-लिखें String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

पासवर्ड को प्राप्त करता है या सेट करता है। पढ़ें-लिखें String।

मान: पासवर्ड।

**वापसी:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

पासवर्ड को प्राप्त करता है या सेट करता है। पढ़ें-लिखें String।

मान: पासवर्ड।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

यदि प्रेज़ेंटेशन फ़ाइल पासवर्ड-संरक्षित है तो यह प्रॉपर्टी उपयोगी होती है। true मान का अर्थ है कि केवल दस्तावेज़ गुण एन्क्रिप्टेड प्रेज़ेंटेशन फ़ाइल से लोड किए जाने चाहिए और पासवर्ड को अनदेखा किया जाना चाहिए। false मान का अर्थ है कि सही पासवर्ड का उपयोग करके पूरी एन्क्रिप्टेड प्रेज़ेंटेशन लोड की जानी चाहिए। यदि प्रेज़ेंटेशन एन्क्रिप्टेड नहीं है तो प्रॉपर्टी मान हमेशा अनदेखा किया जाता है। यदि एन्क्रिप्टेड फ़ाइल के दस्तावेज़ गुण सार्वजनिक नहीं हैं और प्रॉपर्टी मान true है तो दस्तावेज़ गुण लोड नहीं किए जा सकते और अपवाद उत्पन्न होगा। पढ़ें-लिखें boolean।

**वापसी:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

यदि प्रेज़ेंटेशन फ़ाइल पासवर्ड-संरक्षित है तो यह प्रॉपर्टी उपयोगी होती है। true मान का अर्थ है कि केवल दस्तावेज़ गुण एन्क्रिप्टेड प्रेज़ेंटेशन फ़ाइल से लोड किए जाने चाहिए और पासवर्ड को अनदेखा किया जाना चाहिए। false मान का अर्थ है कि सही पासवर्ड का उपयोग करके पूरी एन्क्रिप्टेड प्रेज़ेंटेशन लोड की जानी चाहिए। यदि प्रेज़ेंटेशन एन्क्रिप्टेड नहीं है तो प्रॉपर्टी मान हमेशा अनदेखा किया जाता है। यदि एन्क्रिप्टेड फ़ाइल के दस्तावेज़ गुण सार्वजनिक नहीं हैं और प्रॉपर्टी मान true है तो दस्तावेज़ गुण लोड नहीं किए जा सकते और अपवाद उत्पन्न होगा। पढ़ें-लिखें boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

चेतावनियों को प्राप्त करने वाले और यह तय करने वाले ऑब्जेक्ट को प्राप्त करता है या सेट करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द होगी। पढ़ें/लिखें [IWarningCallback](../../com.aspose.slides/iwarningcallback)।

**वापसी:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

चेतावनियों को प्राप्त करने वाले और यह तय करने वाले ऑब्जेक्ट को प्राप्त करता है या सेट करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द होगी। पढ़ें/लिखें [IWarningCallback](../../com.aspose.slides/iwarningcallback)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

विकल्पों को दर्शाता है जो बाइनरी लैर्ज ऑब्जेक्ट्स (BLOBs) के हैंडलिंग व्यवहार को प्रबंधित करने के लिए उपयोग किए जा सकते हैं, जैसे अस्थायी फ़ाइलों का प्रयोग या मेमोरी में अधिकतम BLOB बाइट्स। ये विकल्प किसी विशेष वातावरण या आवश्यकताओं के लिए सर्वश्रेष्ठ प्रदर्शन/मेमोरी उपयोग अनुपात सेट करने के लिये नियत किए गए हैं।

--------------------

एक बाइनरी लैर्ज ऑब्जेक्ट (BLOB) एक बाइनरी डेटा है जो एक इकाई के रूप में संग्रहीत होता है - अर्थात् BLOB एक ऑडियो, वीडियो या स्वयं प्रेज़ेंटेशन हो सकता है।

**वापसी:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

विकल्पों को दर्शाता है जो बाइनरी लैर्ज ऑब्जेक्ट्स (BLOBs) के हैंडलिंग व्यवहार को प्रबंधित करने के लिए उपयोग किए जा सकते हैं, जैसे अस्थायी फ़ाइलों का प्रयोग या मेमोरी में अधिकतम BLOB बाइट्स। ये विकल्प किसी विशेष वातावरण या आवश्यकताओं के लिए सर्वश्रेष्ठ प्रदर्शन/मेमोरी उपयोग अनुपात सेट करने के लिये नियत किए गए हैं।

--------------------

एक बाइनरी लैर्ज ऑब्जेक्ट (BLOB) एक बाइनरी डेटा है जो एक इकाई के रूप में संग्रहीत होता है - अर्थात् BLOB एक ऑडियो, वीडियो या स्वयं प्रेज़ेंटेशन हो सकता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

प्रेज़ेंटेशन द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्टों के स्रोत निर्दिष्ट करता है। ये फ़ॉन्ट पूरे प्रेज़ेंटेशन के जीवनकाल में उपलब्ध होते हैं और अन्य प्रेज़ेंटेशन के साथ साझा नहीं होते।

**वापसी:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

प्रेज़ेंटेशन द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्टों के स्रोत निर्दिष्ट करता है। ये फ़ॉन्ट पूरे प्रेज़ेंटेशन के जीवनकाल में उपलब्ध होते हैं और अन्य प्रेज़ेंटेशन के साथ साझा नहीं होते।

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

यह टोकन पूरे [IPresentation](../../com.aspose.slides/ipresentation) इंस्टेंस के जीवनकाल का प्रबंधन करता है। कोई भी दीर्घकालिक ऑपरेशन, जैसे प्रेज़ेंटेशन लोडिंग या सहेजना, [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) के [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) मेथड को कॉल करके बाधित किया जाएगा।

**वापसी:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

इंटरप्शन अनुरोधों की निगरानी के लिए टोकन।

--------------------

यह टोकन पूरे [IPresentation](../../com.aspose.slides/ipresentation) इंस्टेंस के जीवनकाल का प्रबंधन करता है। कोई भी दीर्घकालिक ऑपरेशन, जैसे प्रेज़ेंटेशन लोडिंग या सहेजना, [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) के [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) मेथड को कॉल करके बाधित किया जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

एक कॉलबैक इंटरफ़ेस को प्राप्त करता है या सेट करता है जो बाहरी संसाधनों के लोडिंग का प्रबंधन करता है। पढ़ें/लिखें [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)।

**वापसी:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

एक कॉलबैक इंटरफ़ेस को प्राप्त करता है या सेट करता है जो बाहरी संसाधनों के लोडिंग का प्रबंधन करता है। पढ़ें/लिखें [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

विकल्पों को दर्शाता है जो अतिरिक्त स्प्रेडशीट व्यवहार को निर्दिष्ट करने के लिए उपयोग किए जा सकते हैं।

**वापसी:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

विकल्पों को दर्शाता है जो अतिरिक्त स्प्रेडशीट व्यवहार को निर्दिष्ट करने के लिए उपयोग किए जा सकते हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

प्रेज़ेंटेशन टेक्स्ट के लिए डिफ़ॉल्ट भाषा को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String।

--------------------

> ```
> Example:
>   
>  // लोड विकल्पों का उपयोग करके डिफ़ॉल्ट टेक्स्ट संस्कृति निर्धारित करें
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // टेक्स्ट के साथ नया आयत आकार जोड़ें
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // पहले पोर्शन की भाषा जाँचें
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```

प्रेज़ेंटेशन टेक्स्ट के लिए डिफ़ॉल्ट भाषा को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String।

--------------------

> ```
> Example:
>   
>  // लोड विकल्पों का उपयोग करके डिफ़ॉल्ट टेक्स्ट संस्कृति निर्धारित करें
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // टेक्स्ट के साथ नया आयताकार आकार जोड़ें
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // पहले पोर्शन की भाषा जाँचें
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

निर्धारित करता है कि प्रेज़ेंटेशन लोड करते समय Aspose.Slides सभी एंबेडेड बाइनरी ऑब्जेक्ट्स को हटाएगा या नहीं।

एंबेडेड बाइनरी ऑब्जेक्ट्स के प्रकार:
 *  
 *  
 *  

पढ़ें/लिखें  boolean।

--------------------

> ```
> निम्न उदाहरण दिखाता है कि कैसे प्रेज़ेंटेशन को बिना किसी एंबेडेड बाइनरी ऑब्जेक्ट के लोड किया जाए।
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

डिफ़ॉल्ट है  **false**।

**वापसी:**
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

निर्धारित करता है कि प्रेज़ेंटेशन लोड करते समय Aspose.Slides सभी एंबेडेड बाइनरी ऑब्जेक्ट्स को हटाएगा या नहीं।

एंबेडेड बाइनरी ऑब्जेक्ट्स के प्रकार:
 *  
 *  
 *  

पढ़ें/लिखें  boolean।

--------------------

> ```
> निम्न उदाहरण दिखाता है कि कैसे प्रेज़ेंटेशन को बिना किसी एंबेडेड बाइनरी ऑब्जेक्ट्स के लोड किया जाए।
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

डिफ़ॉल्ट है  **false**।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |