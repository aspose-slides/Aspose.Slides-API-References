---
title: IViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Presentation wide view properties.
type: docs
url: /hi/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

प्रेज़ेंटेशन-व्यापी दृश्य गुण।

## विधियाँ

| Method | Description |
| --- | --- |
| [getLastView()](#getLastView--) | वह व्यू मोड निर्दिष्ट करता है जो प्रेज़ेंटेशन दस्तावेज़ को अंतिम बार सहेजा गया था। |
| [setLastView(int value)](#setLastView-int-) | वह व्यू मोड निर्दिष्ट करता है जो प्रेज़ेंटेशन दस्तावेज़ को अंतिम बार सहेजा गया था। |
| [getShowComments()](#getShowComments--) | यह निर्दिष्ट करता है कि स्लाइड टिप्पणी प्रदर्शित की जानी चाहिए या नहीं। |
| [setShowComments(byte value)](#setShowComments-byte-) | यह निर्दिष्ट करता है कि स्लाइड टिप्पणी प्रदर्शित की जानी चाहिए या नहीं। |
| [getSlideViewProperties()](#getSlideViewProperties--) | स्लाइड व्यू मोड से जुड़े सामान्य दृश्य गुण निर्दिष्ट करता है। |
| [getNotesViewProperties()](#getNotesViewProperties--) | नोट्स व्यू मोड से जुड़े सामान्य दृश्य गुण निर्दिष्ट करता है। |
| [getNormalViewProperties()](#getNormalViewProperties--) | सामान्य दृश्य गुणों का प्रतिनिधित्व करता है। |
| [getGridSpacing()](#getGridSpacing--) | प्रेज़ेंटेशन दस्तावेज़ के नीचे के ग्रिड के लिए उपयोग किए जाने वाले ग्रिड स्पेसिंग को पॉइंट में प्राप्त या सेट करता है। |
| [setGridSpacing(float value)](#setGridSpacing-float-) | प्रेज़ेंटेशन दस्तावेज़ के नीचे के ग्रिड के लिए उपयोग किए जाने वाले ग्रिड स्पेसिंग को पॉइंट में प्राप्त या सेट करता है। |

### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

वह व्यू मोड निर्दिष्ट करता है जो प्रेज़ेंटेशन दस्तावेज़ को अंतिम बार सहेजा गया था। पढ़ने/लिखने योग्य [ViewType](../../com.aspose.slides/viewtype)।

**वापसी:**
int

### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

वह व्यू मोड निर्दिष्ट करता है जो प्रेज़ेंटेशन दस्तावेज़ को अंतिम बार सहेजा गया था। पढ़ने/लिखने योग्य [ViewType](../../com.aspose.slides/viewtype)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

निर्दिष्ट करता है कि स्लाइड टिप्पणी प्रदर्शित की जानी चाहिए या नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**वापसी:**
byte

### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

निर्दिष्ट करता है कि स्लाइड टिप्पणी प्रदर्शित की जानी चाहिए या नहीं। पढ़ने/लिखने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

स्लाइड व्यू मोड से जुड़े सामान्य दृश्य गुण निर्दिष्ट करता है। केवल पढ़ने योग्य [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)।

**वापसी:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

नोट्स व्यू मोड से जुड़े सामान्य दृश्य गुण निर्दिष्ट करता है। केवल पढ़ने योग्य [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)।

**वापसी:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

सामान्य दृश्य गुणों का प्रतिनिधित्व करता है। सामान्य दृश्य में तीन सामग्री क्षेत्र होते हैं: स्वयं स्लाइड, एक साइड कंटेंट रीजन, और एक बॉटम कंटेंट रीजन। केवल पढ़ने योग्य [INormalViewProperties](../../com.aspose.slides/inormalviewproperties)।

**वापसी:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)

### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

प्रेज़ेंटेशन दस्तावेज़ के नीचे के ग्रिड के लिए उपयोग किए जाने वाले ग्रिड स्पेसिंग को पॉइंट में प्राप्त या सेट करता है। पढ़ने/लिखने योग्य float।

--------------------

> ```
> निम्नलिखित नमूना कोड दिखाता है कि PowerPoint प्रस्तुति में ग्रिड स्पेसिंग कैसे बदलें।
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

ग्रिड स्पेसिंग मान एक सकारात्मक संख्या होना चाहिए। सामान्य मान सीमा 1 mm (2.8349607 पॉइंट) से 2 इंच (144 पॉइंट) तक होती है।

**वापसी:**
float

### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

प्रेज़ेंटेशन दस्तावेज़ के नीचे के ग्रिड के लिए उपयोग किए जाने वाले ग्रिड स्पेसिंग को पॉइंट में प्राप्त या सेट करता है। पढ़ने/लिखने योग्य float।

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

ग्रिड स्पेसिंग मान एक सकारात्मक संख्या होना चाहिए। सामान्य मान सीमा 1 mm (2.8349607 पॉइंट) से 2 इंच (144 पॉइंट) तक होती है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |