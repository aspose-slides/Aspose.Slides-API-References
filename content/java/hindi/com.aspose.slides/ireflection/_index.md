---
title: IReflection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक प्रतिबिंब प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ireflection/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IReflection extends IImageTransformOperation, IAccessiblePVIObject<IReflectionEffectiveData>
```

एक प्रतिबिंब प्रभाव का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | Specifies the start position (along the alpha gradient ramp) of the start alpha value (percents). |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | Specifies the start position (along the alpha gradient ramp) of the start alpha value (percents). |
| [getEndPosAlpha()](#getEndPosAlpha--) | Specifies the end position (along the alpha gradient ramp) of the end alpha value (percents). |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | Specifies the end position (along the alpha gradient ramp) of the end alpha value (percents). |
| [getFadeDirection()](#getFadeDirection--) | Specifies the direction to offset the reflection. |
| [setFadeDirection(float value)](#setFadeDirection-float-) | Specifies the direction to offset the reflection. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | Starting reflection opacity. |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | Starting reflection opacity. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | End reflection opacity. |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | End reflection opacity. |
| [getBlurRadius()](#getBlurRadius--) | Blur radius. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Blur radius. |
| [getDirection()](#getDirection--) | Direction of reflection. |
| [setDirection(float value)](#setDirection-float-) | Direction of reflection. |
| [getDistance()](#getDistance--) | Distance of reflection. |
| [setDistance(double value)](#setDistance-double-) | Distance of reflection. |
| [getRectangleAlign()](#getRectangleAlign--) | Rectangle alignment. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Rectangle alignment. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Specifies the horizontal skew angle. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Specifies the horizontal skew angle. |
| [getSkewVertical()](#getSkewVertical--) | Specifies the vertical skew angle. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Specifies the vertical skew angle. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Specifies whether the reflection should rotate with the shape if the shape is rotated. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Specifies whether the reflection should rotate with the shape if the shape is rotated. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Specifies the horizontal scaling factor, negative scaling causes a flip. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Specifies the horizontal scaling factor, negative scaling causes a flip. |
| [getScaleVertical()](#getScaleVertical--) | Specifies the vertical scaling factor, negative scaling causes a flip. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Specifies the vertical scaling factor, negative scaling causes a flip. |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

शुरुआती अल्फा मान (प्रतिशत) की शुरू स्थिति (alpha ग्रेडिएंट रैंप के साथ) को निर्दिष्ट करता है। पढ़ने/लिखने योग्य float.

**वापसी:**
float

### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public abstract void setStartPosAlpha(float value)
```

शुरुआती अल्फा मान (प्रतिशत) की शुरू स्थिति (alpha ग्रेडिएंट रैंप के साथ) को निर्दिष्ट करता है। पढ़ने/लिखने योग्य float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

अंत अल्फा मान (प्रतिशत) की अंत स्थिति (alpha ग्रेडिएंट रैंप के साथ) को निर्दिष्ट करता है। पढ़ने/लिखने योग्य float.

**वापसी:**
float

### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public abstract void setEndPosAlpha(float value)
```

अंत अल्फा मान (प्रतिशत) की अंत स्थिति (alpha ग्रेडिएंट रैंप के साथ) को निर्दिष्ट करता है। पढ़ने/लिखने योग्य float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

प्रतिबिंब को ऑफसेट करने की दिशा (कोण) को निर्दिष्ट करता है। पढ़ने/लिखने योग्य float.

**वापसी:**
float

### setFadeDirection(float value) {#setFadeDirection-float-}
```
public abstract void setFadeDirection(float value)
```

प्रतिबिंब को ऑफसेट करने की दिशा (कोण) को निर्दिष्ट करता है। पढ़ने/लिखने योग्य float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

प्रारम्भिक प्रतिबिंब अपारदर्शिता (प्रतिशत)। पढ़ने/लिखने योग्य float.

**वापसी:**
float

### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public abstract void setStartReflectionOpacity(float value)
```

प्रारम्भिक प्रतिबिंब अपारदर्शिता (प्रतिशत)। पढ़ने/लिखने योग्य float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

अंत प्रतिबिंब अपारदर्शिता (प्रतिशत)। पढ़ने/लिखने योग्य float.

**वापसी:**
float

### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public abstract void setEndReflectionOpacity(float value)
```

अंत प्रतिबिंब अपारदर्शिता (प्रतिशत)। पढ़ने/लिखने योग्य float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

ब्लर त्रिज्या। पढ़ने/लिखने योग्य double.

**वापसी:**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

ब्लर त्रिज्या। पढ़ने/लिखने योग्य double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

प्रतिबिंब की दिशा। पढ़ने/लिखने योग्य float.

**वापसी:**
float

### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

प्रतिबिंब की दिशा। पढ़ने/लिखने योग्य float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

प्रतिबिंब की दूरी। पढ़ने/लिखने योग्य double.

**वापसी:**
double

### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

प्रतिबिंब की दूरी। पढ़ने/लिखने योग्य double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

आयत संरेखण। पढ़ने/लिखने योग्य [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**वापसी:**
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

आयत संरेखण। पढ़ने/लिखने योग्य [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

क्षैतिज स्क्यू कोण को निर्दिष्ट करता है। पढ़ने/लिखने योग्य double.

**वापसी:**
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

क्षैतिज स्क्यू कोण को निर्दिष्ट करता है। पढ़ने/लिखने योग्य double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

वर्टिकल स्क्यू कोण को निर्दिष्ट करता है। पढ़ने/लिखने योग्य double.

**वापसी:**
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

वर्टिकल स्क्यू कोण को निर्दिष्ट करता है। पढ़ने/लिखने योग्य double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

यदि आकार घुमाया गया हो तो प्रतिबिंब को आकार के साथ घुमाना चाहिए या नहीं, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य boolean.

**वापसी:**
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

यदि आकार घुमाया गया हो तो प्रतिबिंब को आकार के साथ घुमाना चाहिए या नहीं, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

क्षैतिज स्केलिंग कारक को निर्दिष्ट करता है, नकारात्मक स्केलिंग फ्लिप का कारण बनती है। (प्रतिशत) पढ़ने/लिखने योग्य double.

**वापसी:**
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

क्षैतिज स्केलिंग कारक को निर्दिष्ट करता है, नकारात्मक स्केलिंग फ्लिप का कारण बनती है। (प्रतिशत) पढ़ने/लिखने योग्य double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

वर्टिकल स्केलिंग कारक को निर्दिष्ट करता है, नकारात्मक स्केलिंग फ्लिप का कारण बनती है। (प्रतिशत) पढ़ने/लिखने योग्य double.

**वापसी:**
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

वर्टिकल स्केलिंग कारक को निर्दिष्ट करता है, नकारात्मक स्केलिंग फ्लिप का कारण बनती है। (प्रतिशत) पढ़ने/लिखने योग्य double.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |