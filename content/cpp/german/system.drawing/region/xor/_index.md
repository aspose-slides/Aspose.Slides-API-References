---
title: Xor()
second_title: Aspose.Slides für C++ API-Referenz
description: Ersetzt die von dem aktuellen Objekt dargestellte Region durch die Teile dieser Region und der durch das angegebene Rechteck definierten Region, die nicht überschneiden.
type: docs
weight: 144
url: /de/system.drawing/region/xor/
---
## Region::Xor(const RectangleF\&) Methode


Ersetzt die von dem aktuellen Objekt dargestellte Region durch die Teile dieser Region und der durch das angegebene Rechteck definierten Region, die nicht überschneiden.

```cpp
void System::Drawing::Region::Xor(const RectangleF &rect)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Ein Rechteck, das eine Region definiert, die mit der von dem aktuellen Objekt dargestellten Region xor-verknüpft werden soll |

## Region::Xor(const Rectangle\&) Methode


Ersetzt die von dem aktuellen Objekt dargestellte Region durch die Teile dieser Region und der durch das angegebene Rechteck definierten Region, die nicht überschneiden.

```cpp
void System::Drawing::Region::Xor(const Rectangle &rect)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Ein Rechteck, das eine Region definiert, die mit der von dem aktuellen Objekt dargestellten Region xor-verknüpft werden soll |

## Region::Xor(const SharedPtr\<Drawing2D::GraphicsPath\>\&) Methode


Ersetzt die von dem aktuellen Objekt dargestellte Region durch die Teile dieser Region und dem durch den angegebenen Pfad definierten Region, die nicht überschneiden.

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Ein Pfad, der eine Region definiert, die mit der von dem aktuellen Objekt dargestellten Region xor-verknüpft werden soll |

## Region::Xor(const SharedPtr\<Region\>\&) Methode


Ersetzt die von dem aktuellen Objekt dargestellte Region durch die Teile dieser Region und der angegebenen Region, die nicht überschneiden.

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Region> &region)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Eine Region, die mit der von dem aktuellen Objekt dargestellten Region xor-verknüpft werden soll |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [RectangleF](../../rectanglef/)
* Klasse [Region](../)
* Klasse [Rectangle](../../rectangle/)
* Klasse [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)