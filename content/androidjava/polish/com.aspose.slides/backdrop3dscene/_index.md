---
title: Backdrop3DScene
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Definiuje płaszczyznę, w której efekty takie jak poświata i cień są stosowane w odniesieniu do kształtu, do którego są aplikowane.
type: docs
url: /pl/com.aspose.slides/backdrop3dscene/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**  
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)  
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Definiuje płaszczyznę, w której efekty, takie jak poświata i cień, są stosowane w odniesieniu do kształtu, do którego są aplikowane.

## Metody

| Metoda | Opis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Zwraca lub ustawia wektor normalny. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Zwraca lub ustawia wektor normalny. |
| [getAnchorPoint()](#getAnchorPoint--) | Zwraca lub ustawia punkt w przestrzeni 3D. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Zwraca lub ustawia punkt w przestrzeni 3D. |
| [getUpVector()](#getUpVector--) | Zwraca lub ustawia wektor wskazujący kierunek w górę. |
| [setUpVector(float[] value)](#setUpVector-float---) | Zwraca lub ustawia wektor wskazujący kierunek w górę. |

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

Zwraca lub ustawia wektor normalny. Dokładniej, ten atrybut definiuje wektor prostopadły do płaszczyzny tła. Wektor jest reprezentowany przez tablicę 3 wartości float określających współrzędne X, Y i Z. Odczyt/zapis float[].

**Zwraca:**  
float[]

### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

Zwraca lub ustawia wektor normalny. Dokładniej, ten atrybut definiuje wektor prostopadły do płaszczyzny tła. Wektor jest reprezentowany przez tablicę 3 wartości float określających współrzędne X, Y i Z. Odczyt/zapis float[].

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

Zwraca lub ustawia punkt w przestrzeni 3D. Ten punkt jest punktem w przestrzeni, który ustawia płaszczyznę tła. Punkt 3D jest reprezentowany przez tablicę 3 wartości float określających współrzędne X, Y i Z. Odczyt/zapis float[].

**Zwraca:**  
float[]

### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

Zwraca lub ustawia punkt w przestrzeni 3D. Ten punkt jest punktem w przestrzeni, który ustawia płaszczyznę tła. Punkt 3D jest reprezentowany przez tablicę 3 wartości float określających współrzędne X, Y i Z. Odczyt/zapis float[].

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

Zwraca lub ustawia wektor wskazujący kierunek w górę. Dokładniej, ten atrybut definiuje wektor wskazujący kierunek w górę w odniesieniu do płaszczyzny tła. Wektor jest reprezentowany przez tablicę 3 wartości float określających współrzędne X, Y i Z. Odczyt/zapis float[].

**Zwraca:**  
float[]

### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

Zwraca lub ustawia wektor wskazujący kierunek w górę. Dokładniej, ten atrybut definiuje wektor wskazujący kierunek w górę w odniesieniu do płaszczyzny tła. Wektor jest reprezentowany przez tablicę 3 wartości float określających współrzędne X, Y i Z. Odczyt/zapis float[].

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float[] |  |