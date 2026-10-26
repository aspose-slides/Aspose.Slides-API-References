---
title: IViewProperties
second_title: Aspose.Slides for Java API Reference
description: Presentation wide view properties.
type: docs
url: /hi/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

प्रस्तुति-व्यापी दृश्य गुण.
## विधियाँ

| Method | Description |
| --- | --- |
| [getLastView()](#getLastView--) | प्रस्तुति दस्तावेज़ को अंतिम बार सहेजा गया था, तब उपयोग किए गए दृश्य मोड को निर्दिष्ट करता है। |
| [setLastView(int value)](#setLastView-int-) | प्रस्तुति दस्तावेज़ को अंतिम बार सहेजा गया था, तब उपयोग किए गए दृश्य मोड को निर्दिष्ट करता है। |
| [getShowComments()](#getShowComments--) | निर्धारित करता है कि स्लाइड टिप्पणियाँ दिखानी चाहिए या नहीं। |
| [setShowComments(byte value)](#setShowComments-byte-) | निर्धारित करता है कि स्लाइड टिप्पणियाँ दिखानी चाहिए या नहीं। |
| [getSlideViewProperties()](#getSlideViewProperties--) | स्लाइड दृश्य मोड से जुड़ी सामान्य दृश्य गुणों को निर्दिष्ट करता है। |
| [getNotesViewProperties()](#getNotesViewProperties--) | नोट्स दृश्य मोड से जुड़ी सामान्य दृश्य गुणों को निर्दिष्ट करता है। |
| [getNormalViewProperties()](#getNormalViewProperties--) | सामान्य दृश्य गुणों को दर्शाता है। |
| [getGridSpacing()](#getGridSpacing--) | प्रस्तुति दस्तावेज़ के नीचे स्थित ग्रिड के लिए उपयोग किए जाने वाले ग्रिड स्पेसिंग को पॉइंट में लौटाता है या सेट करता है। |
| [setGridSpacing(float value)](#setGridSpacing-float-) | प्रस्तुति दस्तावेज़ के नीचे स्थित ग्रिड के लिए उपयोग किए जाने वाले ग्रिड स्पेसिंग को पॉइंट में लौटाता है या सेट करता है। |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```


प्रस्तुति दस्तावेज़ को अंतिम बार सहेजा गया था, तब उपयोग किए गए दृश्य मोड को निर्दिष्ट करता है। पढ़ने/लिखने [ViewType](../../com.aspose.slides/viewtype).

**वापसी:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```


प्रस्तुति दस्तावेज़ को अंतिम बार सहेजा गया था, तब उपयोग किए गए दृश्य मोड को निर्दिष्ट करता है। पढ़ने/लिखने [ViewType](../../com.aspose.slides/viewtype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```


निर्धारित करता है कि स्लाइड टिप्पणियाँ दिखानी चाहिए या नहीं। पढ़ने/लिखने [NullableBool](../../com.aspose.slides/nullablebool).

**वापसी:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```


निर्धारित करता है कि स्लाइड टिप्पणियाँ दिखानी चाहिए या नहीं। पढ़ने/लिखने [NullableBool](../../com.aspose.slides/nullablebool).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```


स्लाइड दृश्य मोड से जुड़ी सामान्य दृश्य गुणों को निर्दिष्ट करता है। केवल पढ़ने के लिए [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**वापसी:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```


नोट्स दृश्य मोड से जुड़ी सामान्य दृश्य गुणों को निर्दिष्ट करता है। केवल पढ़ने के लिए [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**वापसी:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```


सामान्य दृश्य गुणों को दर्शाता है। सामान्य दृश्य में तीन सामग्री क्षेत्र होते हैं: स्वयं स्लाइड, एक साइड सामग्री क्षेत्र, और एक निचला सामग्री क्षेत्र। केवल पढ़ने के लिए [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**वापसी:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```


प्रस्तुति दस्तावेज़ के नीचे स्थित ग्रिड के लिए उपयोग किए जाने वाले ग्रिड स्पेसिंग को पॉइंट में लौटाता है या सेट करता है। पढ़ने/लिखने float.

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

ग्रिड स्पेसिंग मान एक सकारात्मक संख्या होना चाहिए। सामान्य मान श्रेणी 1 मिमी (2.8349607 पॉइंट) से 2 इंच (144 पॉइंट) तक है।

**वापसी:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```


प्रस्तुति दस्तावेज़ के नीचे स्थित ग्रिड के लिए उपयोग किए जाने वाले ग्रिड स्पेसिंग को पॉइंट में लौटाता है या सेट करता है। पढ़ने/लिखने float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>      } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

ग्रिड स्पेसिंग मान एक सकारात्मक संख्या होना चाहिए। सामान्य मान श्रेणी 1 मिमी (2.8349607 पॉइंट) से 2 इंच (144 पॉइंट) तक है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |