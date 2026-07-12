---
title: IReflection
second_title: Aspose.Slides Androidhoz a Java API referencia
description: Egy tükrözési effektust reprezentál.
type: docs
url: /hu/com.aspose.slides/ireflection/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IReflection extends IImageTransformOperation, IAccessiblePVIObject<IReflectionEffectiveData>
```

Egy tükrözési effektust reprezentál.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | Meghatározza a kezdő alfa érték kezdőpozícióját (az alfa színátmenet fokozatán) (százalék). |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | Meghatározza a kezdő alfa érték kezdőpozícióját (az alfa színátmenet fokozatán) (százalék). |
| [getEndPosAlpha()](#getEndPosAlpha--) | Meghatározza a vég alfa érték végpozícióját (az alfa színátmenet fokozatán) (százalék). |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | Meghatározza a vég alfa érték végpozícióját (az alfa színátmenet fokozatán) (százalék). |
| [getFadeDirection()](#getFadeDirection--) | Meghatározza a tükrözés eltolásának irányát. |
| [setFadeDirection(float value)](#setFadeDirection-float-) | Meghatározza a tükrözés eltolásának irányát. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | A tükrözés kezdeti átlátszatlansága. |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | A tükrözés kezdeti átlátszatlansága. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | A tükrözés végátlátszatlansága. |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | A tükrözés végátlátszatlansága. |
| [getBlurRadius()](#getBlurRadius--) | Elmosás sugara. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Elmosás sugara. |
| [getDirection()](#getDirection--) | A tükrözés iránya. |
| [setDirection(float value)](#setDirection-float-) | A tükrözés iránya. |
| [getDistance()](#getDistance--) | A tükrözés távolsága. |
| [setDistance(double value)](#setDistance-double-) | A tükrözés távolsága. |
| [getRectangleAlign()](#getRectangleAlign--) | Téglalap igazítása. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Téglalap igazítása. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Meghatározza a vízszintes ferdeség szögét. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Meghatározza a vízszintes ferdeség szögét. |
| [getSkewVertical()](#getSkewVertical--) | Meghatározza a függőleges ferdeség szögét. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Meghatározza a függőleges ferdeség szögét. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Meghatározza, hogy a tükrözés forgatódjon-e a formával, ha a forma el van forgatva. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Meghatározza, hogy a tükrözés forgatódjon-e a formával, ha a forma el van forgatva. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Meghatározza a vízszintes méretezési tényezőt, a negatív méretezés tükrözést okoz. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Meghatározza a vízszintes méretezési tényezőt, a negatív méretezés tükrözést okoz. |
| [getScaleVertical()](#getScaleVertical--) | Meghatározza a függőleges méretezési tényezőt, a negatív méretezés tükrözést okoz. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Meghatározza a függőleges méretezési tényezőt, a negatív méretezés tükrözést okoz. |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

Meghatározza a kezdő alfa érték kezdőpozícióját (az alfa színátmenet fokozatán) (százalék). Olvasás/írás float.

**Visszatér:**
float

### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public abstract void setStartPosAlpha(float value)
```

Meghatározza a kezdő alfa érték kezdőpozícióját (az alfa színátmenet fokozatán) (százalék). Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

Meghatározza a vég alfa érték végpozícióját (az alfa színátmenet fokozatán) (százalék). Olvasás/írás float.

**Visszatér:**
float

### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public abstract void setEndPosAlpha(float value)
```

Meghatározza a vég alfa érték végpozícióját (az alfa színátmenet fokozatán) (százalék). Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

Meghatározza a tükrözés eltolásának irányát (szög). Olvasás/írás float.

**Visszatér:**
float

### setFadeDirection(float value) {#setFadeDirection-float-}
```
public abstract void setFadeDirection(float value)
```

Meghatározza a tükrözés eltolásának irányát (szög). Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

A tükrözés kezdeti átlátszatlansága (százalék). Olvasás/írás float.

**Visszatér:**
float

### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public abstract void setStartReflectionOpacity(float value)
```

A tükrözés kezdeti átlátszatlansága (százalék). Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

A tükrözés végátlátszatlansága (százalék). Olvasás/írás float.

**Visszatér:**
float

### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public abstract void setEndReflectionOpacity(float value)
```

A tükrözés végátlátszatlansága (százalék). Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Elmosás sugara. Olvasás/írás double.

**Visszatér:**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Elmosás sugara. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

A tükrözés iránya. Olvasás/írás float.

**Visszatér:**
float

### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

A tükrözés iránya. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

A tükrözés távolsága. Olvasás/írás double.

**Visszatér:**
double

### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

A tükrözés távolsága. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Téglalap igazítása. Olvasás/írás [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Visszatér:**
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

Téglalap igazítása. Olvasás/írás [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Meghatározza a vízszintes ferdeség szögét. Olvasás/írás double.

**Visszatér:**
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

Meghatározza a vízszintes ferdeség szögét. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Meghatározza a függőleges ferdeség szögét. Olvasás/írás double.

**Visszatér:**
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

Meghatározza a függőleges ferdeség szögét. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Meghatározza, hogy a tükrözés forgatódjon-e a formával, ha a forma el van forgatva. Olvasás/írás boolean.

**Visszatér:**
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

Meghatározza, hogy a tükrözés forgatódjon-e a formával, ha a forma el van forgatva. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Meghatározza a vízszintes méretezési tényezőt, a negatív méretezés tükrözést okoz. (százalék) Olvasás/írás double.

**Visszatér:**
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

Meghatározza a vízszintes méretezési tényezőt, a negatív méretezés tükrözést okoz. (százalék) Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Meghatározza a függőleges méretezési tényezőt, a negatív méretezés tükrözést okoz. (százalék) Olvasás/írás double.

**Visszatér:**
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

Meghatározza a függőleges méretezési tényezőt, a negatív méretezés tükrözést okoz. (százalék) Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |