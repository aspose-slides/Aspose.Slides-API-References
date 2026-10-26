---
title: Rotation3D
second_title: Aspose.Slides dla Java – Dokumentacja API
description: Reprezentuje obrót 3D wykresu.
type: docs
url: /pl/com.aspose.slides/rotation3d/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

Reprezentuje obrót 3D wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getRotationX()](#getRotationX--) | Zwraca lub ustawia kąt obrotu wokół osi X, tj. |
| [setRotationX(byte value)](#setRotationX-byte-) | Zwraca lub ustawia kąt obrotu wokół osi X, tj. |
| [getRotationY()](#getRotationY--) | Zwraca lub ustawia kąt obrotu wokół osi Y, tj. |
| [setRotationY(int value)](#setRotationY-int-) | Zwraca lub ustawia kąt obrotu wokół osi Y, tj. |
| [getPerspective()](#getPerspective--) | Zwraca lub ustawia wartość perspektywy (kąt pola widzenia) dla wykresów 3D (od 0 do 240). |
| [setPerspective(byte value)](#setPerspective-byte-) | Zwraca lub ustawia wartość perspektywy (kąt pola widzenia) dla wykresów 3D (od 0 do 240). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Określa, czy osie wykresu są pod kątem prostym, zamiast rysowanych w perspektywie. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Określa, czy osie wykresu są pod kątem prostym, zamiast rysowanych w perspektywie. |
| [getDepthPercents()](#getDepthPercents--) | Zwraca lub ustawia głębokość wykresu 3D jako procent szerokości wykresu (od 20 do 2000 procent). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Zwraca lub ustawia głębokość wykresu 3D jako procent szerokości wykresu (od 20 do 2000 procent). |
| [getHeightPercents()](#getHeightPercents--) | Określa wysokość wykresu 3D jako procent szerokości wykresu (od 5 do 500 procent). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Określa wysokość wykresu 3D jako procent szerokości wykresu (od 5 do 500 procent). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```


Zwraca lub ustawia kąt obrotu wokół osi X, tj. w kierunku Y dla wykresów 3D (od -90 do 90 stopni). Właściwość odpowiada elementowi 21.2.2.157 rotX (X Rotation) w ECMA-376 oraz opcji „Y Rotation” w PowerPoint 2007+. odczyt/zapis byte.

**Zwraca:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```


Zwraca lub ustawia kąt obrotu wokół osi X, tj. w kierunku Y dla wykresów 3D (od -90 do 90 stopni). Właściwość odpowiada elementowi 21.2.2.157 rotX (X Rotation) w ECMA-376 oraz opcji „Y Rotation” w PowerPoint 2007+. odczyt/zapis byte.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```


Zwraca lub ustawia kąt obrotu wokół osi Y, tj. w kierunku X dla wykresów 3D (od 0 do 360 stopni). Właściwość odpowiada elementowi 21.2.2.158 rotY (Y Rotation) w ECMA-376 oraz opcji „X Rotation” w PowerPoint 2007+. odczyt/zapis int.

**Zwraca:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```


Zwraca lub ustawia kąt obrotu wokół osi Y, tj. w kierunku X dla wykresów 3D (od 0 do 360 stopni). Właściwość odpowiada elementowi 21.2.2.158 rotY (Y Rotation) w ECMA-376 oraz opcji „X Rotation” w PowerPoint 2007+. odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```


Zwraca lub ustawia wartość perspektywy (kąt pola widzenia) dla wykresów 3D (od 0 do 240). Ignorowane, jeśli wartość właściwości RightAngleAxes jest prawda. odczyt/zapis byte.

**Zwraca:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```


Zwraca lub ustawia wartość perspektywy (kąt pola widzenia) dla wykresów 3D (od 0 do 240). Ignorowane, jeśli wartość właściwości RightAngleAxes jest prawda. odczyt/zapis byte.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```


Określa, czy osie wykresu są pod kątem prostym, zamiast rysowanych w perspektywie. Innymi słowy określa, czy kąty osi wykresu są niezależne od obrotu lub pochylenia wykresu. odczyt/zapis boolean.

**Zwraca:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```


Określa, czy osie wykresu są pod kątem prostym, zamiast rysowanych w perspektywie. Innymi słowy określa, czy kąty osi wykresu są niezależne od obrotu lub pochylenia wykresu. odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```


Zwraca lub ustawia głębokość wykresu 3D jako procent szerokości wykresu (od 20 do 2000 procent). odczyt/zapis int.

**Zwraca:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```


Zwraca lub ustawia głębokość wykresu 3D jako procent szerokości wykresu (od 20 do 2000 procent). odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```


Określa wysokość wykresu 3D jako procent szerokości wykresu (od 5 do 500 procent). odczyt/zapis int.

**Zwraca:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```


Określa wysokość wykresu 3D jako procent szerokości wykresu (od 5 do 500 procent). odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject