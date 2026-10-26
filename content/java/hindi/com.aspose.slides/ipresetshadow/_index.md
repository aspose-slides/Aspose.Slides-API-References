---
title: IPresetShadow
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एक प्रीसेट शैडो प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ipresetshadow/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

एक प्रीसेट शैडो प्रभाव का प्रतिनिधित्व करता है।
## विधियाँ

| Method | Description |
| --- | --- |
| [getDirection()](#getDirection--) | छाया की दिशा। |
| [setDirection(float value)](#setDirection-float-) | छाया की दिशा। |
| [getDistance()](#getDistance--) | छाया की दूरी। |
| [setDistance(double value)](#setDistance-double-) | छाया की दूरी। |
| [getShadowColor()](#getShadowColor--) | छाया का रंग। |
| [getPreset()](#getPreset--) | पूर्व-निर्धारित। |
| [setPreset(int value)](#setPreset-int-) | पूर्व-निर्धारित। |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

छाया की दिशा। पढ़ने/लिखने योग्य float।

**Returns:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

छाया की दिशा। पढ़ने/लिखने योग्य float।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

छाया की दूरी। पढ़ने/लिखने योग्य double।

**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

छाया की दूरी। पढ़ने/लिखने योग्य double।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

छाया का रंग। पढ़ने-केवल [IColorFormat](../../com.aspose.slides/icolorformat)।

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

पूर्व-निर्धारित। पढ़ने/लिखने योग्य [PresetShadowType](../../com.aspose.slides/presetshadowtype)।

**Returns:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```

पूर्व-निर्धारित। पढ़ने/लिखने योग्य [PresetShadowType](../../com.aspose.slides/presetshadowtype)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |