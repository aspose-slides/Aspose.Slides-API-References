---
title: IChartWall
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: 3D चार्ट्स पर दीवारों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

3D चार्ट्स पर दीवारों का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getThickness()](#getThickness--) | दीवारों की मोटाई को प्लॉट आयतन के सबसे बड़े आयाम के प्रतिशत के रूप में रिटर्न या सेट करता है। |
| [setThickness(int value)](#setThickness-int-) | दीवारों की मोटाई को प्लॉट आयतन के सबसे बड़े आयाम के प्रतिशत के रूप में रिटर्न या सेट करता है। |
| [getFormat()](#getFormat--) | दीवार की भराव, रेखा, प्रभाव, 3D शैली को रिटर्न करता है। |
| [getPictureType()](#getPictureType--) | चित्र प्रकार को रिटर्न या सेट करता है। |
| [setPictureType(int value)](#setPictureType-int-) | चित्र प्रकार को रिटर्न या सेट करता है। |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```


दीवारों की मोटाई को प्लॉट आयतन के सबसे बड़े आयाम के प्रतिशत के रूप में रिटर्न या सेट करता है। पढ़ने/लिखने योग्य int.

**रिटर्न:**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```


दीवारों की मोटाई को प्लॉट आयतन के सबसे बड़े आयाम के प्रतिशत के रूप में रिटर्न या सेट करता है। पढ़ने/लिखने योग्य int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


दीवार की भराव, रेखा, प्रभाव, 3D शैली को रिटर्न करता है। केवल-पढ़ने योग्य [IFormat](../../com.aspose.slides/iformat).

**रिटर्न:**
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```


चित्र प्रकार को रिटर्न या सेट करता है। पढ़ने/लिखने योग्य [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**रिटर्न:**
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```


चित्र प्रकार को रिटर्न या सेट करता है। पढ़ने/लिखने योग्य [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |