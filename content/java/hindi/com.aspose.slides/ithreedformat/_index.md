---
title: IThreeDFormat
second_title: जावा के लिए Aspose.Slides API संदर्भ
description: 3-डी गुणों को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ithreedformat/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

3-डी गुणों को दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | 3D कंटूर की चौड़ाई को लौटाता है या सेट करता है। |
| [setContourWidth(double value)](#setContourWidth-double-) | 3D कंटूर की चौड़ाई को लौटाता है या सेट करता है। |
| [getExtrusionHeight()](#getExtrusionHeight--) | एक एक्सट्रूज़न प्रभाव की ऊँचाई को लौटाता है या सेट करता है। |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | एक एक्सट्रूज़न प्रभाव की ऊँचाई को लौटाता है या सेट करता है। |
| [getDepth()](#getDepth--) | 3D आकार की गहराई को लौटाता है या सेट करता है। |
| [setDepth(double value)](#setDepth-double-) | 3D आकार की गहराई को लौटाता है या सेट करता है। |
| [getBevelTop()](#getBevelTop--) | एक शीर्ष 3D बिवल का प्रकार लौटाता है या सेट करता है। |
| [getBevelBottom()](#getBevelBottom--) | एक निचला 3D बिवल का प्रकार लौटाता है या सेट करता है। |
| [getContourColor()](#getContourColor--) | कंटूर का रंग लौटाता है या सेट करता है। |
| [getExtrusionColor()](#getExtrusionColor--) | एक एक्सट्रूज़न का रंग लौटाता है या सेट करता है। |
| [getCamera()](#getCamera--) | कैमरा की सेटिंग्स लौटाता है या सेट करता है। |
| [getLightRig()](#getLightRig--) | लाइट का प्रकार लौटाता है या सेट करता है। |
| [getMaterial()](#getMaterial--) | मटेरियल का प्रकार लौटाता है या सेट करता है। |
| [setMaterial(int value)](#setMaterial-int-) | मटेरियल का प्रकार लौटाता है या सेट करता है। |
| [getEffective()](#getEffective--) | विरासत लागू होने के साथ प्रभावी 3-डी फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


3D कंटूर की चौड़ाई को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य double.

**रिटर्न:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```


3D कंटूर की चौड़ाई को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


एक एक्सट्रूज़न प्रभाव की ऊँचाई को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य double.

**रिटर्न:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```


एक एक्सट्रूज़न प्रभाव की ऊँचाई को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


3D आकार की गहराई को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य double.

**रिटर्न:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```


3D आकार की गहराई को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```


एक शीर्ष 3D बिवल का प्रकार लौटाता है या सेट करता है। केवल-पढ़ने योग्य [IShapeBevel](../../com.aspose.slides/ishapebevel).

**रिटर्न:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```


एक निचला 3D बिवल का प्रकार लौटाता है या सेट करता है। केवल-पढ़ने योग्य [IShapeBevel](../../com.aspose.slides/ishapebevel).

**रिटर्न:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```


कंटूर का रंग लौटाता है या सेट करता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```


एक एक्सट्रूज़न का रंग लौटाता है या सेट करता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```


कैमरा की सेटिंग्स लौटाता है या सेट करता है। केवल-पढ़ने योग्य [ICamera](../../com.aspose.slides/icamera).

**रिटर्न:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```


लाइट का प्रकार लौटाता है या सेट करता है। केवल-पढ़ने योग्य [ILightRig](../../com.aspose.slides/ilightrig).

**रिटर्न:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


मटेरियल का प्रकार लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**रिटर्न:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```


मटेरियल का प्रकार लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```


विरासत लागू होने के साथ प्रभावी 3-डी फ़ॉर्मेटिंग डेटा प्राप्त करता है।

**रिटर्न:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).