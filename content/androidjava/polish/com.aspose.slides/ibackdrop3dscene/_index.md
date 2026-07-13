---
title: IBackdrop3DScene
second_title: Aspose.Slides for Android via Java API Reference
description: Definiuje płaszczyznę, w której efekty, takie jak poświata i cień, są stosowane w odniesieniu do kształtu, do którego są stosowane.
type: docs
url: /pl/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Definiuje płaszczyznę, w której efekty, takie jak poświata i cień, są stosowane w odniesieniu do kształtu, do którego są stosowane.
## Metody

| Metoda | Opis |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Returns or sets a normal vector. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Returns or sets a normal vector. |
| [getAnchorPoint()](#getAnchorPoint--) | Returns or sets a point in 3D space. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Returns or sets a point in 3D space. |
| [getUpVector()](#getUpVector--) | Returns or sets a vector representing up. |
| [setUpVector(float[] value)](#setUpVector-float---) | Returns or sets a vector representing up. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```


Zwraca lub ustawia wektor normalny. Aby być precyzyjniejszym, ten atrybut definiuje wektor prostopadły do płaszczyzny tła. Wektor reprezentowany jako tablica 3 wartości float określających współrzędne X, Y i Z. **Odczyt/zapis** float[].

**Zwraca:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```


Zwraca lub ustawia wektor normalny. Aby być precyzyjniejszym, ten atrybut definiuje wektor prostopadły do płaszczyzny tła. Wektor reprezentowany jako tablica 3 wartości float określających współrzędne X, Y i Z. **Odczyt/zapis** float[].

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```


Zwraca lub ustawia punkt w przestrzeni 3D. Ten punkt jest punktem w przestrzeni, który zakotwicza płaszczyznę tła. Punkt 3D reprezentowany jako tablica 3 wartości float określających współrzędne X, Y i Z. **Odczyt/zapis** float[].

**Zwraca:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```


Zwraca lub ustawia punkt w przestrzeni 3D. Ten punkt jest punktem w przestrzeni, który zakotwicza płaszczyznę tła. Punkt 3D reprezentowany jako tablica 3 wartości float określających współrzędne X, Y i Z. **Odczyt/zapis** float[].

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```


Zwraca lub ustawia wektor wskazujący w górę. Aby być precyzyjniejszym, ten atrybut definiuje wektor wskazujący w górę w odniesieniu do płaszczyzny tła. Wektor reprezentowany jako tablica 3 wartości float określających współrzędne X, Y i Z. **Odczyt/zapis** float[].

**Zwraca:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```


Zwraca lub ustawia wektor wskazujący w górę. Aby być precyzyjniejszym, ten atrybut definiuje wektor wskazujący w górę w odniesieniu do płaszczyzny tła. Wektor reprezentowany jako tablica 3 wartości float określających współrzędne X, Y i Z. **Odczyt/zapis** float[].

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float[] |  |