---
title: Complement()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Nahrazuje oblast reprezentovanou aktuálním objektem částí oblasti definovanou zadaným obdélníkem, která se s touto oblastí nepřekrývá.
type: docs
weight: 131
url: /cs/system.drawing/region/complement/
---
## Region::Complement(const RectangleF\&) metoda


Nahrazuje oblast reprezentovanou aktuálním objektem částí oblasti definované zadaným obdélníkem, která se s touto oblastí nesetkává.

```cpp
void System::Drawing::Region::Complement(const RectangleF &rect)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Obdélník, který určuje oblast k doplnění |

## Region::Complement(const Rectangle\&) metoda


Nahrazuje oblast reprezentovanou aktuálním objektem částí oblasti definované zadaným obdélníkem, která se s touto oblastí nesetkává.

```cpp
void System::Drawing::Region::Complement(const Rectangle &rect)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Obdélník, který určuje oblast k doplnění |

## Region::Complement(const SharedPtr\<Drawing2D::GraphicsPath\>\&) metoda


Nahrazuje oblast reprezentovanou aktuálním objektem částí oblasti definované zadanou cestou, která se s touto oblastí nesetkává.

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Cesta, která určuje oblast k doplnění |

## Region::Complement(const SharedPtr\<Region\>\&) metoda


Nahrazuje oblast reprezentovanou aktuálním objektem částí zadané oblasti, která se s touto oblastí nesetkává.

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Region> &region)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Oblast k doplnění |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [RectangleF](../../rectanglef/)
* Třída [Region](../)
* Třída [Rectangle](../../rectangle/)
* Třída [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)