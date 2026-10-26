---
title: IPictureFrame
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: एक फ्रेम का प्रतिनिधित्व करता है जिसमें अंदर एक तस्वीर है।
type: docs
url: /hi/com.aspose.slides/ipictureframe/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

एक फ्रेम का प्रतिनिधित्व करता है जिसमें अंदर एक तस्वीर है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | PictureFrame's locks लौटाता है। |
| [getPictureFormat()](#getPictureFormat--) | PictureFillFormat ऑब्जेक्ट एक picture frame के लिए लौटाता है। |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | picture frame की ऊँचाई (relative to original picture size) का स्केल लौटाता है या सेट करता है। |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | picture frame की ऊँचाई (relative to original picture size) का स्केल लौटाता है या सेट करता है। |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | picture frame की चौड़ाई (relative to original picture size) का स्केल लौटाता है या सेट करता है। |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | picture frame की चौड़ाई (relative to original picture size) का स्केल लौटाता है या सेट करता है। |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```

PictureFrame's locks लौटाता है। केवल-पढ़ने योग्य [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**रिटर्न:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```

PictureFillFormat ऑब्जेक्ट एक picture frame के लिए लौटाता है। केवल-पढ़ने योग्य [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**रिटर्न:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```

picture frame की ऊँचाई (relative to original picture size) का स्केल लौटाता है या सेट करता है। मान 1.0 100% के बराबर है। पढ़ने/लिखने योग्य float।

**रिटर्न:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```

picture frame की ऊँचाई (relative to original picture size) का स्केल लौटाता है या सेट करता है। मान 1.0 100% के बराबर है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```

picture frame की चौड़ाई (relative to original picture size) का स्केल लौटाता है या सेट करता है। मान 1.0 100% के बराबर है। पढ़ने/लिखने योग्य float।

**रिटर्न:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```

picture frame की चौड़ाई (relative to original picture size) का स्केल लौटाता है या सेट करता है। मान 1.0 100% के बराबर है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |