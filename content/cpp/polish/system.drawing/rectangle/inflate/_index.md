---
title: Inflate()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Zwiększa szerokość i wysokość prostokąta reprezentowanego przez bieżący obiekt, zachowując położenie środka geometrycznego prostokąta. Szerokość i wysokość są zwiększane w obu kierunkach o podane wartości.
type: docs
weight: 261
url: /pl/system.drawing/rectangle/inflate/
---
## Rectangle::Inflate(int, int) metoda


Zwiększa szerokość i wysokość prostokąta reprezentowanego przez bieżący obiekt, zachowując położenie środka geometrycznego prostokąta. Szerokość i wysokość są zwiększane w obu kierunkach o podane wartości.

```cpp
void System::Drawing::Rectangle::Inflate(int width, int height)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| width | int | Wartość, o którą szerokość prostokąta ma zostać zwiększona w obu kierunkach |
| height | int | Wartość, o którą wysokość prostokąta ma zostać zwiększona w obu kierunkach |

## Rectangle::Inflate(const Size\&) metoda


Zwiększa szerokość i wysokość prostokąta reprezentowanego przez bieżący obiekt, zachowując położenie środka geometrycznego prostokąta. Szerokość i wysokość są zwiększane w obu kierunkach o wartości określone odpowiednio przez wartości width i height obiektu rozmiaru.

```cpp
void System::Drawing::Rectangle::Inflate(const Size &size)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| size | const [Size](../../size/)\& | Obiekt [Size](../../size/) określający wartości zwiększenia szerokości i wysokości prostokąta o |

## Rectangle::Inflate(const Rectangle\&, int, int) metoda


Zwiększa szerokość i wysokość prostokąta reprezentowanego przez podany obiekt, zachowując położenie środka geometrycznego prostokąta. Szerokość i wysokość są zwiększane w obu kierunkach o podane wartości.

```cpp
static Rectangle System::Drawing::Rectangle::Inflate(const Rectangle &rect, int x, int y)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | Prostokąt do pompowania |
| x | int | Wartość, o którą szerokość prostokąta ma zostać zwiększona w obu kierunkach |
| y | int | Wartość, o którą wysokość prostokąta ma zostać zwiększona w obu kierunkach |

### Wartość zwracana

Obiekt [Rectangle](../) reprezentujący powiększony prostokąt

## Zobacz także

* Klasa [Rectangle](../)
* Klasa [Size](../../size/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)