---
title: IPortionFormat
second_title: Aspose.Slides for Java API संदर्भ
description: यह क्लास टेक्स्ट पोर्शन फ़ॉर्मैटिंग प्रॉपर्टीज़ शामिल करती है।
type: docs
url: /hi/com.aspose.slides/iportionformat/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

यह क्लास टेक्स्ट पोर्शन फ़ॉर्मैटिंग प्रॉपर्टीज़ शामिल करती है। [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) के विपरीत, इस क्लास की सभी प्रॉपर्टीज़ लिखने योग्य हैं।

--------------------

यह क्लास विशेष पोर्शन के लिए परिभाषित टेक्स्ट पोर्शन फ़ॉर्मैटिंग प्रॉपर्टीज़ को लौटाने और बदलने के लिए उपयोग की जाती है। इसका मतलब है कि मान प्राप्त करते समय कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको मान "अपरिभाषित" मिलेगा।

विरासत सहित प्रभावी फ़ॉर्मैटिंग पैरामीटर मान प्राप्त करने के लिए आपको [getEffective](../../com.aspose.slides/iportionformat\#getEffective) मेथड का उपयोग करना होगा जो एक [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) इंस्टैंस लौटाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | बुकमार्क पहचानकर्ता को प्राप्त या सेट करता है। |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | बुकमार्क पहचानकर्ता को प्राप्त या सेट करता है। |
| [getSmartTagClean()](#getSmartTagClean--) | निर्धारित करता है कि स्मार्ट टैग को साफ़ किया जाना चाहिए या नहीं। |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | निर्धारित करता है कि स्मार्ट टैग को साफ़ किया जाना चाहिए या नहीं। |
| [getEffective()](#getEffective--) | विरासत लागू होने के साथ प्रभावी पोर्शन फ़ॉर्मैटिंग डेटा प्राप्त करता है। |

### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

बुकमार्क पहचानकर्ता को प्राप्त या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

बुकमार्क पहचानकर्ता को प्राप्त या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

निर्धारित करता है कि स्मार्ट टैग को साफ़ किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

निर्धारित करता है कि स्मार्ट टैग को साफ़ किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

विरासत लागू होने के साथ प्रभावी पोर्शन फ़ॉर्मैटिंग डेटा प्राप्त करता है।

**रिटर्न:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - एक [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)।