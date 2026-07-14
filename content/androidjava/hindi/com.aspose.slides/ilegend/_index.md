---
title: ILegend
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: चार्ट की लेजेंड गुणधर्म का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ilegend/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

चार्ट की लीजेंड गुणधर्म का प्रतिनिधित्व करता है।
## विधियाँ

| Method | Description |
| --- | --- |
| [getOverlay()](#getOverlay--) | निर्धारित करता है कि अन्य चार्ट तत्वों को लेजेंड के ऊपर ओवरलैप करने की अनुमति दी जानी चाहिए या नहीं। |
| [setOverlay(boolean value)](#setOverlay-boolean-) | निर्धारित करता है कि अन्य चार्ट तत्वों को लेजेंड के ऊपर ओवरलैप करने की अनुमति दी जानी चाहिए या नहीं। |
| [getPosition()](#getPosition--) | चार्ट पर लेजेंड की स्थिति निर्दिष्ट करता है। |
| [setPosition(int value)](#setPosition-int-) | चार्ट पर लेजेंड की स्थिति निर्दिष्ट करता है। |
| [getFormat()](#getFormat--) | लेजेंड का फ़ॉर्मेट लौटाता है। |
| [getEntries()](#getEntries--) | लेजेंड प्रविष्टियों को प्राप्त करता है। |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


निश्चित करता है कि अन्य चार्ट तत्वों को लेजेंड के ऊपर ओवरलैप करने की अनुमति दी जानी चाहिए या नहीं। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


निश्चित करता है कि अन्य चार्ट तत्वों को लेजेंड के ऊपर ओवरलैप करने की अनुमति दी जानी चाहिए या नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


चार्ट पर लेजेंड की स्थिति निर्दिष्ट करता है। X, Y, Width, Height गुणों के Non-NaN मान इस गुण के प्रभाव को ओवरराइड करते हैं। पढ़ें/लिखें [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**रिटर्न:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


चार्ट पर लेजेंड की स्थिति निर्दिष्ट करता है। X, Y, Width, Height गुणों के Non-NaN मान इस गुण के प्रभाव को ओवरराइड करते हैं। पढ़ें/लिखें [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


लेजेंड का फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IFormat](../../com.aspose.slides/iformat).

**रिटर्न:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```


लेजेंड प्रविष्टियों को प्राप्त करता है। केवल-पढ़ने योग्य [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**रिटर्न:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)