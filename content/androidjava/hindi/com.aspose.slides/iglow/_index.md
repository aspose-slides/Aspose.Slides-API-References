---
title: IGlow
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक ग्लो प्रभाव का प्रतिनिधित्व करता है, जिसमें वस्तु के किनारों के बाहर एक रंगीन धुंधला रूपरेखा जोड़ी जाती है।
type: docs
url: /hi/com.aspose.slides/iglow/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

एक ग्लो प्रभाव का प्रतिनिधित्व करता है, जिसमें वस्तु के किनारों के बाहर एक रंगीन धुंधला रूपरेखा जोड़ी जाती है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getRadius()](#getRadius--) | त्रिज्या। |
| [setRadius(double value)](#setRadius-double-) | त्रिज्या। |
| [getColor()](#getColor--) | रंग प्रारूप। |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


त्रिज्या। पढ़ें/लिखें double.

**रिटर्न वैल्यू:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


त्रिज्या। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


रंग प्रारूप। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**रिटर्न वैल्यू:**
[IColorFormat](../../com.aspose.slides/icolorformat)