---
title: IShapeFrame
second_title: Aspose.Slides for Java API संदर्भ
description: आकार फ्रेम की प्रॉपर्टी का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ishapeframe/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

आकार फ्रेम की प्रॉपर्टी का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getX()](#getX--) | फ़्रेम के ऊपरी-बाएँ कोने की X निर्देशांक वापस करता है। |
| [getY()](#getY--) | फ़्रेम के ऊपरी-बाएँ कोने की Y निर्देशांक वापस करता है। |
| [getWidth()](#getWidth--) | फ़्रेम की चौड़ाई वापस करता है। |
| [getHeight()](#getHeight--) | फ़्रेम की ऊँचाई वापस करता है। |
| [getRotation()](#getRotation--) | फ़्रेम के z-अक्ष के चारों ओर घुमाए जाने की डिग्री संख्या वापस करता है। |
| [getCenterX()](#getCenterX--) | फ़्रेम के केंद्र की X निर्देशांक वापस करता है। |
| [getCenterY()](#getCenterY--) | फ़्रेम के केंद्र की Y निर्देशांक वापस करता है। |
| [getFlipH()](#getFlipH--) | निर्धारित करता है कि फ़्रेम क्षैतिज रूप से फ़्लिप किया गया है या नहीं। |
| [getFlipV()](#getFlipV--) | निर्धारित करता है कि फ़्रेम लंबवत रूप से फ़्लिप किया गया है या नहीं। |
| [getRectangle()](#getRectangle--) | फ़्रेम के निर्देशांक वापस करता है। |
### getX() {#getX--}
```
public abstract float getX()
```

फ़्रेम के ऊपरी-बाएँ कोने की X निर्देशांक वापस करता है। केवल पढ़ने योग्य float.

**वापसी:**
float
### getY() {#getY--}
```
public abstract float getY()
```

फ़्रेम के ऊपरी-बाएँ कोने की Y निर्देशांक वापस करता है। केवल पढ़ने योग्य float.

**वापसी:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

फ़्रेम की चौड़ाई वापस करता है। केवल पढ़ने योग्य float.

**वापसी:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

फ़्रेम की ऊँचाई वापस करता है। केवल पढ़ने योग्य float.

**वापसी:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

फ़्रेम के z-अक्ष के चारों ओर घुमाए जाने की डिग्री संख्या वापस करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिक्लॉकवाइज़ घुमाव दर्शाता है। केवल पढ़ने योग्य float.

**वापसी:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```

फ़्रेम के केंद्र की X निर्देशांक वापस करता है। केवल पढ़ने योग्य float.

**वापसी:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```

फ़्रेम के केंद्र की Y निर्देशांक वापस करता है। केवल पढ़ने योग्य float.

**वापसी:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```

निर्धारित करता है कि फ़्रेम क्षैतिज रूप से फ़्लिप किया गया है या नहीं। केवल पढ़ने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**वापसी:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```

निर्धारित करता है कि फ़्रेम लंबवत रूप से फ़्लिप किया गया है या नहीं। केवल पढ़ने योग्य [NullableBool](../../com.aspose.slides/nullablebool).

**वापसी:**
byte
### getRectangle() {#getRectangle--}
```
public abstract Rectangle2D.Float getRectangle()
```

फ़्रेम के निर्देशांक वापस करता है। केवल पढ़ने योग्य java.awt.geom.Rectangle2D.Float.

**वापसी:**
java.awt.geom.Rectangle2D.Float