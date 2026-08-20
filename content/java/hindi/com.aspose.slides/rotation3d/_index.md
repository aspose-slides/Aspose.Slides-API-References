---
title: Rotation3D
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: चार्ट के 3D रोटेशन का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/rotation3d/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

एक चार्ट के 3D रोटेशन का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getRotationX()](#getRotationX--) | X-अक्ष के चारों ओर घूर्णन डिग्री को प्राप्त करता है या सेट करता है, अर्थात् |
| [setRotationX(byte value)](#setRotationX-byte-) | X-अक्ष के चारों ओर घूर्णन डिग्री को प्राप्त करता है या सेट करता है, अर्थात् |
| [getRotationY()](#getRotationY--) | Y-अक्ष के चारों ओर घूर्णन डिग्री को प्राप्त करता है या सेट करता है, अर्थात् |
| [setRotationY(int value)](#setRotationY-int-) | Y-अक्ष के चारों ओर घूर्णन डिग्री को प्राप्त करता है या सेट करता है, अर्थात् |
| [getPerspective()](#getPerspective--) | 3D चार्ट्स के लिए परिप्रेक्ष्य मान (फ़ील्ड ऑफ़ व्यू कोण) को प्राप्त करता है या सेट करता है (0 से 240 के बीच)। |
| [setPerspective(byte value)](#setPerspective-byte-) | 3D चार्ट्स के लिए परिप्रेक्ष्य मान (फ़ील्ड ऑफ़ व्यू कोण) को प्राप्त करता है या सेट करता है (0 से 240 के बीच)। |
| [getRightAngleAxes()](#getRightAngleAxes--) | निर्धारित करता है कि चार्ट के अक्ष दृश्‍यविन्यास में नहीं, बल्कि समकोण पर हैं या नहीं। |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | निर्धारित करता है कि चार्ट के अक्ष दृश्‍यविन्यास में नहीं, बल्कि समकोण पर हैं या नहीं। |
| [getDepthPercents()](#getDepthPercents--) | 3D चार्ट की गहराई को चार्ट की चौड़ाई के प्रतिशत के रूप में प्राप्त करता है या सेट करता है (20 से 2000 प्रतिशत के बीच)। |
| [setDepthPercents(int value)](#setDepthPercents-int-) | 3D चार्ट की गहराई को चार्ट की चौड़ाई के प्रतिशत के रूप में प्राप्त करता है या सेट करता है (20 से 2000 प्रतिशत के बीच)। |
| [getHeightPercents()](#getHeightPercents--) | 3-D चार्ट की ऊँचाई को चार्ट की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है (5 से 500 प्रतिशत के बीच)। |
| [setHeightPercents(int value)](#setHeightPercents-int-) | 3-D चार्ट की ऊँचाई को चार्ट की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है (5 से 500 प्रतिशत के बीच)। |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

X-अक्ष के चारों ओर घूर्णन डिग्री को प्राप्त या सेट करता है, अर्थात् 3D चार्ट्स के लिए Y दिशा में (-90 से 90 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 के 21.2.2.157 rotX (X Rotation) आइटम और PowerPoint 2007+ के "Y Rotation" विकल्प के साथ मेल खाती है। Read/write बाइट।

**रिटर्न:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

X-अक्ष के चारों ओर घूर्णन डिग्री को प्राप्त या सेट करता है, अर्थात् 3D चार्ट्स के लिए Y दिशा में (-90 से 90 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 के 21.2.2.157 rotX (X Rotation) आइटम और PowerPoint 2007+ के "Y Rotation" विकल्प के साथ मेल खाती है। Read/write बाइट।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

Y-अक्ष के चारों ओर घूर्णन डिग्री को प्राप्त या सेट करता है, अर्थात् 3D चार्ट्स के लिए X दिशा में (0 से 360 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 के 21.2.2.158 rotY (Y Rotation) आइटम और PowerPoint 2007+ के "X Rotation" विकल्प के साथ मेल खाती है। Read/write int.

**रिटर्न:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

Y-अक्ष के चारों ओर घूर्णन डिग्री को प्राप्त या सेट करता है, अर्थात् 3D चार्ट्स के लिए X दिशा में (0 से 360 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 के 21.2.2.158 rotY (Y Rotation) आइटम और PowerPoint 2007+ के "X Rotation" विकल्प के साथ मेल खाती है। Read/write int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

3D चार्ट्स के लिए परिप्रेक्ष्य मान (फ़ील्ड ऑफ़ व्यू कोण) को प्राप्त या सेट करता है (0 से 240 के बीच)। यदि RightAngleAxes प्रॉपर्टी मान true है तो इसे नज़रअंदाज़ किया जाता है। Read/write बाइट।

**रिटर्न:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

3D चार्ट्स के लिए परिप्रेक्ष्य मान (फ़ील्ड ऑफ़ व्यू कोण) को प्राप्त या सेट करता है (0 से 240 के बीच)। यदि RightAngleAxes प्रॉपर्टी मान true है तो इसे नज़रअंदाज़ किया जाता है। Read/write बाइट।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

निर्धारित करता है कि चार्ट के अक्ष दृश्‍यविन्यास में नहीं, बल्कि समकोण पर हैं या नहीं। दूसरे शब्दों में यह निर्धारित करता है कि चार्ट के अक्षों के कोण चार्ट के घूर्णन या ऊँचाई से स्वतंत्र हैं या नहीं। Read/write बूलियन।

**रिटर्न:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

निर्धारित करता है कि चार्ट के अक्ष दृश्‍यविन्यास में नहीं, बल्कि समकोण पर हैं या नहीं। दूसरे शब्दों में यह निर्धारित करता है कि चार्ट के अक्षों के कोण चार्ट के घूर्णन या ऊँचाई से स्वतंत्र हैं या नहीं। Read/write बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

3D चार्ट की गहराई को चार्ट की चौड़ाई के प्रतिशत के रूप में प्राप्त या सेट करता है (20 से 2000 प्रतिशत के बीच)। Read/write int।

**रिटर्न:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

3D चार्ट की गहराई को चार्ट की चौड़ाई के प्रतिशत के रूप में प्राप्त या सेट करता है (20 से 2000 प्रतिशत के बीच)। Read/write int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

3-D चार्ट की ऊँचाई को चार्ट की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है (5 से 500 प्रतिशत के बीच)। Read/write int।

**रिटर्न:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

3-D चार्ट की ऊँचाई को चार्ट की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है (5 से 500 प्रतिशत के बीच)। Read/write int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट को प्राप्त करता है। केवल-पढ़ने योग्य IDOMObject।

**रिटर्न:**
com.aspose.slides.IDOMObject