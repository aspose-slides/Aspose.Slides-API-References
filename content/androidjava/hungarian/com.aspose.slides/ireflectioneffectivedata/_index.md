---
title: IReflectionEffectiveData
second_title: Aspose.Slides Androidhoz Java API referencia
description: Módosíthatatlan objektum, amely egy tükrözési hatást képvisel.
type: docs
url: /hu/com.aspose.slides/ireflectioneffectivedata/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IReflectionEffectiveData extends IEffectEffectiveData
```

Módosíthatatlan objektum, amely egy tükrözési hatást képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | Meghatározza a kezdő alfa érték (százalék) pozícióját (az alfa színátmenet mentén). |
| [getEndPosAlpha()](#getEndPosAlpha--) | Megadja a végső alfa érték (százalék) pozícióját (az alfa színátmenet mentén). |
| [getFadeDirection()](#getFadeDirection--) | Megadja a tükrözés eltolásának irányát. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | Kezdő tükrözés átlátszósága. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | Végső tükrözés átlátszósága. |
| [getBlurRadius()](#getBlurRadius--) | Elmosódás sugara. |
| [getDirection()](#getDirection--) | A tükrözés iránya. |
| [getDistance()](#getDistance--) | A tükrözés távolsága. |
| [getRectangleAlign()](#getRectangleAlign--) | Téglalap igazítás. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Megadja a vízszintes ferdeség szögét. |
| [getSkewVertical()](#getSkewVertical--) | Megadja a függőleges ferdeség szögét. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Megadja, hogy a tükrözés forgatódjon-e a formával, ha a forma el van forgatva. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Megadja a vízszintes méretezési tényezőt, a negatív méretezés tükrözést eredményez. |
| [getScaleVertical()](#getScaleVertical--) | Megadja a függőleges méretezési tényezőt, a negatív méretezés tükrözést eredményez. |
### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

Meghatározza a kezdő alfa érték (százalék) pozícióját (az alfa színátmenet mentén). Csak olvasható float.

**Visszaad:**  
float
### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

Megadja a végső alfa érték (százalék) pozícióját (az alfa színátmenet mentén). Csak olvasható float.

**Visszaad:**  
float
### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

Megadja a tükrözés eltolásának irányát (szög). Csak olvasható float.

**Visszaad:**  
float
### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

Kezdeti tükrözés átlátszósága (százalék). Csak olvasható float.

**Visszaad:**  
float
### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

Végső tükrözés átlátszósága (százalék). Csak olvasható float.

**Visszaad:**  
float
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Elmosódás sugara. Csak olvasható double.

**Visszaad:**  
double
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

A tükrözés iránya. Csak olvasható float.

**Visszaad:**  
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

A tükrözés távolsága. Csak olvasható double.

**Visszaad:**  
double
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Téglalap igazítás. Csak olvasható [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Visszaad:**  
byte
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Megadja a vízszintes ferdeség szögét. Csak olvasható double.

**Visszaad:**  
double
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Megadja a függőleges ferdeség szögét. Csak olvasható double.

**Visszaad:**  
double
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Megadja, hogy a tükrözés forgatódjon-e a formával, ha a forma el van forgatva. Csak olvasható boolean.

**Visszaad:**  
boolean
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Megadja a vízszintes méretezési tényezőt, a negatív méretezés tükrözést eredményez (százalék). Csak olvasható double.

**Visszaad:**  
double
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Megadja a függőleges méretezési tényezőt, a negatív méretezés tükrözést eredményez (százalék). Csak olvasható double.

**Visszaad:**  
double