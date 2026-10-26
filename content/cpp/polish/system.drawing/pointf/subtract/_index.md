---
title: Subtract()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Odejmowane są wartości szerokości i wysokości określonego obiektu SizeF od wartości współrzędnych X i Y określonego obiektu PointF odpowiednio.
type: docs
weight: 157
url: /pl/system.drawing/pointf/subtract/
---
## PointF::Subtract(const PointF\&, const SizeF\&) metoda

Odejmowane są wartości szerokości i wysokości określonego [SizeF](../../sizef/) obiektu od wartości współrzędnych X i Y określonego [PointF](../) obiektu odpowiednio.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const SizeF &size)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| point | const [PointF](../)\& | Punkt do przemieszczenia |
| size | const [SizeF](../../sizef/)\& | Obiekt [SizeF](../../sizef/) określający wartości do odjęcia od wartości współrzędnych **point** |

### Wartość zwracana

Nowy obiekt [PointF](../), którego wartość współrzędnej X jest równa wynikowi odjęcia wartości szerokości **size** od wartości współrzędnej X **point**, a wartość współrzędnej Y jest równa wynikowi odjęcia wartości wysokości **size** od wartości współrzędnej Y **point**.

## PointF::Subtract(const PointF\&, const Size\&) metoda

Odejmowane są wartości szerokości i wysokości określonego [Size](../../size/) obiektu od wartości współrzędnych X i Y określonego [PointF](../) obiektu odpowiednio.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const Size &size)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| point | const [PointF](../)\& | Punkt do przemieszczenia |
| size | const [Size](../../size/)\& | Obiekt [Size](../../size/) określający wartości do odjęcia od wartości współrzędnych **point** |

### Wartość zwracana

Nowy obiekt [PointF](../), którego wartość współrzędnej X jest równa wynikowi odjęcia wartości szerokości **size** od wartości współrzędnej X **point**, a wartość współrzędnej Y jest równa wynikowi odjęcia wartości wysokości **size** od wartości współrzędnej Y **point**.

## Zobacz także

* Klasa [PointF](../)
* Klasa [SizeF](../../sizef/)
* Klasa [Size](../../size/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)