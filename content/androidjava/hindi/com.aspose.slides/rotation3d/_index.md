---
title: Rotation3D
second_title: Aspose.Slides एंड्रॉइड के लिए जावा API रेफ़रेंस के माध्यम से
description: एक चार्ट के 3D घूर्णन का प्रतिनिधित्व करता है।
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

एक चार्ट के 3D घूर्णन का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getRotationX()](#getRotationX--) | X-अक्ष के आसपास घूर्णन डिग्री को लौटाता है या सेट करता है, अर्थात |
| [setRotationX(byte value)](#setRotationX-byte-) | X-अक्ष के आसपास घूर्णन डिग्री को लौटाता है या सेट करता है, अर्थात |
| [getRotationY()](#getRotationY--) | Y-अक्ष के आसपास घूर्णन डिग्री को लौटाता है या सेट करता है, अर्थात |
| [setRotationY(int value)](#setRotationY-int-) | Y-अक्ष के आसपास घूर्णन डिग्री को लौटाता है या सेट करता है, अर्थात |
| [getPerspective()](#getPerspective--) | 3D चार्ट के लिए परिप्रेक्ष्य मान (दृष्टिकोण कोण) को लौटाता है या सेट करता है (0 और 240 के बीच)। |
| [setPerspective(byte value)](#setPerspective-byte-) | 3D चार्ट के लिए परिप्रेक्ष्य मान (दृष्टिकोण कोण) को लौटाता है या सेट करता है (0 और 240 के बीच)। |
| [getRightAngleAxes()](#getRightAngleAxes--) | निर्धारित करता है कि चार्ट अक्षों को परिप्रेक्ष्य में खींचे जाने के बजाय समकोण पर रखा गया है या नहीं। |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | निर्धारित करता है कि चार्ट अक्षों को परिप्रेक्ष्य में खींचे जाने के बजाय समकोण पर रखा गया है या नहीं। |
| [getDepthPercents()](#getDepthPercents--) | 3D चार्ट की गहराई को चार्ट की चौड़ाई के प्रतिशत के रूप में लौटाता है या सेट करता है (20 से 2000 प्रतिशत के बीच)। |
| [setDepthPercents(int value)](#setDepthPercents-int-) | 3D चार्ट की गहराई को चार्ट की चौड़ाई के प्रतिशत के रूप में लौटाता है या सेट करता है (20 से 2000 प्रतिशत के बीच)। |
| [getHeightPercents()](#getHeightPercents--) | 3-D चार्ट की ऊँचाई को चार्ट की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है (5 से 500 प्रतिशत के बीच)। |
| [setHeightPercents(int value)](#setHeightPercents-int-) | 3-D चार्ट की ऊँचाई को चार्ट की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है (5 से 500 प्रतिशत के बीच)। |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

X-अक्ष के आसपास घूर्णन डिग्री को लौटाता है या सेट करता है, अर्थात 3D चार्ट के लिए Y दिशा में (-90 और 90 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 में 21.2.2.157 rotX (X Rotation) आइटम और PowerPoint 2007+ में "Y Rotation" विकल्प से मेल खाती है। पढ़ें/लिखें byte.

**रिटर्न:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

X-अक्ष के आसपास घूर्णन डिग्री को लौटाता है या सेट करता है, अर्थात 3D चार्ट के लिए Y दिशा में (-90 और 90 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 में 21.2.2.157 rotX (X Rotation) आइटम और PowerPoint 2007+ में "Y Rotation" विकल्प से मेल खाती है। पढ़ें/लिखें byte.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

Y-अक्ष के आसपास घूर्णन डिग्री को लौटाता है या सेट करता है, अर्थात 3D चार्ट के लिए X दिशा में (0 और 360 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 में 21.2.2.158 rotY (Y Rotation) आइटम और PowerPoint 2007+ में "X Rotation" विकल्प से मेल खाती है। पढ़ें/लिखें int.

**रिटर्न:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

Y-अक्ष के आसपास घूर्णन डिग्री को लौटाता है या सेट करता है, अर्थात 3D चार्ट के लिए X दिशा में (0 और 360 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 में 21.2.158 rotY (Y Rotation) आइटम और PowerPoint 2007+ में "X Rotation" विकल्प से मेल खाती है। पढ़ें/लिखें int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

3D चार्ट के लिए परिप्रेक्ष्य मान (दृष्टिकोण कोण) को लौटाता है या सेट करता है (0 और 240 के बीच)। यदि RightAngleAxes प्रॉपर्टी का मान true है तो अनदेखा किया जाता है। पढ़ें/लिखें byte.

**रिटर्न:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

3D चार्ट के लिए परिप्रेक्ष्य मान (दृष्टिकोण कोण) को लौटाता है या सेट करता है (0 और 240 के बीच)। यदि RightAngleAxes प्रॉपर्टी का मान true है तो अनदेखा किया जाता है। पढ़ें/लिखें byte.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

निर्धारित करता है कि चार्ट अक्षों को परिप्रेक्ष्य में खींचे जाने के बजाय समकोण पर रखा गया है या नहीं। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

निर्धारित करता है कि चार्ट अक्षों को परिप्रेक्ष्य में खींचे जाने के बजाय समकोण पर रखा गया है या नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

3D चार्ट की गहराई को चार्ट की चौड़ाई के प्रतिशत के रूप में लौटाता है या सेट करता है (20 से 2000 प्रतिशत के बीच)। पढ़ें/लिखें int.

**रिटर्न:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

3D चार्ट की गहराई को चार्ट की चौड़ाई के प्रतिशत के रूप में लौटाता है या सेट करता है (20 से 2000 प्रतिशत के बीच)। पढ़ें/लिखें int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

3-D चार्ट की ऊँचाई को चार्ट की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है (5 से 500 प्रतिशत के बीच)। पढ़ें/लिखें int.

**रिटर्न:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

3-D चार्ट की ऊँचाई को चार्ट की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है (5 से 500 प्रतिशत के बीच)। पढ़ें/लिखें int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject.

**रिटर्न:**
com.aspose.slides.IDOMObject