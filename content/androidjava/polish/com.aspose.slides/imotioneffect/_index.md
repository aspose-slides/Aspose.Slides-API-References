---
title: IMotionEffect
second_title: Aspose.Slides dla Androida – odwołanie do API Java
description: Reprezentuje zachowanie efektu ruchu.
type: docs
url: /pl/com.aspose.slides/imotioneffect/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Reprezentuje zachowanie efektu ruchu.

## Metody

| Metoda | Opis |
| --- | --- |
| [getFrom()](#getFrom--) | Określa współrzędną x/y, od której rozpoczyna się animacja (w procentach). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Określa współrzędną x/y, od której rozpoczyna się animacja (w procentach). |
| [getTo()](#getTo--) | Określa docelową lokalizację dla efektu ruchu animacji (w procentach). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Określa docelową lokalizację dla efektu ruchu animacji (w procentach). |
| [getBy()](#getBy--) | Opisuje względną wartość przesunięcia dla animacji (w procentach). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Opisuje względną wartość przesunięcia dla animacji (w procentach). |
| [getRotationCenter()](#getRotationCenter--) | Opisuje środek obrotu używany do obrotu ścieżki ruchu o kąt X. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Opisuje środek obrotu używany do obrotu ścieżki ruchu o kąt X. |
| [getOrigin()](#getOrigin--) | Określa, do czego odnosi się początek ścieżki ruchu, np. do układu slajdu lub elementu nadrzędnego. |
| [setOrigin(int value)](#setOrigin-int-) | Określa, do czego odnosi się początek ścieżki ruchu, np. do układu slajdu lub elementu nadrzędnego. |
| [getPath()](#getPath--) | Określa prymityw ścieżki, po którym następują współrzędne dla ruchu animacji. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Określa prymityw ścieżki, po którym następują współrzędne dla ruchu animacji. |
| [getPathEditMode()](#getPathEditMode--) | Określa, jak ścieżka ruchu przemieszcza się, gdy kształt jest przesuwany. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Określa, jak ścieżka ruchu przemieszcza się, gdy kształt jest przesuwany. |
| [getAngle()](#getAngle--) | Opisuje względny kąt ścieżki ruchu. |
| [setAngle(float value)](#setAngle-float-) | Opisuje względny kąt ścieżki ruchu. |

### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

Określa współrzędną x/y, od której rozpoczyna się animacja (w procentach). Odczyt/zapis android.graphics.PointF.

**Zwraca:**
android.graphics.PointF

### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

Określa współrzędną x/y, od której rozpoczyna się animacja (w procentach). Odczyt/zapis android.graphics.PointF.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```

Określa docelową lokalizację dla efektu ruchu animacji (w procentach). Odczyt/zapis android.graphics.PointF.

**Zwraca:**
android.graphics.PointF

### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

Określa docelową lokalizację dla efektu ruchu animacji (w procentach). Odczyt/zapis android.graphics.PointF.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```

Opisuje względną wartość przesunięcia dla animacji (w procentach). Odczyt/zapis android.graphics.PointF.

**Zwraca:**
android.graphics.PointF

### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

Opisuje względną wartość przesunięcia dla animacji (w procentach). Odczyt/zapis android.graphics.PointF.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```

Opisuje środek obrotu używany do obrotu ścieżki ruchu o kąt X. Odczyt/zapis android.graphics.PointF.

**Zwraca:**
android.graphics.PointF

### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```

Opisuje środek obrotu używany do obrotu ścieżki ruchu o kąt X. Odczyt/zapis android.graphics.PointF.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Określa, do czego odnosi się początek ścieżki ruchu, np. do układu slajdu lub elementu nadrzędnego. Odczyt/zapis [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Zwraca:**
int

### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Określa, do czego odnosi się początek ścieżki ruchu, np. do układu slajdu lub elementu nadrzędnego. Odczyt/zapis [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Określa prymityw ścieżki, po którym następują współrzędne dla ruchu animacji. Odczyt/zapis [IMotionPath](../../com.aspose.slides/imotionpath).

**Zwraca:**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Określa prymityw ścieżki, po którym następują współrzędne dla ruchu animacji. Odczyt/zapis [IMotionPath](../../com.aspose.slides/imotionpath).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Określa, jak ścieżka ruchu przemieszcza się, gdy kształt jest przesuwany. Odczyt/zapis [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Zwraca:**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Określa, jak ścieżka ruchu przemieszcza się, gdy kształt jest przesuwany. Odczyt/zapis [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Opisuje względny kąt ścieżki ruchu. Odczyt/zapis float.

**Zwraca:**
float

### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Opisuje względny kąt ścieżki ruchu. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |