---
title: IPictureFrame
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एक फ्रेम को दर्शाता है जिसमें चित्र शामिल है।
type: docs
url: /hi/com.aspose.slides/ipictureframe/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

एक फ़्रेम को दर्शाता है जिसमें चित्र शामिल है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Returns PictureFrame's locks. |
| [getPictureFormat()](#getPictureFormat--) | Returns the PictureFillFormat object for a picture frame. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Returns or sets the scale of height(relative to original picture size) of the picture frame. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Returns or sets the scale of height(relative to original picture size) of the picture frame. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Returns or sets the scale of width (relative to original picture size) of the picture frame. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Returns or sets the scale of width (relative to original picture size) of the picture frame. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```

PictureFrame के लॉक को लौटाता है। केवल-पढ़ने योग्य [IPictureFrameLock](../../com.aspose.slides/ipictureframelock)।

**वापसी:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```

एक चित्र फ़्रेम के लिए PictureFillFormat ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)।

**वापसी:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```

चित्र फ़्रेम की ऊँचाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है या सेट करता है। मान 1.0 = 100% के बराबर है। पढ़ने/लिखने योग्य float।

**वापसी:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```

चित्र फ़्रेम की ऊँचाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है या सेट करता है। मान 1.0 = 100% के बराबर है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```

चित्र फ़्रेम की चौड़ाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है या सेट करता है। मान 1.0 = 100% के बराबर है। पढ़ने/लिखने योग्य float।

**वापसी:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```

चित्र फ़्रेम की चौड़ाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है या सेट करता है। मान 1.0 = 100% के बराबर है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |