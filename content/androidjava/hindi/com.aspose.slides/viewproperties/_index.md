---
title: ViewProperties
second_title: Aspose.Slides के लिए Android में Java API संदर्भ
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

| विधि | वर्णन |
| --- | --- |
| [getLastView()](#getLastView--) | निर्दिष्ट करता है कि प्रस्तुति दस्तावेज़ को अंतिम बार सहेजे जाने पर किस दृश्य मोड का उपयोग किया गया था। |
| [setLastView(int value)](#setLastView-int-) | निर्दिष्ट करता है कि प्रस्तुति दस्तावेज़ को अंतिम बार सहेजे जाने पर किस दृश्य मोड का उपयोग किया गया था। |
| [getShowComments()](#getShowComments--) | निर्दिष्ट करता है कि स्लाइड टिप्पणी दर्शायी जानी चाहिए या नहीं। |
| [setShowComments(byte value)](#setShowComments-byte-) | निर्दिष्ट करता है कि स्लाइड टिप्पणी दर्शायी जानी चाहिए या नहीं। |
| [getNormalViewProperties()](#getNormalViewProperties--) | सामान्य दृश्य गुणों का प्रतिनिधित्व करता है। |
| [getSlideViewProperties()](#getSlideViewProperties--) | स्लाइड दृश्य मोड से जुड़े सामान्य दृश्य गुणों को निर्दिष्ट करता है। |
| [getNotesViewProperties()](#getNotesViewProperties--) | नोट्स दृश्य मोड से जुड़े सामान्य दृश्य गुणों को निर्दिष्ट करता है। |
| [getGridSpacing()](#getGridSpacing--) | ग्रिड स्पेसिंग को लौटाता है या सेट करता है जो प्रस्तुति दस्तावेज़ के नीचे स्थित ग्रिड के लिए उपयोग किया जाना चाहिए, बिंदुओं में। |
| [setGridSpacing(float value)](#setGridSpacing-float-) | ग्रिड स्पेसिंग को लौटाता है या सेट करता है जो प्रस्तुति दस्तावेज़ के नीचे स्थित ग्रिड के लिए उपयोग किया जाना चाहिए, बिंदुओं में। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```

निर्दिष्ट करता है कि प्रस्तुति दस्तावेज़ को अंतिम बार सहेजे जाने पर कौन सा दृश्य मोड उपयोग किया गया था। पढ़ें/लिखें [ViewType](../../com.aspose.slides/viewtype)।

**वापसी:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

निर्दिष्ट करता है कि प्रस्तुति दस्तावेज़ को अंतिम बार सहेजे जाने पर कौन सा दृश्य मोड उपयोग किया गया था। पढ़ें/लिखें [ViewType](../../com.aspose.slides/viewtype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

निर्दिष्ट करता है कि स्लाइड टिप्पणी दर्शायी जानी चाहिए या नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

निर्दिष्ट करता है कि स्लाइड टिप्पणी दर्शायी जानी चाहिए या नहीं। पढ़ें/लिखें [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

सामान्य दृश्य गुणों का प्रतिनिधित्व करता है। सामान्य दृश्य में तीन सामग्री क्षेत्र होते हैं: स्वयं स्लाइड, एक साइड सामग्री क्षेत्र, और एक नीचे का सामग्री क्षेत्र। केवल-पढ़ें [INormalViewProperties](../../com.aspose.slides/inormalviewproperties)।

**वापसी:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

स्लाइड दृश्य मोड से जुड़े सामान्य दृश्य गुणों को निर्दिष्ट करता है। केवल-पढ़ें [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)।

**वापसी:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

नोट्स दृश्य मोड से जुड़े सामान्य दृश्य गुणों को निर्दिष्ट करता है। केवल-पढ़ें [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)।

**वापसी:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

ग्रिड स्पेसिंग को लौटाता है या सेट करता है जो प्रस्तुति दस्तावेज़ के नीचे स्थित ग्रिड के लिए उपयोग किया जाना चाहिए, बिंदुओं में। पढ़ें/लिखें float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
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

ग्रिड स्पेसिंग मान एक सकारात्मक संख्या होना चाहिए। सामान्य मान रेंज 1 mm (2.8349607 बिंदु) से 2 इंच (144 बिंदु) तक है।

**वापसी:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

ग्रिड स्पेसिंग को लौटाता है या सेट करता है जो प्रस्तुति दस्तावेज़ के नीचे स्थित ग्रिड के लिए उपयोग किया जाना चाहिए, बिंदुओं में। पढ़ें/लिखें float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
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

ग्रिड स्पेसिंग मान एक सकारात्मक संख्या होना चाहिए। सामान्य मान रेंज 1 mm (2.8349607 बिंदु) से 2 इंच (144 बिंदु) तक है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट को लौटाता है। केवल-पढ़ें IDOMObject।

**वापसी:**
com.aspose.slides.IDOMObject