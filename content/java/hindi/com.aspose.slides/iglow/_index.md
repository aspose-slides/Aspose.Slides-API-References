---
title: IGlow
second_title: Aspose.Slides जावा API रेफ़रेंस
description: ऑब्जेक्ट के किनारों के बाहर एक रंगीन धुंधली रूपरेखा जोड़ी जाने वाले ग्लो प्रभाव को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/iglow/
---
**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

आब्जेक्ट के किनारों के बाहर रंगीन धुंधला रूपरेखा जोड़कर चमक प्रभाव को दर्शाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getRadius()](#getRadius--) | त्रिज्या। |
| [setRadius(double value)](#setRadius-double-) | त्रिज्या। |
| [getColor()](#getColor--) | रंग स्वरूप। |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

त्रिज्या। पढ़ें/लिखें डबल।

**वापसी:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

त्रिज्या। पढ़ें/लिखें डबल।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

रंग स्वरूप। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)