---
title: IRotation3D
second_title: Aspose.Slides for Java API Reference
description: एक चार्ट का 3D रोटेशन दर्शाता है।
type: docs
url: /hi/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

एक चार्ट का 3D रोटेशन दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getRotationX()](#getRotationX--) | X-axis के चारों ओर घूर्णन डिग्री को लौटाता है या सेट करता है, अर्थात् |
| [setRotationX(byte value)](#setRotationX-byte-) | X-axis के चारों ओर घूर्णन डिग्री को लौटाता है या सेट करता है, अर्थात् |
| [getRotationY()](#getRotationY--) | Y-axis के चारों ओर घूर्णन डिग्री को लौटाता है या सेट करता है, अर्थात् |
| [setRotationY(int value)](#setRotationY-int-) | Y-axis के चारों ओर घूर्णन डिग्री को लौटाता है या सेट करता है, अर्थात् |
| [getPerspective()](#getPerspective--) | 3D चार्ट्स के लिए परिप्रेक्ष्य मान (फ़ील्ड ऑफ़ व्यू कोण) को लौटाता है या सेट करता है (0 से 100 के बीच)। |
| [setPerspective(byte value)](#setPerspective-byte-) | 3D चार्ट्स के लिए परिप्रेक्ष्य मान (फ़ील्ड ऑफ़ व्यू कोण) को लौटाता है या सेट करता है (0 से 100 के बीच)। |
| [getRightAngleAxes()](#getRightAngleAxes--) | निर्धारित करता है कि चार्ट की धुरीयाँ दायाँ कोण पर हैं या परिप्रेक्ष्य में नहीं खींची गई हैं। |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | निर्धारित करता है कि चार्ट की धुरीयाँ दायाँ कोण पर हैं या परिप्रेक्ष्य में नहीं खींची गई हैं। |
| [getDepthPercents()](#getDepthPercents--) | एक 3D चार्ट की गहराई को चार्ट की चौड़ाई के प्रतिशत के रूप में लौटाता है या सेट करता है (20 से 2000 प्रतिशत के बीच)। |
| [setDepthPercents(int value)](#setDepthPercents-int-) | एक 3D चार्ट की गहराई को चार्ट की चौड़ाई के प्रतिशत के रूप में लौटाता है या सेट करता है (20 से 2000 प्रतिशत के बीच)। |
| [getHeightPercents()](#getHeightPercents--) | 3-डि चार्ट की ऊँचाई को चार्ट की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है (5 से 500 प्रतिशत के बीच)। |
| [setHeightPercents(int value)](#setHeightPercents-int-) | 3-डि चार्ट की ऊँचाई को चार्ट की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है (5 से 500 प्रतिशत के बीच)। |

### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

X-axis के चारों ओर घूर्णन डिग्री को लौटाता है या सेट करता है, अर्थात् 3D चार्ट्स के लिए Y दिशा में (-90 से 90 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 में 21.2.2.157 rotX (X Rotation) आइटम और PowerPoint 2007+ में "Y Rotation" विकल्प के साथ मेल खाती है। पढ़ें/लिखें बाइट।

**रिटर्न्स:**
byte

### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

X-axis के चारों ओर घूर्णन डिग्री को लौटाता है या सेट करता है, अर्थात् 3D चार्ट्स के लिए Y दिशा में (-90 से 90 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 में 21.2.2.157 rotX (X Rotation) आइटम और PowerPoint 2007+ में "Y Rotation" विकल्प के साथ मेल खाती है। पढ़ें/लिखें बाइट।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Y-axis के चारों ओर घूर्णन डिग्री को लौटाता है या सेट करता है, अर्थात् 3D चार्ट्स के लिए X दिशा में (0 से 360 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 में 21.2.158 rotY (Y Rotation) आइटम और PowerPoint 2007+ में "X Rotation" विकल्प के साथ मेल खाती है। पढ़ें/लिखें int।

**रिटर्न्स:**
int

### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Y-axis के चारों ओर घूर्णन डिग्री को लौटाता है या सेट करता है, अर्थात् 3D चार्ट्स के लिए X दिशा में (0 से 360 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 में 21.2.158 rotY (Y Rotation) आइटम और PowerPoint 2007+ में "X Rotation" विकल्प के साथ मेल खाती है। पढ़ें/लिखें int।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

3D चार्ट्स के लिए परिप्रेक्ष्य मान (फ़ील्ड ऑफ़ व्यू कोण) को लौटाता है या सेट करता है (0 और 100 के बीच)। यदि RightAngleAxes प्रॉपर्टी का मान true है तो इसे अनदेखा किया जाता है। पढ़ें/लिखें बाइट।

**रिटर्न्स:**
byte

### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

3D चार्ट्स के लिए परिप्रेक्ष्य मान (फ़ील्ड ऑफ़ व्यू कोण) को लौटाता है या सेट करता है (0 और 100 के बीच)। यदि RightAngleAxes प्रॉपर्टी का मान true है तो इसे अनदेखा किया जाता है। पढ़ें/लिखें बाइट।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

निर्धारित करता है कि चार्ट की धुरीयाँ दायाँ कोण पर हैं या परिप्रेक्ष्य में नहीं खींची गई हैं। दूसरे शब्दों में यह निर्धारित करता है कि चार्ट की धुरीयों के कोण चार्ट के घुमाव या उन्नयन से स्वतंत्र हैं। पढ़ें/लिखें बूलियन।

**रिटर्न्स:**
boolean

### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

निर्धारित करता है कि चार्ट की धुरीयाँ दायाँ कोण पर हैं या परिप्रेक्ष्य में नहीं खींची गई हैं। दूसरे शब्दों में यह निर्धारित करता है कि चार्ट की धुरीयों के कोण चार्ट के घुमाव या उन्नयन से स्वतंत्र हैं। पढ़ें/लिखें बूलियन।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

एक 3D चार्ट की गहराई को चार्ट की चौड़ाई के प्रतिशत के रूप में लौटाता है या सेट करता है (20 से 2000 प्रतिशत के बीच)। पढ़ें/लिखें int।

**रिटर्न्स:**
int

### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

एक 3D चार्ट की गहराई को चार्ट की चौड़ाई के प्रतिशत के रूप में लौटाता है या सेट करता है (20 से 2000 प्रतिशत के बीच)। पढ़ें/लिखें int।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

3-डि चार्ट की ऊँचाई को चार्ट की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है (5 से 500 प्रतिशत के बीच)। पढ़ें/लिखें int।

**रिटर्न्स:**
int

### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

3-डि चार्ट की ऊँचाई को चार्ट की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है (5 से 500 प्रतिशत के बीच)। पढ़ें/लिखें int।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |