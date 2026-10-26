---
title: Add()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Dodaje wartości szerokości i wysokości określonego obiektu SizeF do wartości współrzędnych X i Y określonego obiektu PointF odpowiednio.
type: docs
weight: 144
url: /pl/system.drawing/pointf/add/
---
## PointF::Add(const PointF\&, const SizeF\&) metoda

Dodaje wartości szerokości i wysokości określonego [SizeF](../../sizef/) obiektu do wartości współrzędnych X i Y określonego [PointF](../) obiektu odpowiednio.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const SizeF &size)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| point | const [PointF](../)\& | Punkt do przetłumaczenia |
| size | const [SizeF](../../sizef/)\& | Obiekt [SizeF](../../sizef/) określający wartości do dodania do współrzędnych **point** |

### Wartość zwracana

Nowy [PointF](../) obiekt, którego wartość współrzędnej X jest równa sumie wartości współrzędnej X **point** i wartości szerokości **size**, a wartość współrzędnej Y jest równa sumie wartości współrzędnej Y **point** i wartości wysokości **size**.

## PointF::Add(const PointF\&, const Size\&) metoda

Dodaje wartości szerokości i wysokości określonego [Size](../../size/) obiektu do wartości współrzędnych X i Y określonego [PointF](../) obiektu odpowiednio.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const Size &size)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| point | const [PointF](../)\& | Punkt do przetłumaczenia |
| size | const [Size](../../size/)\& | Obiekt [Size](../../size/) określający wartości do dodania do współrzędnych **point** |

### Wartość zwracana

Nowy [PointF](../) obiekt, którego wartość współrzędnej X jest równa sumie wartości współrzędnej X **point** i wartości szerokości **size**, a wartość współrzędnej Y jest równa sumie wartości współrzędnej Y **point** i wartości wysokości **size**.

## Zobacz także

* Klasa [PointF](../)
* Klasa [SizeF](../../sizef/)
* Klasa [Size](../../size/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)