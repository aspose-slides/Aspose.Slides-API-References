---
title: ViewProperties
second_title: Aspose.Slides के लिए Java API संदर्भ
description: प्रेजेंटेशन-व्यापी दृश्य गुण।
type: docs
url: /hi/com.aspose.slides/viewproperties/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

प्रेजेंटेशन-व्यापी दृश्य गुण।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLastView()](#getLastView--) | उस दृश्य मोड को निर्दिष्ट करता है जो प्रेजेंटेशन दस्तावेज़ को अंतिम बार सहेजा गया था। |
| [setLastView(int value)](#setLastView-int-) | उस दृश्य मोड को निर्दिष्ट करता है जो प्रेजेंटेशन दस्तावेज़ को अंतिम बार सहेजा गया था। |
| [getShowComments()](#getShowComments--) | निर्दिष्ट करता है कि स्लाइड टिप्पणियाँ दिखानी चाहिए या नहीं। |
| [setShowComments(byte value)](#setShowComments-byte-) | निर्दिष्ट करता है कि स्लाइड टिप्पणियाँ दिखानी चाहिए या नहीं। |
| [getNormalViewProperties()](#getNormalViewProperties--) | सामान्य दृश्य गुणों का प्रतिनिधित्व करता है। |
| [getSlideViewProperties()](#getSlideViewProperties--) | स्लाइड दृश्य मोड से जुड़े सामान्य दृश्य गुणों को निर्दिष्ट करता है। |
| [getNotesViewProperties()](#getNotesViewProperties--) | नोट्स दृश्य मोड से जुड़े सामान्य दृश्य गुणों को निर्दिष्ट करता है। |
| [getGridSpacing()](#getGridSpacing--) | प्रेजेंटेशन दस्तावेज़ के अंतर्निहित ग्रिड के लिए उपयोग की जाने वाली ग्रिड स्पेसिंग को पॉइंट में लौटाता या सेट करता है। |
| [setGridSpacing(float value)](#setGridSpacing-float-) | प्रेजेंटेशन दस्तावेज़ के अंतर्निहित ग्रिड के लिए उपयोग की जाने वाली ग्रिड स्पेसिंग को पॉइंट में लौटाता या सेट करता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```

उस दृश्य मोड को निर्दिष्ट करता है जो प्रेजेंटेशन दस्तावेज़ को अंतिम बार सहेजा गया था। पढ़ें/लिखें [ViewType](../../com.aspose.slides/viewtype).

**रिटर्न:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

उस दृश्य मोड को निर्दिष्ट करता है जो प्रेजेंटेशन दस्तावेज़ को अंतिम बार सहेजा गया था। पढ़ें/लिखें [ViewType](../../com.aspose.slides/viewtype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

निर्दिष्ट करता है कि स्लाइड टिप्पणियाँ दिखानी चाहिए या नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**रिटर्न:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

निर्दिष्ट करता है कि स्लाइड टिप्पणियाँ दिखानी चाहिए या नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

सामान्य दृश्य गुणों का प्रतिनिधित्व करता है। सामान्य दृश्य में तीन सामग्री क्षेत्र होते हैं: स्वयं स्लाइड, एक साइड सामग्री क्षेत्र, और एक नीचे का सामग्री क्षेत्र। केवल पढ़ने योग्य [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**रिटर्न:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

स्लाइड दृश्य मोड से जुड़े सामान्य दृश्य गुणों को निर्दिष्ट करता है। केवल पढ़ने योग्य [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**रिटर्न:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

नोट्स दृश्य मोड से जुड़े सामान्य दृश्य गुणों को निर्दिष्ट करता है। केवल पढ़ने योग्य [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**रिटर्न:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

प्रेजेंटेशन दस्तावेज़ के अंतर्निहित ग्रिड के लिए उपयोग की जाने वाली ग्रिड स्पेसिंग को पॉइंट में लौटाता या सेट करता है। पढ़ें/लिखें float.

--------------------

> ```
> निम्नलिखित नमूना कोड PowerPoint प्रस्तुति में ग्रिड स्पेसिंग बदलने का तरीका दिखाता है।
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

ग्रिड स्पेसिंग मान एक सकारात्मक संख्या होना चाहिए। सामान्य मान सीमा 1 मिमी (2.8349607 प्वाइंट) से 2 इंच (144 प्वाइंट) तक होती है।

**रिटर्न:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

प्रेजेंटेशन दस्तावेज़ के अंतर्निहित ग्रिड के लिए उपयोग की जाने वाली ग्रिड स्पेसिंग को पॉइंट में लौटाता या सेट करता है। पढ़ें/लिखें float.

--------------------

> ```
> निम्नलिखित नमूना कोड PowerPoint प्रस्तुति में ग्रिड स्पेसिंग बदलने का तरीका दिखाता है।
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

ग्रिड स्पेसिंग मान एक सकारात्मक संख्या होना चाहिए। सामान्य मान सीमा 1 मिमी (2.8349607 प्वाइंट) से 2 इंच (144 प्वाइंट) तक होती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट को लौटाता है। केवल पढ़ने योग्य IDOMObject।

**रिटर्न:**
com.aspose.slides.IDOMObject