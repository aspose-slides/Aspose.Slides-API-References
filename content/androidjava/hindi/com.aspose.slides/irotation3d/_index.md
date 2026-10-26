---
title: IRotation3D
second_title: Aspose.Slides for Android via Java API Reference
description: चार्ट का 3D घूर्णन दर्शाता है।
type: docs
url: /hi/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

चार्ट का 3D घूर्णन दर्शाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getRotationX()](#getRotationX--) | X-अक्ष के चारों ओर घूर्णन डिग्री लौटाता है या सेट करता है, अर्थात् |
| [setRotationX(byte value)](#setRotationX-byte-) | X-अक्ष के चारों ओर घूर्णन डिग्री लौटाता है या सेट करता है, अर्थात् |
| [getRotationY()](#getRotationY--) | Y-अक्ष के चारों ओर घूर्णन डिग्री लौटाता है या सेट करता है, अर्थात् |
| [setRotationY(int value)](#setRotationY-int-) | Y-अक्ष के चारों ओर घूर्णन डिग्री लौटाता है या सेट करता है, अर्थात् |
| [getPerspective()](#getPerspective--) | 3D चार्ट के लिए परिप्रेक्ष्य मान (क्षेत्र दृश्य कोण) लौटाता है या सेट करता है (0 से 100 के बीच)। |
| [setPerspective(byte value)](#setPerspective-byte-) | 3D चार्ट के लिए परिप्रेक्ष्य मान (क्षेत्र दृश्य угол) लौटाता है या सेट करता है (0 से 100 के बीच)। |
| [getRightAngleAxes()](#getRightAngleAxes--) | निर्धारित करता है कि चार्ट अक्ष सही कोणों पर हैं या नहीं, परिप्रेक्ष्य में खींचे जाने के बजाय। |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | निर्धारित करता है कि चार्ट अक्ष सही कोणों पर हैं या नहीं, परिप्रेक्ष्य में खींचे जाने के बजाय। |
| [getDepthPercents()](#getDepthPercents--) | चार्ट की चौड़ाई के प्रतिशत के रूप में 3D चार्ट की गहराई लौटाता है या सेट करता है (20 से 2000 प्रतिशत के बीच)। |
| [setDepthPercents(int value)](#setDepthPercents-int-) | चार्ट की चौड़ाई के प्रतिशत के रूप में 3D चार्ट की गहराई लौटाता है या सेट करता है (20 से 2000 प्रतिशत के बीच)। |
| [getHeightPercents()](#getHeightPercents--) | चार्ट की चौड़ाई के प्रतिशत के रूप में 3-D चार्ट की ऊँचाई निर्दिष्ट करता है (5 से 500 प्रतिशत के बीच)। |
| [setHeightPercents(int value)](#setHeightPercents-int-) | चार्ट की चौड़ाई के प्रतिशत के रूप में 3-D चार्ट की ऊँचाई निर्दिष्ट करता है (5 से 500 प्रतिशत के बीच)। |

### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

X-अक्ष के चारों ओर घूर्णन डिग्री लौटाता है या सेट करता है, अर्थात् 3D चार्ट के लिए Y दिशा में (-90 से 90 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 में 21.2.2.157 rotX (X Rotation) आइटम और PowerPoint 2007+ में "Y Rotation" विकल्प के साथ मेल खाती है। पढ़ें/लिखें बाइट।

**रिटर्न:**  
byte

### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

X-अक्ष के चारों ओर घूर्णन डिग्री लौटाता है या सेट करता है, अर्थात् 3D चार्ट के लिए Y दिशा में (-90 से 90 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 में 21.2.2.157 rotX (X Rotation) आइटम और PowerPoint 2007+ में "Y Rotation" विकल्प के साथ मेल खाती है। पढ़ें/लिखें बाइट।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Y-अक्ष के चारों ओर घूर्णन डिग्री लौटाता है या सेट करता है, अर्थात् 3D चार्ट के लिए X दिशा में (0 से 360 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 में 21.2.2.158 rotY (Y Rotation) आइटम और PowerPoint 2007+ में "X Rotation" विकल्प के साथ मेल खाती है। पढ़ें/लिखें int।

**रिटर्न:**  
int

### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Y-अक्ष के चारों ओर घूर्णन डिग्री लौटाता है या सेट करता है, अर्थात् 3D चार्ट के लिए X दिशा में (0 से 360 डिग्री के बीच)। यह प्रॉपर्टी ECMA-376 में 21.2.158 rotY (Y Rotation) आइटम और PowerPoint 2007+ में "X Rotation" विकल्प के साथ मेल खाती है। पढ़ें/लिखें int।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

3D चार्ट के लिए परिप्रेक्ष्य मान (क्षेत्र दृश्य угол) लौटाता है या सेट करता है (0 से 100 के बीच)। यदि RightAngleAxes प्रॉपर्टी मान true है तो इसे नजरअंदाज किया जाता है। पढ़ें/लिखें बाइट।

**रिटर्न:**  
byte

### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

3D चार्ट के लिए परिप्रेक्ष्य मान (क्षेत्र दृश्य угол) लौटाता है या सेट करता है (0 से 100 के बीच)। यदि RightAngleAxes प्रॉपर्टी मान true है तो इसे नजरअंदाज किया जाता है। पढ़ें/लिखें बाइट।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

निर्धारित करता है कि चार्ट अक्ष सही कोणों पर हैं या नहीं, परिप्रेक्ष्य में खींचे जाने के बजाय। दूसरे शब्दों में यह निर्धारित करता है कि चार्ट अक्षों के कोण चार्ट घूर्णन या ऊँचाई से स्वतंत्र हैं या नहीं। पढ़ें/लिखें बूलियन।

**रिटर्न:**  
boolean

### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

निर्धारित करता है कि चार्ट अक्ष सही कोणों पर हैं या नहीं, परिप्रेक्ष्य में खींचे जाने के बजाय। दूसरे शब्दों में यह निर्धारित करता है कि चार्ट अक्षों के कोण चार्ट घूर्णन या ऊँचाई से स्वतंत्र हैं या नहीं। पढ़ें/लिखें बूलियन।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

चार्ट की चौड़ाई के प्रतिशत के रूप में 3D चार्ट की गहराई लौटाता है या सेट करता है (20 से 2000 प्रतिशत के बीच)। पढ़ें/लिखें int।

**रिटर्न:**  
int

### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

चार्ट की चौड़ाई के प्रतिशत के रूप में 3D चार्ट की गहराई लौटाता है या सेट करता है (20 से 2000 प्रतिशत के बीच)। पढ़ें/लिखें int।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

चार्ट की चौड़ाई के प्रतिशत के रूप में 3-D चार्ट की ऊँचाई निर्दिष्ट करता है (5 से 500 प्रतिशत के बीच)। पढ़ें/लिखें int।

**रिटर्न:**  
int

### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

चार्ट की चौड़ाई के प्रतिशत के रूप में 3-D चार्ट की ऊँचाई निर्दिष्ट करता है (5 से 500 प्रतिशत के बीच)। पढ़ें/लिखें int।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |