---
title: Xor()
second_title: Référence de l'API Aspose.Slides pour C++
description: Remplace la région représentée par l'objet actuel par les portions de cette région et de la région définie par le rectangle spécifié qui ne s'intersectent pas.
type: docs
weight: 144
url: /fr/system.drawing/region/xor/
---
## Region::Xor(const RectangleF\&) méthode


Remplace la région représentée par l'objet actuel par les portions de cette région et de la région définie par le rectangle spécifié qui ne s'intersectent pas.

```cpp
void System::Drawing::Region::Xor(const RectangleF &rect)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Un rectangle qui définit une région à xor avec la région représentée par l'objet actuel |

## Region::Xor(const Rectangle\&) méthode


Remplace la région représentée par l'objet actuel par les portions de cette région et de la région définie par le rectangle spécifié qui ne s'intersectent pas.

```cpp
void System::Drawing::Region::Xor(const Rectangle &rect)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Un rectangle qui définit une région à xor avec la région représentée par l'objet actuel |

## Region::Xor(const SharedPtr\<Drawing2D::GraphicsPath\>\&) méthode


Remplace la région représentée par l'objet actuel par les portions de cette région et du chemin spécifié qui ne s'intersectent pas.

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Un chemin qui définit une région à xor avec la région représentée par l'objet actuel |

## Region::Xor(const SharedPtr\<Region\>\&) méthode


Remplace la région représentée par l'objet actuel par les portions de cette région et de la région spécifiée qui ne s'intersectent pas.

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Region> &region)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Une région à xor avec la région représentée par l'objet actuel |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RectangleF](../../rectanglef/)
* Classe [Region](../)
* Classe [Rectangle](../../rectangle/)
* Classe [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)