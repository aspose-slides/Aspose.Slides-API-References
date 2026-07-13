---
title: MotionEffect
second_title: Aspose.Slides dla Androida – Java API Reference
description: Reprezentuje zachowanie efektu ruchu.
type: docs
url: /pl/com.aspose.slides/motioneffect/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)
```
public class MotionEffect extends Behavior implements IMotionEffect
```

Reprezentuje zachowanie efektu ruchu.

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |

## Metody

| Metoda | Opis |
| --- | --- |
| [getFrom()](#getFrom--) | Określa współrzędne x/y, z których rozpoczyna się animacja (w procentach). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Określa współrzędne x/y, z których rozpoczyna się animacja (w procentach). |
| [getTo()](#getTo--) | Określa docelową lokalizację efektu ruchu animacji (w procentach). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Określa docelową lokalizację efektu ruchu animacji (w procentach). |
| [getBy()](#getBy--) | Opisuje względną wartość offsetu dla animacji (w procentach). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Opisuje względną wartość offsetu dla animacji (w procentach). |
| [getRotationCenter()](#getRotationCenter--) | Opisuje środek obrotu używany do obrotu ścieżki ruchu o kąt X. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Opisuje środek obrotu używany do obrotu ścieżki ruchu o kąt X. |
| [getOrigin()](#getOrigin--) | Określa, względem czego jest pochodzenie ścieżki ruchu, np. układu slajdu lub elementu nadrzędnego. |
| [setOrigin(int value)](#setOrigin-int-) | Określa, względem czego jest pochodzenie ścieżki ruchu, np. układu slajdu lub elementu nadrzędnego. |
| [getPath()](#getPath--) | Określa prymityw ścieżki, po którym następują współrzędne ruchu animacji. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Określa prymityw ścieżki, po którym następują współrzędne ruchu animacji. |
| [getPathEditMode()](#getPathEditMode--) | Określa, jak ścieżka ruchu porusza się, gdy kształt jest przemieszczany. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Określa, jak ścieżka ruchu porusza się, gdy kształt jest przemieszczany. |
| [getAngle()](#getAngle--) | Opisuje względny kąt ścieżki ruchu. |
| [setAngle(float value)](#setAngle-float-) | Opisuje względny kąt ścieżki ruchu. |

### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```

### getFrom() {#getFrom--}
```
public final PointF getFrom()
```

Określa współrzędne x/y, z których rozpoczyna się animacja (w procentach). Odczyt/zapis android.graphics.PointF.

**Zwraca:**
android.graphics.PointF

### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public final void setFrom(PointF value)
```

Określa współrzędne x/y, z których rozpoczyna się animacja (w procentach). Odczyt/zapis android.graphics.PointF.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public final PointF getTo()
```

Określa docelową lokalizację efektu ruchu animacji (w procentach). Odczyt/zapis android.graphics.PointF.

**Zwraca:**
android.graphics.PointF

### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public final void setTo(PointF value)
```

Określa docelową lokalizację efektu ruchu animacji (w procentach). Odczyt/zapis android.graphics.PointF.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public final PointF getBy()
```

Opisuje względną wartość offsetu dla animacji (w procentach). Odczyt/zapis android.graphics.PointF.

**Zwraca:**
android.graphics.PointF

### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public final void setBy(PointF value)
```

Opisuje względną wartość offsetu dla animacji (w procentach). Odczyt/zapis android.graphics.PointF.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public final PointF getRotationCenter()
```

Opisuje środek obrotu używany do obrotu ścieżki ruchu o kąt X. Odczyt/zapis android.graphics.PointF.

**Zwraca:**
android.graphics.PointF

### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public final void setRotationCenter(PointF value)
```

Opisuje środek obrotu używany do obrotu ścieżki ruchu o kąt X. Odczyt/zapis android.graphics.PointF.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```

Określa, względem czego jest pochodzenie ścieżki ruchu, np. układu slajdu lub elementu nadrzędnego. Odczyt/zapis [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Zwraca:**
int

### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```

Określa, względem czego jest pochodzenie ścieżki ruchu, np. układu slajdu lub elementu nadrzędnego. Odczyt/zapis [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```

Określa prymityw ścieżki, po którym następują współrzędne ruchu animacji. Odczyt/zapis [IMotionPath](../../com.aspose.slides/imotionpath).

**Zwraca:**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```

Określa prymityw ścieżki, po którym następują współrzędne ruchu animacji. Odczyt/zapis [IMotionPath](../../com.aspose.slides/imotionpath).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```

Określa, jak ścieżka ruchu porusza się, gdy kształt jest przemieszczany. Odczyt/zapis [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Zwraca:**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```

Określa, jak ścieżka ruchu porusza się, gdy kształt jest przemieszczany. Odczyt/zapis [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```

Opisuje względny kąt ścieżki ruchu. Odczyt/zapis float.

**Zwraca:**
float

### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```

Opisuje względny kąt ścieżki ruchu. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |