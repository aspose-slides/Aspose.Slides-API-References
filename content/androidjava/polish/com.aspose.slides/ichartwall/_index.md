---
title: IChartWall
second_title: Aspose.Slides na Androida za pośrednictwem Java API Reference
description: Reprezentuje ściany na wykresach 3D.
type: docs
url: /pl/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

Reprezentuje ściany na wykresach 3D.
## Metody

| Metoda | Opis |
| --- | --- |
| [getThickness()](#getThickness--) | Zwraca lub ustawia grubość ścian jako procent największego wymiaru objętości wykresu. |
| [setThickness(int value)](#setThickness-int-) | Zwraca lub ustawia grubość ścian jako procent największego wymiaru objętości wykresu. |
| [getFormat()](#getFormat--) | Zwraca wypełnienie ściany, linię, efekt, style 3D. |
| [getPictureType()](#getPictureType--) | Zwraca lub ustawia typ obrazu. |
| [setPictureType(int value)](#setPictureType-int-) | Zwraca lub ustawia typ obrazu. |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```


Zwraca lub ustawia grubość ścian jako procent największego wymiaru objętości wykresu. Odczyt/zapis int.

**Zwraca:**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```


Zwraca lub ustawia grubość ścian jako procent największego wymiaru objętości wykresu. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Zwraca wypełnienie ściany, linię, efekt, style 3D. Tylko do odczytu [IFormat](../../com.aspose.slides/iformat).

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```


Zwraca lub ustawia typ obrazu. Odczyt/zapis [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Zwraca:**
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```


Zwraca lub ustawia typ obrazu. Odczyt/zapis [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |