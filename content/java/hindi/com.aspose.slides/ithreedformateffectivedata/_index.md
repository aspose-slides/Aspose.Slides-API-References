---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक अपरिवर्तनीय वस्तु जो प्रभावी 3-D स्वरूपण गुणों का प्रतिनिधित्व करती है।
type: docs
url: /hi/com.aspose.slides/ithreedformateffectivedata/
---
**सभी लागू किए गए इंटरफ़ेस:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

एक अपरिवर्तनीय वस्तु जो प्रभावी 3-D स्वरूपण गुणों का प्रतिनिधित्व करती है।

--------------------

यह इंटरफ़ेस [IThreeDFormat](../../com.aspose.slides/ithreedformat) इंटरफ़ेस के साथ मिलकर उपयोग किया जाता है ताकि विरासत लागू होने पर प्रभावी स्वरूपण मान लौटाए जा सकें।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | 3D कंटूर की चौड़ाई लौटाता है। |
| [getExtrusionHeight()](#getExtrusionHeight--) | एक एक्सट्रूज़न प्रभाव की ऊँचाई लौटाता है। |
| [getDepth()](#getDepth--) | 3D आकार की गहराई लौटाता है। |
| [getBevelTop()](#getBevelTop--) | ऊपरी 3D बिवेल का प्रकार लौटाता है। |
| [getBevelBottom()](#getBevelBottom--) | निचले 3D बिवेल का प्रकार लौटाता है। |
| [getContourColor()](#getContourColor--) | कंटूर का रंग लौटाता है। |
| [getExtrusionColor()](#getExtrusionColor--) | एक्सट्रूज़न का रंग लौटाता है। |
| [getCamera()](#getCamera--) | कैमरा की सेटिंग्स लौटाता है। |
| [getLightRig()](#getLightRig--) | प्रकाश का प्रकार लौटाता है। |
| [getMaterial()](#getMaterial--) | सामग्री का प्रकार लौटाता है। |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

3D कंटूर की चौड़ाई लौटाता है। केवल-पढ़ने योग्य double.

**वापसी:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

एक्सट्रूज़न प्रभाव की ऊँचाई लौटाता है। केवल-पढ़ने योग्य double.

**वापसी:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

3D आकार की गहराई लौटाता है। केवल-पढ़ने योग्य double.

**वापसी:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

ऊपरी 3D बिवेल का प्रकार लौटाता है। केवल-पढ़ने योग्य [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**वापसी:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

निचले 3D बिवेल का प्रकार लौटाता है। केवल-पढ़ने योग्य [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**वापसी:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Color getContourColor()
```

कंटूर का रंग लौटाता है। केवल-पढ़ने योग्य java.awt.Color.

**वापसी:**
java.awt.Color
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Color getExtrusionColor()
```

एक्सट्रूज़न का रंग लौटाता है। केवल-पढ़ने योग्य java.awt.Color.

**वापसी:**
java.awt.Color
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

कैमरा की सेटिंग्स लौटाता है। केवल-पढ़ने योग्य [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**वापसी:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

प्रकाश का प्रकार लौटाता है। केवल-पढ़ने योग्य [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**वापसी:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

सामग्री का प्रकार लौटाता है। केवल-पढ़ने योग्य [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**वापसी:**
int