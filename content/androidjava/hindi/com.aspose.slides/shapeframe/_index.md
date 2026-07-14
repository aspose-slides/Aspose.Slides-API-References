---
title: ShapeFrame
second_title: Java API रेफ़रेंस के माध्यम से Android के लिए Aspose.Slides
description: shape frames की विशेषताओं को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/shapeframe/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

shape frame की विशेषताओं को दर्शाता है।

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | नए shape frame की विशेषताओं को बनाता है। |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getX()](#getX--) | एक फ्रेम के ऊपरी-बाएँ कोने का X निर्देशांक लौटाता है। |
| [getY()](#getY--) | एक फ्रेम के ऊपरी-बाएँ कोने का Y निर्देशांक लौटाता है। |
| [getWidth()](#getWidth--) | एक फ्रेम की चौड़ाई लौटाता है। |
| [getHeight()](#getHeight--) | एक फ्रेम की ऊँचाई लौटाता है। |
| [getRotation()](#getRotation--) | Z-अक्ष के आसपास फ्रेम के घुमाव की डिग्री संख्या लौटाता है। |
| [getCenterX()](#getCenterX--) | फ्रेम के केंद्र का X निर्देशांक लौटाता है। |
| [getCenterY()](#getCenterY--) | फ्रेम के केंद्र का Y निर्देशांक लौटाता है। |
| [getFlipH()](#getFlipH--) | निर्धारित करता है कि फ्रेम क्षैतिज रूप से फ़्लिप किया गया है या नहीं। |
| [getFlipV()](#getFlipV--) | निर्धारित करता है कि फ्रेम लंबवत रूप से फ़्लिप किया गया है या नहीं। |
| [getRectangle()](#getRectangle--) | फ्रेम के निर्देशांक लौटाता है। |
| [deepClone()](#deepClone--) | कॉपी बनाता है |
| [cloneT()](#cloneT--) | कॉपी बनाता है। |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट ऑब्जेक्ट के बराबर है या नहीं। |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट ऑब्जेक्ट के बराबर है या नहीं। |

### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

नया shape frame की विशेषताएँ बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | फ़्रेम का X निर्देशांक। |
| y | float | फ़्रेम का Y निर्देशांक। |
| width | float | फ़्रेम की चौड़ाई। |
| height | float | फ़्रेम की ऊँचाई। |
| flipH | byte | यदि फ्रेम क्षैतिज रूप से फ़्लिप किया गया है तो true। |
| flipV | byte | यदि फ्रेम लंबवत रूप से फ़्लिप किया गया है तो true। |
| rotationAngle | float | फ़्रेम के घुमाव की डिग्री संख्या। |

### getX() {#getX--}
```
public final float getX()
```

एक फ्रेम के ऊपरी-बाएँ कोने का X निर्देशांक लौटाता है। केवल पढ़ने योग्य float।

**रिटर्न:**
float

### getY() {#getY--}
```
public final float getY()
```

एक फ्रेम के ऊपरी-बाएँ कोने का Y निर्देशांक लौटाता है। केवल पढ़ने योग्य float।

**रिटर्न:**
float

### getWidth() {#getWidth--}
```
public final float getWidth()
```

फ़्रेम की चौड़ाई लौटाता है। केवल पढ़ने योग्य float।

**रिटर्न:**
float

### getHeight() {#getHeight--}
```
public final float getHeight()
```

फ़्रेम की ऊँचाई लौटाता है। केवल पढ़ने योग्य float।

**रिटर्न:**
float

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Z-अक्ष के आसपास फ्रेम के घुमाव की डिग्री संख्या लौटाता है। सकारात्मक मान घड़ी की दिशा में घूमना दर्शाता है; नकारात्मक मान विपरीत दिशा में घूमना दर्शाता है। केवल पढ़ने योग्य float।

**रिटर्न:**
float

### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

फ़्रेम के केंद्र का X निर्देशांक लौटाता है। केवल पढ़ने योग्य float।

**रिटर्न:**
float

### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

फ़्रेम के केंद्र का Y निर्देशांक लौटाता है। केवल पढ़ने योग्य float।

**रिटर्न:**
float

### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

निर्धारित करता है कि फ्रेम क्षैतिज रूप से फ़्लिप किया गया है या नहीं। केवल पढ़ने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**
byte

### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

निर्धारित करता है कि फ्रेम लंबवत रूप से फ़्लिप किया गया है या नहीं। केवल पढ़ने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न:**
byte

### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```

फ़्रेम के निर्देशांक लौटाता है। केवल पढ़ने योग्य android.graphics.RectF।

**रिटर्न:**
android.graphics.RectF

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

कॉपी बनाता है

**रिटर्न:**
java.lang.Object - क्लोन किया गया shape frame।

### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

कॉपी बनाता है।

**रिटर्न:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - क्लोन किया गया shape frame।

### hashCode() {#hashCode--}
```
public int hashCode()
```




**रिटर्न:**
int

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट ऑब्जेक्ट के बराबर है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस इंस्टेंस से तुलना करने के लिए ऑब्जेक्ट। |

**रिटर्न:**
boolean - **true** यदि obj एक ShapeFrame है जिसका मान इस इंस्टेंस के समान है; अन्यथा, **false**।

### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट ऑब्जेक्ट के बराबर है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | इस इंस्टेंस से तुलना करने के लिए ShapeFRameEx। |

**रिटर्न:**
boolean - **true** यदि value एक ShapeFrame है जिसका मान इस इंस्टेंस के समान है; अन्यथा, **false**.