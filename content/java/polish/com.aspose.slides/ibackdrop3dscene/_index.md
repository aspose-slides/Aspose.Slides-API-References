---
title: IBackdrop3DScene
second_title: Aspose.Slides for Java API Reference
description: Defines a plane in which effects such as glow and shadow are applied in relation to the shape they are being applied to.
type: docs
url: /pl/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Definiuje płaszczyznę, w której efekty, takie jak poświata i cień, są stosowane w odniesieniu do kształtu, do którego są stosowane.
## Metody

| Metoda | Opis |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Zwraca lub ustawia wektor normalny. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Zwraca lub ustawia wektor normalny. |
| [getAnchorPoint()](#getAnchorPoint--) | Zwraca lub ustawia punkt w przestrzeni 3D. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Zwraca lub ustawia punkt w przestrzeni 3D. |
| [getUpVector()](#getUpVector--) | Zwraca lub ustawia wektor reprezentujący kierunek w górę. |
| [setUpVector(float[] value)](#setUpVector-float---) | Zwraca lub ustawia wektor reprezentujący kierunek w górę. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

Zwraca lub ustawia wektor normalny. Dokładniej, ten atrybut definiuje wektor prostopadły do powierzchni płaszczyzny tła. Wektor jest reprezentowany przez tablicę 3 wartości typu float, które określają współrzędne X, Y i Z. Odczyt/zapis float[].

**Zwraca:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

Zwraca lub ustawia wektor normalny. Dokładniej, ten atrybut definiuje wektor prostopadły do powierzchni płaszczyzny tła. Wektor jest reprezentowany przez tablicę 3 wartości typu float, które określają współrzędne X, Y i Z. Odczyt/zapis float[].

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

Zwraca lub ustawia punkt w przestrzeni 3D. Ten punkt jest punktem w przestrzeni, który zakotwicza płaszczyznę tła. Punkt 3D jest reprezentowany przez tablicę 3 wartości typu float, które określają współrzędne X, Y i Z. Odczyt/zapis float[].

**Zwraca:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

Zwraca lub ustawia punkt w przestrzeni 3D. Ten punkt jest punktem w przestrzeni, który zakotwicza płaszczyznę tła. Punkt 3D jest reprezentowany przez tablicę 3 wartości typu float, które określają współrzędne X, Y i Z. Odczyt/zapis float[].

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

Zwraca lub ustawia wektor reprezentujący kierunek w górę. Dokładniej, ten atrybut definiuje wektor reprezentujący kierunek w górę w odniesieniu do powierzchni płaszczyzny tła. Wektor jest reprezentowany przez tablicę 3 wartości typu float, które określają współrzędne X, Y i Z. Odczyt/zapis float[].

**Zwraca:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

Zwraca lub ustawia wektor reprezentujący kierunek w górę. Dokładniej, ten atrybut definiuje wektor reprezentujący kierunek w górę w odniesieniu do powierzchni płaszczyzny tła. Wektor jest reprezentowany przez tablicę 3 wartości typu float, które określają współrzędne X, Y i Z. Odczyt/zapis float[].

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float[] |  |