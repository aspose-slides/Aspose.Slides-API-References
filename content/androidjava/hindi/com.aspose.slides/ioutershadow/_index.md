---
title: IOuterShadow
second_title: Aspose.Slides Android के लिए Java API संदर्भ
description: एक बाहरी छाया प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ioutershadow/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

एक बाहरी छाया प्रभाव का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | ब्लर त्रिज्या, पॉइंट्स में। |
| [setBlurRadius(double value)](#setBlurRadius-double-) | ब्लर त्रिज्या, पॉइंट्स में। |
| [getDirection()](#getDirection--) | छाया की दिशा, डिग्री में। |
| [setDirection(float value)](#setDirection-float-) | छाया की दिशा, डिग्री में। |
| [getDistance()](#getDistance--) | ऑब्जेक्ट से छाया की दूरी, पॉइंट्स में। |
| [setDistance(double value)](#setDistance-double-) | ऑब्जेक्ट से छाया की दूरी, पॉइंट्स में। |
| [getShadowColor()](#getShadowColor--) | छाया का रंग। |
| [getRectangleAlign()](#getRectangleAlign--) | आयत की संरेखण। |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | आयत की संरेखण। |
| [getSkewHorizontal()](#getSkewHorizontal--) | क्षैतिज विकृति कोण, डिग्री में। |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | क्षैतिज विकृति कोण, डिग्री में। |
| [getSkewVertical()](#getSkewVertical--) | ऊर्ध्वाधर विकृति कोण, डिग्री में। |
| [setSkewVertical(double value)](#setSkewVertical-double-) | ऊर्ध्वाधर विकृति कोण, डिग्री में। |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | यह दर्शाता है कि छाया आकार के साथ घूमती है या नहीं। |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | यह दर्शाता है कि छाया आकार के साथ घूमती है या नहीं। |
| [getScaleHorizontal()](#getScaleHorizontal--) | क्षैतिज स्केलिंग कारक, मूल आकार के प्रतिशत में। |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | क्षैतिज स्केलिंग कारक, मूल आकार के प्रतिशत में। |
| [getScaleVertical()](#getScaleVertical--) | ऊर्ध्वाधर स्केलिंग कारक, मूल आकार के प्रतिशत में। |
| [setScaleVertical(double value)](#setScaleVertical-double-) | ऊर्ध्वाधर स्केलिंग कारक, मूल आकार के प्रतिशत में। |

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

ब्लर त्रिज्या, पॉइंट्स में। डिफ़ॉल्ट मान - 0 pt। पढ़ें/लिखें double।

**रिटर्न:**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

ब्लर त्रिज्या, पॉइंट्स में। डिफ़ॉल्ट मान - 0 pt। पढ़ें/लिखें double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

छाया की दिशा, डिग्री में। डिफ़ॉल्ट मान - 0 � (left-to-right)। पढ़ें/लिखें float।

**रिटर्न:**
float

### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

छाया की दिशा, डिग्री में। डिफ़ॉल्ट मान - 0 � (left-to-right)। पढ़ें/लिखें float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

ऑब्जेक्ट से छाया की दूरी, पॉइंट्स में। डिफ़ॉल्ट मान - 0 pt। पढ़ें/लिखें double।

**रिटर्न:**
double

### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

ऑब्जेक्ट से छाया की दूरी, पॉइंट्स में। डिफ़ॉल्ट मान - 0 pt। पढ़ें/लिखें double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

छाया का रंग। डिफ़ॉल्ट मान - स्वचालित काला (थीम-निर्भर)। केवल-पढ़ने-योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

आयत की संरेखण। डिफ़ॉल्ट मान - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom)। पढ़ें/लिखें [RectangleAlignment](../../com.aspose.slides/rectanglealignment)।

**रिटर्न:**
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

आयत की संरेखण। डिफ़ॉल्ट मान - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom)। पढ़ें/लिखें [RectangleAlignment](../../com.aspose.slides/rectanglealignment)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

क्षैतिज विकृति कोण, डिग्री में। डिफ़ॉल्ट मान - 0 �। पढ़ें/लिखें double।

**रिटर्न:**
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

क्षैतिज विकृति कोण, डिग्री में। डिफ़ॉल्ट मान - 0 �। पढ़ें/लिखें double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

ऊर्ध्वाधर विकृति कोण, डिग्री में। डिफ़ॉल्ट मान - 0 �। पढ़ें/लिखें double।

**रिटर्न:**
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

ऊर्ध्वाधर विकृति कोण, डिग्री में। डिफ़ॉल्ट मान - 0 �। पढ़ें/लिखें double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

यह दर्शाता है कि छाया आकार के साथ घूमती है या नहीं। डिफ़ॉल्ट मान - true। पढ़ें/लिखें boolean।

**रिटर्न:**
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

यह दर्शाता है कि छाया आकार के साथ घूमती है या नहीं। डिफ़ॉल्ट मान - true। पढ़ें/लिखें boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

क्षैतिज स्केलिंग कारक, मूल आकार के प्रतिशत में। नकारात्मक स्केलिंग फ़्लिप करता है। डिफ़ॉल्ट मान - 100 %. पढ़ें/लिखें double।

**रिटर्न:**
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

क्षैतिज स्केलिंग कारक, मूल आकार के प्रतिशत में। नकारात्मक स्केलिंग फ़्लिप करता है। डिफ़ॉल्ट मान - 100 %. पढ़ें/लिखें double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

ऊर्ध्वाधर स्केलिंग कारक, मूल आकार के प्रतिशत में। नकारात्मक स्केलिंग फ़्लिप करता है। डिफ़ॉल्ट मान - 100 %. पढ़ें/लिखें double।

**रिटर्न:**
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

ऊर्ध्वाधर स्केलिंग कारक, मूल आकार के प्रतिशत में। नकारात्मक स्केलिंग फ़्लिप करता है। डिफ़ॉल्ट मान - 100 %. पढ़ें/लिखें double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |