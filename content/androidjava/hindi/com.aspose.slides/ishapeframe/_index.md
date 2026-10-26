---
title: IShapeFrame
second_title: Aspose.Slides Android के लिए, Java API रेफ़रेंस के माध्यम से
description: आकार फ्रेम की विशेषताओं को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ishapeframe/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

आकार फ्रेम की विशेषताओं को दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getX()](#getX--) | फ़्रेम के ऊपरी-बाएँ कोने का X निर्देशांक लौटाता है। |
| [getY()](#getY--) | फ़्रेम के ऊपरी-बाएँ कोने का Y निर्देशांक लौटाता है। |
| [getWidth()](#getWidth--) | फ़्रेम की चौड़ाई लौटाता है। |
| [getHeight()](#getHeight--) | फ़्रेम की ऊँचाई लौटाता है। |
| [getRotation()](#getRotation--) | फ़्रेम के Z-अक्ष के चारों ओर घुमाए जाने के डिग्री की संख्या लौटाता है। |
| [getCenterX()](#getCenterX--) | फ़्रेम के केंद्र का X निर्देशांक लौटाता है। |
| [getCenterY()](#getCenterY--) | फ़्रेम के केंद्र का Y निर्देशांक लौटाता है। |
| [getFlipH()](#getFlipH--) | निर्धारित करता है कि फ़्रेम क्षैतिज रूप से उलटा है या नहीं। |
| [getFlipV()](#getFlipV--) | निर्धारित करता है कि फ़्रेम लंबवत रूप से उलटा है या नहीं। |
| [getRectangle()](#getRectangle--) | फ़्रेम के निर्देशांक लौटाता है। |
### getX() {#getX--}
```
public abstract float getX()
```

फ़्रेम के ऊपरी-बाएँ कोने का X निर्देशांक लौटाता है। केवल-पढ़ने योग्य float.

**रिटर्न:**
float
### getY() {#getY--}
```
public abstract float getY()
```

फ़्रेम के ऊपरी-बाएँ कोने का Y निर्देशांक लौटाता है। केवल-पढ़ने योग्य float.

**रिटर्न:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

फ़्रेम की चौड़ाई लौटाता है। केवल-पढ़ने योग्य float.

**रिटर्न:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

फ़्रेम की ऊँचाई लौटाता है। केवल-पढ़ने योग्य float.

**रिटर्न:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

फ़्रेम के Z-अक्ष के चारों ओर घुमाए जाने के डिग्री की संख्या लौटाता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिगमनात्मक घुमाव दर्शाता है। केवल-पढ़ने योग्य float.

**रिटर्न:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```

फ़्रेम के केंद्र का X निर्देशांक लौटाता है। केवल-पढ़ने योग्य float.

**रिटर्न:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```

फ़्रेम के केंद्र का Y निर्देशांक लौटाता है। केवल-पढ़ने योग्य float.

**रिटर्न:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```

निर्धारित करता है कि फ़्रेम क्षैतिज रूप से उलटा है या नहीं। केवल-पढ़ने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**रिटर्न:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```

निर्धारित करता है कि फ़्रेम लंबवत रूप से उलटा है या नहीं। केवल-पढ़ने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**रिटर्न:**
byte
### getRectangle() {#getRectangle--}
```
public abstract RectF getRectangle()
```

फ़्रेम के निर्देशांक लौटाता है। केवल-पढ़ने योग्य android.graphics.RectF.

**रिटर्न:**
android.graphics.RectF