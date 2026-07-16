---
title: Complement()
second_title: Référence de l'API Aspose.Slides pour C++
description: Remplace la région représentée par l'objet actuel par la partie de la région définie par le rectangle spécifié qui n'intersecte pas cette région.
type: docs
weight: 131
url: /fr/system.drawing/region/complement/
---
## Region::Complement(const RectangleF\&) méthode


Remplace la région représentée par l'objet actuel par la partie de la région définie par le rectangle spécifié qui n’intersecte pas cette région.

```cpp
void System::Drawing::Region::Complement(const RectangleF &rect)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Un rectangle qui définit une région à compléter |

## Region::Complement(const Rectangle\&) méthode


Remplace la région représentée par l'objet actuel par la partie de la région définie par le rectangle spécifié qui n’intersecte pas cette région.

```cpp
void System::Drawing::Region::Complement(const Rectangle &rect)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Un rectangle qui définit une région à compléter |

## Region::Complement(const SharedPtr\<Drawing2D::GraphicsPath\>\&) méthode


Remplace la région représentée par l'objet actuel par la partie de la région définie par le chemin spécifié qui n’intersecte pas cette région.

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Un chemin qui définit une région à compléter |

## Region::Complement(const SharedPtr\<Region\>\&) méthode


Remplace la région représentée par l'objet actuel par la partie de la région spécifiée qui n’intersecte pas cette région.

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Region> &region)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Une région à compléter |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RectangleF](../../rectanglef/)
* Class [Region](../)
* Class [Rectangle](../../rectangle/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)