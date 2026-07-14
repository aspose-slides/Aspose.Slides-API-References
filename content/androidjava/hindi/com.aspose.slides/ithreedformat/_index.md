---
title: IThreeDFormat
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: 3-D गुणों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ithreedformat/
---
**सभी लागू इंटरफ़ेस:** 
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

3-D गुणों का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | 3D कंटूर की चौड़ाई को लौटाता है या सेट करता है। |
| [setContourWidth(double value)](#setContourWidth-double-) | 3D कंटूर की चौड़ाई को लौटाता है या सेट करता है। |
| [getExtrusionHeight()](#getExtrusionHeight--) | एक्सट्रूज़न प्रभाव की ऊँचाई को लौटाता है या सेट करता है। |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | एक्सट्रूज़न प्रभाव की ऊँचाई को लौटाता है या सेट करता है। |
| [getDepth()](#getDepth--) | 3D आकार की गहराई को लौटाता है या सेट करता है। |
| [setDepth(double value)](#setDepth-double-) | 3D आकार की गहराई को लौटाता है या सेट करता है। |
| [getBevelTop()](#getBevelTop--) | टॉप 3D बिवेल के प्रकार को लौटाता है या सेट करता है। |
| [getBevelBottom()](#getBevelBottom--) | बॉटम 3D बिवेल के प्रकार को लौटाता है या सेट करता है। |
| [getContourColor()](#getContourColor--) | कंटूर का रंग लौटाता है या सेट करता है। |
| [getExtrusionColor()](#getExtrusionColor--) | एक्सट्रूज़न का रंग लौटाता है या सेट करता है। |
| [getCamera()](#getCamera--) | कैमरा सेटिंग्स को लौटाता है या सेट करता है। |
| [getLightRig()](#getLightRig--) | लाइट के प्रकार को लौटाता है या सेट करता है। |
| [getMaterial()](#getMaterial--) | मैटीरियल के प्रकार को लौटाता है या सेट करता है। |
| [setMaterial(int value)](#setMaterial-int-) | मैटीरियल के प्रकार को लौटाता है या सेट करता है। |
| [getEffective()](#getEffective--) | विरासत लागू की गई प्रभावी 3-D फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

3D कंटूर की चौड़ाई को लौटाता है या सेट करता है। पढ़ें/लिखें double.

**वापसी:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

3D कंटूर की चौड़ाई को लौटाता है या सेट करता है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

एक्सट्रूज़न प्रभाव की ऊँचाई को लौटाता है या सेट करता है। पढ़ें/लिखें double.

**वापसी:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

एक्सट्रूज़न प्रभाव की ऊँचाई को लौटाता है या सेट करता है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

3D आकार की गहराई को लौटाता है या सेट करता है। पढ़ें/लिखें double.

**वापसी:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

3D आकार की गहराई को लौटाता है या सेट करता है। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

टॉप 3D बिवेल के प्रकार को लौटाता है या सेट करता है। केवल-पढ़ने योग्य [IShapeBevel](../../com.aspose.slides/ishapebevel).

**वापसी:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

बॉटम 3D बिवेल के प्रकार को लौटाता है या सेट करता है। केवल-पढ़ने योग्य [IShapeBevel](../../com.aspose.slides/ishapebevel).

**वापसी:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

कंटूर का रंग लौटाता है या सेट करता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

एक्सट्रूज़न का रंग लौटाता है या सेट करता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

कैमरा सेटिंग्स को लौटाता है या सेट करता है। केवल-पढ़ने योग्य [ICamera](../../com.aspose.slides/icamera).

**वापसी:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

लाइट के प्रकार को लौटाता है या सेट करता है। केवल-पढ़ने योग्य [ILightRig](../../com.aspose.slides/ilightrig).

**वापसी:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

मैटीरियल के प्रकार को लौटाता है या सेट करता है। पढ़ें/लिखें [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**वापसी:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

मैटीरियल के प्रकार को लौटाता है या सेट करता है। पढ़ें/लिखें [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

विरासत लागू की गई प्रभावी 3-D फ़ॉर्मेटिंग डेटा प्राप्त करता है।

**वापसी:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - एक [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).