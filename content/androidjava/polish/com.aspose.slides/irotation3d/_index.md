---
title: IRotation3D
second_title: Aspose.Slides dla Androida przy użyciu Java API Reference
description: Reprezentuje trójwymiarową rotację wykresu.
type: docs
url: /pl/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

Reprezentuje trójwymiarową rotację wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getRotationX()](#getRotationX--) | Zwraca lub ustawia stopień rotacji wokół osi X, tj. |
| [setRotationX(byte value)](#setRotationX-byte-) | Zwraca lub ustawia stopień rotacji wokół osi X, tj. |
| [getRotationY()](#getRotationY--) | Zwraca lub ustawia stopień rotacji wokół osi Y, tj. |
| [setRotationY(int value)](#setRotationY-int-) | Zwraca lub ustawia stopień rotacji wokół osi Y, tj. |
| [getPerspective()](#getPerspective--) | Zwraca lub ustawia wartość perspektywy (kąt pola widzenia) dla wykresów 3D (od 0 do 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | Zwraca lub ustawia wartość perspektywy (kąt pola widzenia) dla wykresów 3D (od 0 do 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Określa, czy osie wykresu są pod kątem prostym, a nie rysowane w perspektywie. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Określa, czy osie wykresu są pod kątem prostym, a nie rysowane w perspektywie. |
| [getDepthPercents()](#getDepthPercents--) | Zwraca lub ustawia głębokość wykresu 3D jako procent szerokości wykresu (od 20 do 2000 procent). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Zwraca lub ustawia głębokość wykresu 3D jako procent szerokości wykresu (od 20 do 2000 procent). |
| [getHeightPercents()](#getHeightPercents--) | Określa wysokość wykresu 3D jako procent szerokości wykresu (od 5 do 500 procent). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Określa wysokość wykresu 3D jako procent szerokości wykresu (od 5 do 500 procent). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

Zwraca lub ustawia stopień rotacji wokół osi X, tj. w kierunku Y dla wykresów 3D (od -90 do 90 stopni). Właściwość odpowiada elementowi 21.2.2.157 rotX (X Rotation) w ECMA-376 oraz opcji “Y Rotation” w PowerPoint 2007+. Odczyt/zapis byte.

**Zwraca:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

Zwraca lub ustawia stopień rotacji wokół osi X, tj. w kierunku Y dla wykresów 3D (od -90 do 90 stopni). Właściwość odpowiada elementowi 21.2.157 rotX (X Rotation) w ECMA-376 oraz opcji “Y Rotation” w PowerPoint 2007+. Odczyt/zapis byte.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Zwraca lub ustawia stopień rotacji wokół osi Y, tj. w kierunku X dla wykresów 3D (od 0 do 360 stopni). Właściwość odpowiada elementowi 21.2.2.158 rotY (Y Rotation) w ECMA-376 oraz opcji “X Rotation” w PowerPoint 2007+. Odczyt/zapis int.

**Zwraca:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Zwraca lub ustawia stopień rotacji wokół osi Y, tj. w kierunku X dla wykresów 3D (od 0 do 360 stopni). Właściwość odpowiada elementowi 21.2.2.158 rotY (Y Rotation) w ECMA-376 oraz opcji “X Rotation” w PowerPoint 2007+. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

Zwraca lub ustawia wartość perspektywy (kąt pola widzenia) dla wykresów 3D (od 0 do 100). Ignorowane, jeśli wartość właściwości RightAngleAxes jest prawdziwa. Odczyt/zapis byte.

**Zwraca:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

Zwraca lub ustawia wartość perspektywy (kąt pola widzenia) dla wykresów 3D (od 0 do 100). Ignorowane, jeśli wartość właściwości RightAngleAxes jest prawdziwa. Odczyt/zapis byte.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

Określa, czy osie wykresu są pod kątem prostym, a nie rysowane w perspektywie. Inaczej mówiąc, określa, czy kąty osi wykresu są niezależne od rotacji lub elewacji wykresu. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

Określa, czy osie wykresu są pod kątem prostym, a nie rysowane w perspektywie. Inaczej mówiąc, określa, czy kąty osi wykresu są niezależne od rotacji lub elewacji wykresu. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

Zwraca lub ustawia głębokość wykresu 3D jako procent szerokości wykresu (od 20 do 2000 procent). Odczyt/zapis int.

**Zwraca:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

Zwraca lub ustawia głębokość wykresu 3D jako procent szerokości wykresu (od 20 do 2000 procent). Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

Określa wysokość wykresu 3D jako procent szerokości wykresu (od 5 do 500 procent). Odczyt/zapis int.

**Zwraca:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

Określa wysokość wykresu 3D jako procent szerokości wykresu (od 5 do 500 procent). Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |