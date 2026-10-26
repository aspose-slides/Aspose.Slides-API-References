---
title: IReflection
second_title: Aspose.Slides for Java API-referencia
description: Tükrözési effektust reprezentál.
type: docs
url: /hu/com.aspose.slides/ireflection/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IReflection extends IImageTransformOperation, IAccessiblePVIObject<IReflectionEffectiveData>
```

Represents a reflection effect.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | Megadja a kezdő alfa érték (százalék) kezdőpozícióját (az alfa gradiens rámpán). |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | Megadja a kezdő alfa érték (százalék) kezdőpozícióját (az alfa gradiens rámpán). |
| [getEndPosAlpha()](#getEndPosAlpha--) | Megadja a befejező alfa érték (százalék) végpozícióját (az alfa gradiens rámpán). |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | Megadja a befejező alfa érték (százalék) végpozícióját (az alfa gradiens rámpán). |
| [getFadeDirection()](#getFadeDirection--) | Megadja a tükrözés eltolásának irányát. |
| [setFadeDirection(float value)](#setFadeDirection-float-) | Megadja a tükrözés eltolásának irányát. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | Kezdő tükrözés átlátszósága (százalék). |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | Kezdő tükrözés átlátszósága (százalék). |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | Végső tükrözés átlátszósága (százalék). |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | Végső tükrözés átlátszósága (százalék). |
| [getBlurRadius()](#getBlurRadius--) | Elmosódási sugár. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Elmosódási sugár. |
| [getDirection()](#getDirection--) | Tükrözés iránya. |
| [setDirection(float value)](#setDirection-float-) | Tükrözés iránya. |
| [getDistance()](#getDistance--) | Tükrözés távolsága. |
| [setDistance(double value)](#setDistance-double-) | Tükrözés távolsága. |
| [getRectangleAlign()](#getRectangleAlign--) | Téglalap igazítása. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Téglalap igazítása. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Megadja a vízszintes ferdeségi szöget. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Megadja a vízszintes ferdeségi szöget. |
| [getSkewVertical()](#getSkewVertical--) | Megadja a függőleges ferdeségi szöget. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Megadja a függőleges ferdeségi szöget. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Megadja, hogy a tükrözés forgatható-e a formával, ha a forma elfordul. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Megadja, hogy a tükrözés forgatható-e a formával, ha a forma elfordul. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Megadja a vízszintes méretezési tényezőt, a negatív méretezés tükrözést eredményez. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Megadja a vízszintes méretezési tényezőt, a negatív méretezés tükrözést eredményez. |
| [getScaleVertical()](#getScaleVertical--) | Megadja a függőleges méretezési tényezőt, a negatív méretezés tükrözést eredményez. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Megadja a függőleges méretezési tényezőt, a negatív méretezés tükrözést eredményez. |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

Specifies the start position (along the alpha gradient ramp) of the start alpha value (percents). Read/write float.

**Returns:**
float

### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public abstract void setStartPosAlpha(float value)
```

Specifies the start position (along the alpha gradient ramp) of the start alpha value (percents). Read/write float.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

Specifies the end position (along the alpha gradient ramp) of the end alpha value (percents). Read/write float.

**Returns:**
float

### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public abstract void setEndPosAlpha(float value)
```

Specifies the end position (along the alpha gradient ramp) of the end alpha value (percents). Read/write float.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

Specifies the direction to offset the reflection. (angle). Read/write float.

**Returns:**
float

### setFadeDirection(float value) {#setFadeDirection-float-}
```
public abstract void setFadeDirection(float value)
```

Specifies the direction to offset the reflection. (angle). Read/write float.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

Starting reflection opacity. (percents). Read/write float.

**Returns:**
float

### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public abstract void setStartReflectionOpacity(float value)
```

Starting reflection opacity. (percents). Read/write float.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

End reflection opacity. (percents). Read/write float.

**Returns:**
float

### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public abstract void setEndReflectionOpacity(float value)
```

End reflection opacity. (percents). Read/write float.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Blur radius. Read/write double.

**Returns:**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Blur radius. Read/write double.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Direction of reflection. Read/write float.

**Returns:**
float

### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Direction of reflection. Read/write float.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Distance of reflection. Read/write double.

**Returns:**
double

### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Distance of reflection. Read/write double.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Rectangle alignment. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Returns:**
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

Rectangle alignment. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Specifies the horizontal skew angle. Read/write double.

**Returns:**
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

Specifies the horizontal skew angle. Read/write double.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Specifies the vertical skew angle. Read/write double.

**Returns:**
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

Specifies the vertical skew angle. Read/write double.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Specifies whether the reflection should rotate with the shape if the shape is rotated. Read/write boolean.

**Returns:**
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

Specifies whether the reflection should rotate with the shape if the shape is rotated. Read/write boolean.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Specifies the horizontal scaling factor, negative scaling causes a flip. (percents) Read/write double.

**Returns:**
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

Specifies the horizontal scaling factor, negative scaling causes a flip. (percents) Read/write double.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Specifies the vertical scaling factor, negative scaling causes a flip. (percents) Read/write double.

**Returns:**
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

Specifies the vertical scaling factor, negative scaling causes a flip. (percents) Read/write double.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |