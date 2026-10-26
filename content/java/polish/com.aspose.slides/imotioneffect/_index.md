---
title: IMotionEffect
second_title: Aspose.Slides dla Java – odniesienie API
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
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | Określa współrzędną x/y, od której rozpoczyna się animacja (w procentach). |
| [getTo()](#getTo--) | Określa docelową lokalizację efektu ruchu animacji (w procentach). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | Określa docelową lokalizację efektu ruchu animacji (w procentach). |
| [getBy()](#getBy--) | Opisuje względną wartość offsetu dla animacji (w procentach). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | Opisuje względną wartość offsetu dla animacji (w procentach). |
| [getRotationCenter()](#getRotationCenter--) | Opisuje środek obrotu używany do obracania ścieżki ruchu o kąt X. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | Opisuje środek obrotu używany do obracania ścieżki ruchu o kąt X. |
| [getOrigin()](#getOrigin--) | Określa, do czego odnosi się początek ścieżki ruchu, np. układ slajdu lub element nadrzędny. |
| [setOrigin(int value)](#setOrigin-int-) | Określa, do czego odnosi się początek ścieżki ruchu, np. układ slajdu lub element nadrzędny. |
| [getPath()](#getPath--) | Określa prymityw ścieżki, po którym następują współrzędne ruchu animacji. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Określa prymityw ścieżki, po którym następują współrzędne ruchu animacji. |
| [getPathEditMode()](#getPathEditMode--) | Określa, jak ścieżka ruchu przemieszcza się, gdy kształt jest przemieszczany. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Określa, jak ścieżka ruchu przemieszcza się, gdy kształt jest przemieszczany. |
| [getAngle()](#getAngle--) | Opisuje względny kąt ścieżki ruchu. |
| [setAngle(float value)](#setAngle-float-) | Opisuje względny kąt ścieżki ruchu. |

### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

Określa współrzędną x/y, od której rozpoczyna się animacja (w procentach). Odczyt/zapis java.awt.geom.Point2D.Float.

**Zwraca:**
java.awt.geom.Point2D.Float

### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

Określa współrzędną x/y, od której rozpoczyna się animacja (w procentach). Odczyt/zapis java.awt.geom.Point2D.Float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

Określa docelową lokalizację efektu ruchu animacji (w procentach). Odczyt/zapis java.awt.geom.Point2D.Float.

**Zwraca:**
java.awt.geom.Point2D.Float

### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

Określa docelową lokalizację efektu ruchu animacji (w procentach). Odczyt/zapis java.awt.geom.Point2D.Float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

Opisuje względną wartość offsetu dla animacji (w procentach). Odczyt/zapis java.awt.geom.Point2D.Float.

**Zwraca:**
java.awt.geom.Point2D.Float

### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

Opisuje względną wartość offsetu dla animacji (w procentach). Odczyt/zapis java.awt.geom.Point2D.Float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```

Opisuje środek obrotu używany do obracania ścieżki ruchu o kąt X. Odczyt/zapis java.awt.geom.Point2D.Float.

**Zwraca:**
java.awt.geom.Point2D.Float

### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```

Opisuje środek obrotu używany do obracania ścieżki ruchu o kąt X. Odczyt/zapis java.awt.geom.Point2D.Float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Określa, do czego odnosi się początek ścieżki ruchu, np. układ slajdu lub element nadrzędny. Odczyt/zapis [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Zwraca:**
int

### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Określa, do czego odnosi się początek ścieżki ruchu, np. układ slajdu lub element nadrzędny. Odczyt/zapis [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Określa prymityw ścieżki, po którym następują współrzędne ruchu animacji. Odczyt/zapis [IMotionPath](../../com.aspose.slides/imotionpath).

**Zwraca:**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Określa prymityw ścieżki, po którym następują współrzędne ruchu animacji. Odczyt/zapis [IMotionPath](../../com.aspose.slides/imotionpath).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Określa, jak ścieżka ruchu przemieszcza się, gdy kształt jest przemieszczany. Odczyt/zapis [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Zwraca:**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Określa, jak ścieżka ruchu przemieszcza się, gdy kształt jest przemieszczany. Odczyt/zapis [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

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