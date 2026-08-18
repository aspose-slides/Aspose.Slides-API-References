---
title: IReflectionEffectiveData
second_title: Aspose.Slides Java API referencia
description: Módosíthatatlan objektum, amely egy tükrözési effektet képvisel.
type: docs
url: /hu/com.aspose.slides/ireflectioneffectivedata/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IReflectionEffectiveData extends IEffectEffectiveData
```

Módosíthatatlan objektum, amely egy tükrözési effektust képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | Meghatározza a kezdő pozíciót (az alfa színátmenet mentén) a kezdő alfa értékhez (százalékban). |
| [getEndPosAlpha()](#getEndPosAlpha--) | Meghatározza a végpozíciót (az alfa színátmenet mentén) a vég alfa értékhez (százalékban). |
| [getFadeDirection()](#getFadeDirection--) | Meghatározza a tükrözés eltolásának irányát. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | Kezdő tükrözés átlátszatlansága. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | Végső tükrözés átlátszatlansága. |
| [getBlurRadius()](#getBlurRadius--) | Elmosás sugara. |
| [getDirection()](#getDirection--) | Tükrözés iránya. |
| [getDistance()](#getDistance--) | Tükrözés távolsága. |
| [getRectangleAlign()](#getRectangleAlign--) | Téglalap igazítása. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Meghatározza a vízszintes ferdeség szögét. |
| [getSkewVertical()](#getSkewVertical--) | Meghatározza a függőleges ferdeség szögét. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Meghatározza, hogy a tükrözés a formával együtt forgatható-e, ha a forma el van forgatva. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Meghatározza a vízszintes méretezési faktort, a negatív méretezés tükrözést eredményez. |
| [getScaleVertical()](#getScaleVertical--) | Meghatározza a függőleges méretezési faktort, a negatív méretezés tükrözést eredményez. |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

Meghatározza a kezdő pozíciót (az alfa színátmenet mentén) a kezdő alfa értékhez (százalékban). Csak olvasható float.

**Visszatérési érték:**
float

### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

Meghatározza a végpozíciót (az alfa színátmenet mentén) a vég alfa értékhez (százalékban). Csak olvasható float.

**Visszatérési érték:**
float

### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

Meghatározza a tükrözés eltolásának irányát. (szög). Csak olvasható float.

**Visszatérési érték:**
float

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

Kezdő tükrözés átlátszatlansága. (százalékban). Csak olvasható float.

**Visszatérési érték:**
float

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

Végső tükrözés átlátszatlansága. (százalékban). Csak olvasható float.

**Visszatérési érték:**
float

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Elmosás sugara. Csak olvasható double.

**Visszatérési érték:**
double

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Tükrözés iránya. Csak olvasható float.

**Visszatérési érték:**
float

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Tükrözés távolsága. Csak olvasható double.

**Visszatérési érték:**
double

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Téglalap igazítása. Csak olvasható [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Visszatérési érték:**
byte

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Meghatározza a vízszintes ferdeség szögét. Csak olvasható double.

**Visszatérési érték:**
double

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Meghatározza a függőleges ferdeség szögét. Csak olvasható double.

**Visszatérési érték:**
double

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Meghatározza, hogy a tükrözés a formával együtt forgatható-e, ha a forma el van forgatva. Csak olvasható boolean.

**Visszatérési érték:**
boolean

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Meghatározza a vízszintes méretezési faktort, a negatív méretezés tükrözést eredményez. (százalékban) Csak olvasható double.

**Visszatérési érték:**
double

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Meghatározza a függőleges méretezési faktort, a negatív méretezés tükrözést eredményez. (százalékban) Csak olvasható double.

**Visszatérési érték:**
double