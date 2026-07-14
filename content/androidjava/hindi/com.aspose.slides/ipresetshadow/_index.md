---
title: IPresetShadow
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: एक पूर्वनिर्धारित छाया प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ipresetshadow/
---
**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

एक पूर्वनिर्धारित छाया प्रभाव का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getDirection()](#getDirection--) | छाया की दिशा। |
| [setDirection(float value)](#setDirection-float-) | छाया की दिशा। |
| [getDistance()](#getDistance--) | छाया की दूरी। |
| [setDistance(double value)](#setDistance-double-) | छाया की दूरी। |
| [getShadowColor()](#getShadowColor--) | छाया का रंग। |
| [getPreset()](#getPreset--) | पूर्वनिर्धारित। |
| [setPreset(int value)](#setPreset-int-) | पूर्वनिर्धारित। |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

छाया की दिशा। पढ़ें/लिखें float.

**वापसी:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

छाया की दिशा। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

छाया की दूरी। पढ़ें/लिखें double.

**वापसी:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

छाया की दूरी। पढ़ें/लिखें double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

छाया का रंग। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

पूर्वनिर्धारित। पढ़ें/लिखें [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**वापसी:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```

पूर्वनिर्धारित। पढ़ें/लिखें [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |