---
title: IChartWall
second_title: Aspose.Slides for Java API Reference
description: Represents walls on 3d charts.
type: docs
url: /hi/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

3d चार्ट पर दीवारों का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getThickness()](#getThickness--) | दीवार की मोटाई को प्लॉट वॉल्यूम के सबसे बड़े आयाम के प्रतिशत के रूप में लौटाता या सेट करता है। |
| [setThickness(int value)](#setThickness-int-) | दीवार की मोटाई को प्लॉट वॉल्यूम के सबसे बड़े आयाम के प्रतिशत के रूप में लौटाता या सेट करता है। |
| [getFormat()](#getFormat--) | दीवार के भराव, रेखा, प्रभाव, 3d शैलियों को लौटाता है। |
| [getPictureType()](#getPictureType--) | चित्र प्रकार को लौटाता या सेट करता है। |
| [setPictureType(int value)](#setPictureType-int-) | चित्र प्रकार को लौटाता या सेट करता है। |

### getThickness() {#getThickness--}
```
public abstract int getThickness()
```

दीवार की मोटाई को प्लॉट वॉल्यूम के सबसे बड़े आयाम के प्रतिशत के रूप में लौटाता या सेट करता है। पढ़ें/लिखें int.

**रिटर्न:**  
int

### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```

दीवार की मोटाई को प्लॉट वॉल्यूम के सबसे बड़े आयाम के प्रतिशत के रूप में लौटाता या सेट करता है। पढ़ें/लिखें int.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

दीवार के भराव, रेखा, प्रभाव, 3d शैलियों को लौटाता है। केवल पढ़ने योग्य [IFormat](../../com.aspose.slides/iformat).

**रिटर्न:**  
[IFormat](../../com.aspose.slides/iformat)

### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```

चित्र प्रकार को लौटाता या सेट करता है। पढ़ें/लिखें [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**रिटर्न:**  
int

### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```

चित्र प्रकार को लौटाता या सेट करता है। पढ़ें/लिखें [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |