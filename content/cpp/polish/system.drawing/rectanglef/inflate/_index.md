---
title: Inflate()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Zwiększa szerokość i wysokość prostokąta reprezentowanego przez bieżący obiekt, zachowując położenie środka geometrycznego prostokąta. Szerokość i wysokość są zwiększane w obu kierunkach o podane wartości.
type: docs
weight: 261
url: /pl/system.drawing/rectanglef/inflate/
---
## RectangleF::Inflate(float, float) metoda


Zwiększa szerokość i wysokość prostokąta reprezentowanego przez bieżący obiekt, zachowując położenie środka geometrycznego prostokąta. Szerokość i wysokość są zwiększane w obu kierunkach o podane wartości.

```cpp
void System::Drawing::RectangleF::Inflate(float width, float height)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| width | **float** | Kwota, o którą szerokość prostokąta ma zostać zwiększona w obu kierunkach |
| height | **float** | Kwota, o którą wysokość prostokąta ma zostać zwiększona w obu kierunkach |

## RectangleF::Inflate(const SizeF&) metoda


Zwiększa szerokość i wysokość prostokąta reprezentowanego przez bieżący obiekt, zachowując położenie środka geometrycznego prostokąta. Szerokość i wysokość są zwiększane w obu kierunkach o wartości określone odpowiednio przez szerokość i wysokość podanego obiektu rozmiaru.

```cpp
void System::Drawing::RectangleF::Inflate(const SizeF &size)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| size | const [SizeF](../../sizef/)\& | Obiekt [SizeF](../../sizef/) określający kwoty, o które należy zwiększyć szerokość i wysokość prostokąta |

## RectangleF::Inflate(const RectangleF&, float, float) metoda


Zwiększa szerokość i wysokość prostokąta reprezentowanego przez podany obiekt, zachowując położenie środka geometrycznego prostokąta. Szerokość i wysokość są zwiększane w obu kierunkach o podane wartości.

```cpp
static RectangleF System::Drawing::RectangleF::Inflate(const RectangleF &rect, float x, float y)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | Prostokąt do powiększenia |
| x | **float** | Kwota, o którą szerokość prostokąta ma zostać zwiększona w obu kierunkach |
| y | **float** | Kwota, o którą wysokość prostokąta ma zostać zwiększona w obu kierunkach |

### Wartość zwracana

Obiekt [RectangleF](../) reprezentujący powiększony prostokąt

## Zobacz również

* Klasa [RectangleF](../)
* Klasa [SizeF](../../sizef/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)