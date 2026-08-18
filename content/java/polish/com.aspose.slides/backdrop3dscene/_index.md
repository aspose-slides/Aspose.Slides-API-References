---
title: Backdrop3DScene
second_title: Aspose.Slides dla Java - odniesienie API
description: Definiuje płaszczyznę, w której efekty takie jak poświata i cień są stosowane w odniesieniu do kształtu, do którego są aplikowane.
type: docs
url: /pl/com.aspose.slides/backdrop3dscene/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Definiuje płaszczyznę, w której efekty, takie jak poświata i cień, są stosowane w odniesieniu do kształtu, do którego są stosowane.
## Metody

| Metoda | Opis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Returns or sets a normal vector. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Returns or sets a normal vector. |
| [getAnchorPoint()](#getAnchorPoint--) | Returns or sets a point in 3D space. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Returns or sets a point in 3D space. |
| [getUpVector()](#getUpVector--) | Returns or sets a vector representing up. |
| [setUpVector(float[] value)](#setUpVector-float---) | Returns or sets a vector representing up. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Wersja. Tylko do odczytu long.

**Zwraca:**
long
### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

Zwraca lub ustawia wektor normalny. Dokładniej, ten atrybut definiuje wektor prostopadły do powierzchni płaszczyzny tła. Wektor jest reprezentowany przez tablicę 3 wartości typu float, które określają współrzędne X, Y i Z. Odczyt/zapis float[].

**Zwraca:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

Zwraca lub ustawia wektor normalny. Dokładniej, ten atrybut definiuje wektor prostopadły do powierzchni płaszczyzny tła. Wektor jest reprezentowany przez tablicę 3 wartości typu float, które określają współrzędne X, Y i Z. Odczyt/zapis float[].

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

Zwraca lub ustawia punkt w przestrzeni 3D. Ten punkt jest punktem w przestrzeni, który anektuje płaszczyznę tła. Punkt 3D jest reprezentowany przez tablicę 3 wartości typu float, które określają współrzędne X, Y i Z. Odczyt/zapis float[].

**Zwraca:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

Zwraca lub ustawia punkt w przestrzeni 3D. Ten punkt jest punktem w przestrzeni, który anektuje płaszczyznę tła. Punkt 3D jest reprezentowany przez tablicę 3 wartości typu float, które określają współrzędne X, Y i Z. Odczyt/zapis float[].

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

Zwraca lub ustawia wektor reprezentujący kierunek w górę. Dokładniej, ten atrybut definiuje wektor reprezentujący kierunek w górę względem powierzchni płaszczyzny tła. Wektor jest reprezentowany przez tablicę 3 wartości typu float, które określają współrzędne X, Y i Z. Odczyt/zapis float[].

**Zwraca:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

Zwraca lub ustawia wektor reprezentujący kierunek w górę. Dokładniej, ten atrybut definiuje wektor reprezentujący kierunek w górę względem powierzchni płaszczyzny tła. Wektor jest reprezentowany przez tablicę 3 wartości typu float, które określają współrzędne X, Y i Z. Odczyt/zapis float[].

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float[] |  |