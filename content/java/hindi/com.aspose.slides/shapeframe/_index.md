---
title: ShapeFrame
second_title: Aspose.Slides for Java API संदर्भ
description: शेप फ्रेम की प्रॉपर्टीज़ का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/shapeframe/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

Represents shape frame's properties.
## Constructors

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | नया shape frame की प्रॉपर्टीज़ बनाता है। |
## Methods

| मेथड | विवरण |
| --- | --- |
| [getX()](#getX--) | फ्रेम के ऊपर-बाएँ कोने की X निर्देशांक लौटाता है। |
| [getY()](#getY--) | फ्रेम के ऊपर-बाएँ कोने की Y निर्देशांक लौटाता है। |
| [getWidth()](#getWidth--) | फ्रेम की चौड़ाई लौटाता है। |
| [getHeight()](#getHeight--) | फ्रेम की ऊँचाई लौटाता है। |
| [getRotation()](#getRotation--) | फ्रेम के z-अक्ष के चारों ओर घुमाए जाने वाले डिग्री की संख्या लौटाता है। |
| [getCenterX()](#getCenterX--) | फ्रेम के केन्द्र की X निर्देशांक लौटाता है। |
| [getCenterY()](#getCenterY--) | फ्रेम के केन्द्र की Y निर्देशांक लौटाता है। |
| [getFlipH()](#getFlipH--) | निर्धारित करता है कि फ्रेम क्षैतिज रूप से उल्टा है या नहीं। |
| [getFlipV()](#getFlipV--) | निर्धारित करता है कि फ्रेम लंबवत रूप से उल्टा है या नहीं। |
| [getRectangle()](#getRectangle--) | फ्रेम के निर्देशांक लौटाता है। |
| [deepClone()](#deepClone--) | क्लोन करता है |
| [cloneT()](#cloneT--) | क्लोन करता है। |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | वह मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट ऑब्जेक्ट के बराबर है या नहीं। |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | वह मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट ऑब्जेक्ट के बराबर है या नहीं। |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```


नया shape frame की प्रॉपर्टीज़ बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | फ्रेम की X निर्देशांक। |
| y | float | फ्रेम की Y निर्देशांक। |
| width | float | फ्रेम की चौड़ाई। |
| height | float | फ्रेम की ऊँचाई। |
| flipH | byte | यदि फ्रेम क्षैतिज रूप से उल्टा है तो True। |
| flipV | byte | यदि फ्रेम लंबवत रूप से उल्टा है तो True। |
| rotationAngle | float | फ्रेम के घुमाए जाने वाले डिग्री की संख्या। |

### getX() {#getX--}
```
public final float getX()
```


फ़्रेम के ऊपर-बाएँ कोने की X निर्देशांक लौटाता है। केवल-पढ़ने योग्य float।

**रिटर्न मान:**
float
### getY() {#getY--}
```
public final float getY()
```


फ़्रेम के ऊपर-बाएँ कोने की Y निर्देशांक लौटाता है। केवल-पढ़ने योग्य float।

**रिटर्न मान:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```


फ़्रेम की चौड़ाई लौटाता है। केवल-पढ़ने योग्य float।

**रिटर्न मान:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```


फ़्रेम की ऊँचाई लौटाता है। केवल-पढ़ने योग्य float।

**रिटर्न मान:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```


फ़्रेम के z-अक्ष के चारों ओर घुमाए जाने वाले डिग्री की संख्या लौटाता है। सकारात्मक मान घड़ी की सुई की दिशा में घुमाव दर्शाता है; नकारात्मक मान उल्टा दर्शाता है। केवल-पढ़ने योग्य float।

**रिटर्न मान:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```


फ्रेम के केन्द्र की X निर्देशांक लौटाता है। केवल-पढ़ने योग्य float।

**रिटर्न मान:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```


फ्रेम के केन्द्र की Y निर्देशांक लौटाता है। केवल-पढ़ने योग्य float।

**रिटर्न मान:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```


निर्धारित करता है कि फ्रेम क्षैतिज रूप से उल्टा है या नहीं। केवल-पढ़ने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न मान:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```


निर्धारित करता है कि फ्रेम लंबवत रूप से उल्टा है या नहीं। केवल-पढ़ने योग्य [NullableBool](../../com.aspose.slides/nullablebool)।

**रिटर्न मान:**
byte
### getRectangle() {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```


फ्रेम के निर्देशांक लौटाता है। केवल-पढ़ने योग्य java.awt.geom.Rectangle2D.Float।

**रिटर्न मान:**
java.awt.geom.Rectangle2D.Float
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


क्लोन करता है

**रिटर्न मान:**
java.lang.Object - क्लोन किया गया shape frame।
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```


क्लोन करता है।

**रिटर्न मान:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - क्लोन किया गया shape frame।
### hashCode() {#hashCode--}
```
public int hashCode()
```




**रिटर्न मान:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


यह मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट ऑब्जेक्ट के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस इंस्टेंस से तुलना करने वाला ऑब्जेक्ट। |

**रिटर्न मान:**
boolean - **true** यदि obj एक ShapeFrame है जिसका मान इस इंस्टेंस के समान है; अन्यथा **false**।
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```


यह मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट ऑब्जेक्ट के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | इस इंस्टेंस से तुलना करने वाला ShapeFRameEx। |

**रिटर्न मान:**
boolean - **true** यदि value एक ShapeFrame है जिसका मान इस इंस्टेंस के समान है; अन्यथा **false**।