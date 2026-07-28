---
title: GraphicsPath()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy nową instancję klasy GraphicsPath z określonym trybem wypełnienia.
type: docs
weight: 1
url: /pl/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) constructor

Tworzy nową instancję klasy [GraphicsPath](../) z określonym trybem wypełnienia.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | Określa, w jaki sposób wnętrze zamkniętej ścieżki reprezentowanej przez tworzony obiekt powinno być wypełnione |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) constructor

Tworzy nową instancję obiektu [GraphicsPath](../), który reprezentuje określoną ścieżkę.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Tablica zawierająca punkty określające ścieżkę, którą ma reprezentować tworzony obiekt |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica zawierająca wartości określające typy odpowiadających punktów w tablicy **pts** |
| fillMode | [FillMode](../../fillmode/) | Określa, w jaki sposób wnętrze zamkniętej ścieżki reprezentowanej przez tworzony obiekt powinno być wypełnione |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) constructor

Tworzy nową instancję obiektu [GraphicsPath](../), który reprezentuje określoną ścieżkę.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Tablica zawierająca punkty określające ścieżkę, którą ma reprezentować tworzony obiekt |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica zawierająca wartości określające typy odpowiadających punktów w tablicy **pts** |
| fillMode | [FillMode](../../fillmode/) | Określa, w jaki sposób wnętrze zamkniętej ścieżki reprezentowanej przez tworzony obiekt powinno być wypełnione |

## GraphicsPath::GraphicsPath(const SkPath\&) constructor

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## Zobacz także

* Enum [FillMode](../../fillmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [GraphicsPath](../)
* Class [Point](../../../system.drawing/point/)
* Class [PointF](../../../system.drawing/pointf/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)