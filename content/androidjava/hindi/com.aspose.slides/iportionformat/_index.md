---
title: IPortionFormat
second_title: Aspose.Slides एंड्रॉइड के लिए जावा API संदर्भ के माध्यम से
description: यह वर्ग पाठ भाग फ़ॉर्मेटिंग गुणों को शामिल करता है।
type: docs
url: /hi/com.aspose.slides/iportionformat/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

यह कक्षा पाठ भाग फ़ॉर्मेटिंग गुणों को शामिल करती है। [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) के विरुद्ध, इस कक्षा के सभी गुण लिखने योग्य हैं।

--------------------

यह कक्षा किसी विशेष भाग के लिए निर्धारित पाठ भाग फ़ॉर्मेटिंग गुणों को लौटाने और संशोधित करने के लिए उपयोग की जाती है। इसका अर्थ है कि मान प्राप्त करते समय कोई उत्तराधिकार लागू नहीं होता, इसलिए अधिकांश मामलों में आपको मान “अनिर्दिष्ट” मिलेंगे।

विरासत सहित प्रभावी फ़ॉर्मेटिंग पैरामीटर मान प्राप्त करने के लिए आपको [getEffective](../../com.aspose.slides/iportionformat\#getEffective) मेथड का उपयोग करना चाहिए जो एक [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) इंस्टेंस लौटाता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | बुकमार्क पहचानकर्ता को लौटाता है या सेट करता है। |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | बुकमार्क पहचानकर्ता को लौटाता है या सेट करता है। |
| [getSmartTagClean()](#getSmartTagClean--) | निर्धारित करता है कि स्मार्ट टैग को साफ़ किया जाना चाहिए या नहीं। |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | निर्धारित करता है कि स्मार्ट टैग को साफ़ किया जाना चाहिए या नहीं। |
| [getEffective()](#getEffective--) | उत्तराधिकार लागू होने पर प्रभावी भाग फ़ॉर्मेटिंग डेटा प्राप्त करता है। |

### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

बुकमार्क पहचानकर्ता को लौटाता है या सेट करता है। पढ़ें/लिखें String.

**वापसी:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

बुकमार्क पहचानकर्ता को लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

निर्धारित करता है कि स्मार्ट टैग को साफ़ किया जाना चाहिए या नहीं। कोई उत्तराधिकार लागू नहीं। पढ़ें/लिखें boolean.

**वापसी:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

निर्धारित करता है कि स्मार्ट टैग को साफ़ किया जाना चाहिए या नहीं। कोई उत्तराधिकार लागू नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

उत्तराधिकार लागू होने पर प्रभावी भाग फ़ॉर्मेटिंग डेटा प्राप्त करता है।

**वापसी:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).