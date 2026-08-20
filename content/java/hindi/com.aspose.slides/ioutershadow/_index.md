---
title: IOuterShadow
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: एक बाहरी छाया प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ioutershadow/
---
**सभी लागू इंटरफेस:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

एक बाहरी छाया प्रभाव का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | ब्लर त्रिज्या, बिंदुओं में। |
| [setBlurRadius(double value)](#setBlurRadius-double-) | ब्लर त्रिज्या, बिंदुओं में। |
| [getDirection()](#getDirection--) | छाया की दिशा, डिग्री में। |
| [setDirection(float value)](#setDirection-float-) | छाया की दिशा, डिग्री में। |
| [getDistance()](#getDistance--) | वस्तु से छाया की दूरी, बिंदुओं में। |
| [setDistance(double value)](#setDistance-double-) | वस्तु से छाया की दूरी, बिंदुओं में। |
| [getShadowColor()](#getShadowColor--) | छाया का रंग। |
| [getRectangleAlign()](#getRectangleAlign--) | आयत की संरेखण। |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | आयत की संरेखण। |
| [getSkewHorizontal()](#getSkewHorizontal--) | क्षैतिज तिरछा कोण, डिग्री में। |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | क्षैतिज तिरछा कोण, डिग्री में। |
| [getSkewVertical()](#getSkewVertical--) | ऊर्ध्वाधर तिरछा कोण, डिग्री में। |
| [setSkewVertical(double value)](#setSkewVertical-double-) | ऊर्ध्वाधर तिरछा कोण, डिग्री में। |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | यह संकेत देता है कि छाया आकार के साथ घुमती है या नहीं। |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | यह संकेत देता है कि छाया आकार के साथ घुमती है या नहीं। |
| [getScaleHorizontal()](#getScaleHorizontal--) | क्षैतिज स्केलिंग फैक्टर, मूल आकार के प्रतिशत में। |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | क्षैतिज स्केलिंग फैक्टर, मूल आकार के प्रतिशत में। |
| [getScaleVertical()](#getScaleVertical--) | ऊर्ध्वाधर स्केलिंग फैक्टर, मूल आकार के प्रतिशत में। |
| [setScaleVertical(double value)](#setScaleVertical-double-) | ऊर्ध्वाधर स्केलिंग फैक्टर, मूल आकार के प्रतिशत में। |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

डिफ़ॉल्ट मान - 0 pt. पढ़ें/लिखें double.

**रिटर्न:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

डिफ़ॉल्ट मान - 0 pt. पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

डिफ़ॉल्ट मान - 0 � (बाएँ-से-दाएँ). पढ़ें/लिखें float.

**रिटर्न:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

डिफ़ॉल्ट मान - 0 � (बाएँ-से-दाएँ). पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

डिफ़ॉल्ट मान - 0 pt. पढ़ें/लिखें double.

**रिटर्न:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

डिफ़ॉल्ट मान - 0 pt. पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

डिफ़ॉल्ट मान - ऑटोमैटिक ब्लैक (थीम-निर्भर). केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

डिफ़ॉल्ट मान - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). पढ़ें/लिखें [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**रिटर्न:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

डिफ़ॉल्ट मान - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). पढ़ें/लिखें [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

डिफ़ॉल्ट मान - 0 �. पढ़ें/लिखें double.

**रिटर्न:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

डिफ़ॉल्ट मान - 0 �. पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

डिफ़ॉल्ट मान - 0 �. पढ़ें/लिखें double.

**रिटर्न:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

डिफ़ॉल्ट मान - 0 �. पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

डिफ़ॉल्ट मान - true. पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

डिफ़ॉल्ट मान - true. पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

डिफ़ॉल्ट मान - 100 %. पढ़ें/लिखें double.

**रिटर्न:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

डिफ़ॉल्ट मान - 100 %. पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

डिफ़ॉल्ट मान - 100 %. पढ़ें/लिखें double.

**रिटर्न:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

डिफ़ॉल्ट मान - 100 %. पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |