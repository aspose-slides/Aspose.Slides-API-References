---
title: Point()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy nowy obiekt Point i inicjalizuje wartości współrzędnych X i Y wynoszące 0.
type: docs
weight: 1
url: /pl/system.drawing/point/point/
---
## Point::Point() konstruktor

Tworzy nowy obiekt [Point](../) i inicjalizuje jego wartości współrzędnych X i Y wynoszącymi 0.

```cpp
System::Drawing::Point::Point()
```

## Point::Point(int, int) konstruktor

Tworzy nowy obiekt [Point](../) i inicjalizuje go określonymi wartościami.

```cpp
System::Drawing::Point::Point(int x, int y)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | int | Wartość współrzędnej X |
| y | int | Wartość współrzędnej Y |

## Point::Point(const Size\&) konstruktor

Tworzy nowy obiekt [Point](../) i inicjalizuje jego wartości współrzędnych X i Y odpowiednio wartościami szerokości i wysokości określonego obiektu [SizeF](../../sizef/).

```cpp
System::Drawing::Point::Point(const Size &size)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| size | const [Size](../../size/)\& | Obiekt [SizeF](../../sizef/), którego wartości szerokości i wysokości są używane do zainicjowania wartości współrzędnych X i Y obiektu [Point](../) tworzonego |

## Point::Point(int) konstruktor

Tworzy nowy obiekt [Point](../) i inicjalizuje wartość współrzędnej X wartością utworzoną z wyższych 16 bitów podanego 32-bitowego liczby całkowitej oraz wartość współrzędnej Y wartością utworzoną z niższych 16 bitów tej samej liczby całkowitej.

```cpp
System::Drawing::Point::Point(int dw)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dw | int | 32-bitowa wartość całkowita, której wyższe 16 bitów określa wartość współrzędnej X, a niższe 16 bitów określa wartość współrzędnej Y tworzonego obiektu |

## Zobacz również

* Klasa [Point](../)
* Klasa [Size](../../size/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)