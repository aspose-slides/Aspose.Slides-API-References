---
title: Complement()
second_title: Aspose.Slides für C++ API-Referenz
description: Ersetzt die durch das aktuelle Objekt dargestellte Region durch den Teil der Region, der durch das angegebene Rechteck definiert wird und nicht mit dieser Region überschneidet.
type: docs
weight: 131
url: /de/system.drawing/region/complement/
---
## Region::Complement(const RectangleF\&) Methode


Ersetzt die durch das aktuelle Objekt dargestellte Region durch den Teil der Region, der durch das angegebene Rechteck definiert wird und nicht mit dieser Region überschneidet.

```cpp
void System::Drawing::Region::Complement(const RectangleF &rect)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Ein Rechteck, das eine Region zum Ergänzen definiert |

## Region::Complement(const Rectangle\&) Methode


Ersetzt die durch das aktuelle Objekt dargestellte Region durch den Teil der Region, der durch das angegebene Rechteck definiert wird und nicht mit dieser Region überschneidet.

```cpp
void System::Drawing::Region::Complement(const Rectangle &rect)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Ein Rechteck, das eine Region zum Ergänzen definiert |

## Region::Complement(const SharedPtr\<Drawing2D::GraphicsPath\>\&) Methode


Ersetzt die durch das aktuelle Objekt dargestellte Region durch den Teil der Region, der durch den angegebenen Pfad definiert wird und nicht mit dieser Region überschneidet.

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Ein Pfad, der eine Region zum Ergänzen definiert |

## Region::Complement(const SharedPtr\<Region\>\&) Methode


Ersetzt die durch das aktuelle Objekt dargestellte Region durch den Teil der angegebenen Region, der nicht mit dieser Region überschneidet.

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Region> &region)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Eine Region zum Ergänzen |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [RectangleF](../../rectanglef/)
* Klasse [Region](../)
* Klasse [Rectangle](../../rectangle/)
* Klasse [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namensraum [System::Drawing](../../)
* Library [Aspose.Slides](../../../)