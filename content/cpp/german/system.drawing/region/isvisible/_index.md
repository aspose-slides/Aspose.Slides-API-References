---
title: IsVisible()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob der angegebene Punkt innerhalb der Region liegt, die vom aktuellen Objekt repräsentiert wird.
type: docs
weight: 196
url: /de/system.drawing/region/isvisible/
---
## Region::IsVisible(const Point\&) const Methode

Bestimmt, ob der angegebene Punkt innerhalb der Region liegt, die vom aktuellen Objekt repräsentiert wird.

```cpp
bool System::Drawing::Region::IsVisible(const Point &point) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | const [Point](../../point/)\& | Der zu prüfende Punkt |

## Region::IsVisible(const PointF\&) const Methode

Bestimmt, ob der angegebene Punkt innerhalb der Region liegt, die vom aktuellen Objekt repräsentiert wird.

```cpp
bool System::Drawing::Region::IsVisible(const PointF &point) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | Der zu prüfende Punkt |

## Region::IsVisible(const Rectangle\&) Methode

Bestimmt, ob ein Teil des angegebenen Rechtecks innerhalb der Region liegt, die vom aktuellen Objekt repräsentiert wird.

```cpp
bool System::Drawing::Region::IsVisible(const Rectangle &rect)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Das zu prüfende Rechteck |

## Region::IsVisible(const RectangleF\&) Methode

Bestimmt, ob ein Teil des angegebenen Rechtecks innerhalb der Region liegt, die vom aktuellen Objekt repräsentiert wird.

```cpp
bool System::Drawing::Region::IsVisible(const RectangleF &rect)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Das zu prüfende Rechteck |

## Region::IsVisible(const Point\&, const SharedPtr\<Graphics\>\&) const Methode

Bestimmt, ob der angegebene Punkt innerhalb der Region liegt, die vom aktuellen Objekt unter Verwendung der angegebenen Grafik dargestellt wird.

```cpp
bool System::Drawing::Region::IsVisible(const Point &point, const SharedPtr<Graphics> &graphics) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | const [Point](../../point/)\& | Der zu prüfende Punkt |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Der Grafik-Kontext |

## Region::IsVisible(const PointF\&, const SharedPtr\<Graphics\>\&) const Methode

Bestimmt, ob der angegebene Punkt innerhalb der Region liegt, die vom aktuellen Objekt unter Verwendung der angegebenen Grafik dargestellt wird.

```cpp
bool System::Drawing::Region::IsVisible(const PointF &point, const SharedPtr<Graphics> &graphics) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | Der zu prüfende Punkt |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Der Grafik-Kontext |

## Region::IsVisible(const Rectangle\&, const SharedPtr\<Graphics\>\&) Methode

Bestimmt, ob ein Teil des angegebenen Rechtecks innerhalb der Region liegt, die vom aktuellen Objekt unter Verwendung der angegebenen Grafik dargestellt wird.

```cpp
bool System::Drawing::Region::IsVisible(const Rectangle &rect, const SharedPtr<Graphics> &graphics)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Das zu prüfende Rechteck |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Der Grafik-Kontext |

## Region::IsVisible(const RectangleF\&, const SharedPtr\<Graphics\>\&) Methode

Bestimmt, ob ein Teil des angegebenen Rechtecks innerhalb der Region liegt, die vom aktuellen Objekt unter Verwendung der angegebenen Grafik dargestellt wird.

```cpp
bool System::Drawing::Region::IsVisible(const RectangleF &rect, const SharedPtr<Graphics> &graphics)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Das zu prüfende Rechteck |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Der Grafik-Kontext |

## Region::IsVisible(float, float) const Methode

Bestimmt, ob der angegebene Punkt innerhalb der Region liegt, die vom aktuellen Objekt repräsentiert wird.

```cpp
bool System::Drawing::Region::IsVisible(float x, float y) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die X-Koordinate des zu prüfenden Punktes |
| y | **float** | Die Y-Koordinate des zu prüfenden Punktes |

## Region::IsVisible(float, float, const SharedPtr\<Graphics\>\&) const Methode

Bestimmt, ob der angegebene Punkt innerhalb der Region liegt, die vom aktuellen Objekt unter Verwendung der angegebenen Grafik dargestellt wird.

```cpp
bool System::Drawing::Region::IsVisible(float x, float y, const SharedPtr<Graphics> &graphics) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die X-Koordinate des zu prüfenden Punktes |
| y | **float** | Die Y-Koordinate des zu prüfenden Punktes |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Der Grafik-Kontext |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Point](../../point/)
* Klasse [Region](../)
* Klasse [PointF](../../pointf/)
* Klasse [Rectangle](../../rectangle/)
* Klasse [RectangleF](../../rectanglef/)
* Klasse [Graphics](../../graphics/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)