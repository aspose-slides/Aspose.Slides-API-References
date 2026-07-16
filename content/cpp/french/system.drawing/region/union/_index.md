---
title: Union()
second_title: Référence de l'API Aspose.Slides pour C++
description: Remplace la région représentée par l'objet actuel par le résultat de l'opération d'union de cette région et d'une région définie par le rectangle spécifié.
type: docs
weight: 53
url: /fr/system.drawing/region/union/
---
## Region::Union(const RectangleF\&) méthode

Remplace la région représentée par l'objet actuel par le résultat de l'opération d'union de cette région et d'une région définie par le rectangle spécifié.

```cpp
void System::Drawing::Region::Union(const RectangleF &rect)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Un rectangle qui définit une région à unir à cette région |

## Region::Union(const Rectangle\&) méthode

Remplace la région représentée par l'objet actuel par le résultat de l'union de cette région et d'une région définie par le rectangle spécifié.

```cpp
void System::Drawing::Region::Union(const Rectangle &rect)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Un rectangle qui définit une région à unir à cette région |

## Region::Union(const SharedPtr\<Drawing2D::GraphicsPath\>\&) méthode

Remplace la région représentée par l'objet actuel par le résultat de l'union de cette région et d'une région définie par le chemin spécifié.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Un chemin qui définit une région à unir à cette région |

## Region::Union(const SharedPtr\<Region\>\&) méthode

Remplace la région représentée par l'objet actuel par le résultat de l'union de cette région et de la région spécifiée.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Region> &region)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Une région à unir à cette région |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RectangleF](../../rectanglef/)
* Classe [Region](../)
* Classe [Rectangle](../../rectangle/)
* Classe [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)