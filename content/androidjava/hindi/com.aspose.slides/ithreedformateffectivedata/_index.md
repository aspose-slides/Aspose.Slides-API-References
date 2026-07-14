---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: एक अपरिवर्तनीय ऑब्जेक्ट जो प्रभावी 3-D फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ithreedformateffectivedata/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

एक अपरिवर्तनीय वस्तु जो प्रभावी 3-D फ़ॉर्मेटिंग गुणां को दर्शाती है।

--------------------

यह इंटरफ़ेस [IThreeDFormat](../../com.aspose.slides/ithreedformat) इंटरफ़ेस के साथ मिलकर विरासत लागू की गई प्रभावी फ़ॉर्मेटिंग मान लौटाने के लिए उपयोग किया जाता है।

## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | एक 3D कंटूर की चौड़ाई लौटाता है। |
| [getExtrusionHeight()](#getExtrusionHeight--) | एक एक्सट्रूज़न प्रभाव की ऊँचाई लौटाता है। |
| [getDepth()](#getDepth--) | एक 3D आकार की गहराई लौटाता है। |
| [getBevelTop()](#getBevelTop--) | शीर्ष 3D बिवेल का प्रकार लौटाता है। |
| [getBevelBottom()](#getBevelBottom--) | निचले 3D बिवेल का प्रकार लौटाता है। |
| [getContourColor()](#getContourColor--) | एक कंटूर का रंग लौटाता है। |
| [getExtrusionColor()](#getExtrusionColor--) | एक एक्सट्रूज़न का रंग लौटाता है। |
| [getCamera()](#getCamera--) | एक कैमरा की सेटिंग्स लौटाता है। |
| [getLightRig()](#getLightRig--) | एक लाइट का प्रकार लौटाता है। |
| [getMaterial()](#getMaterial--) | एक सामग्री का प्रकार लौटाता है। |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

एक 3D कंटूर की चौड़ाई लौटाता है। केवल-पढ़ने योग्य double.

**वापसी:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

एक एक्सट्रूज़न प्रभाव की ऊँचाई लौटाता है। केवल-पढ़ने योग्य double.

**वापसी:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

एक 3D आकार की गहराई लौटाता है। केवल-पढ़ने योग्य double.

**वापसी:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

शीर्ष 3D बिवेल का प्रकार लौटाता है। केवल-पढ़ने योग्य [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)।

**वापसी:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

निचले 3D बिवेल का प्रकार लौटाता है। केवल-पढ़ने योग्य [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)।

**वापसी:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Integer getContourColor()
```

एक कंटूर का रंग लौटाता है। केवल-पढ़ने योग्य java.lang.Integer।

**वापसी:**
java.lang.Integer
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Integer getExtrusionColor()
```

एक एक्सट्रूज़न का रंग लौटाता है। केवल-पढ़ने योग्य java.lang.Integer।

**वापसी:**
java.lang.Integer
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

एक कैमरा की सेटिंग्स लौटाता है। केवल-पढ़ने योग्य [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)।

**वापसी:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

एक लाइट का प्रकार लौटाता है। केवल-पढ़ने योग्य [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)।

**वापसी:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

एक सामग्री का प्रकार लौटाता है। केवल-पढ़ने योग्य [MaterialPresetType](../../com.aspose.slides/materialpresettype)।

**वापसी:**
int