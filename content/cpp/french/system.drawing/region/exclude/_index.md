---
title: Exclude()
second_title: Référence de l'API Aspose.Slides pour C++
description: Remplace la région représentée par l'objet actuel par le résultat de l'exclusion de la région définie par le rectangle spécifié.
type: docs
weight: 92
url: /fr/system.drawing/region/exclude/
---
## Region::Exclude(const RectangleF\&) méthode

Remplace la région représentée par l'objet actuel par le résultat de l’exclusion de la région définie par le rectangle spécifié.

```cpp
void System::Drawing::Region::Exclude(const RectangleF &rect)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Un rectangle qui définit une région à exclure |

## Region::Exclude(const Rectangle\&) méthode

Remplace la région représentée par l'objet actuel par le résultat de l’exclusion de la région définie par le rectangle spécifié.

```cpp
void System::Drawing::Region::Exclude(const Rectangle &rect)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Un rectangle qui définit une région à exclure |

## Region::Exclude(const SharedPtr\<Drawing2D::GraphicsPath\>\&) méthode

Remplace la région représentée par l'objet actuel par le résultat de l’exclusion de la région définie par le chemin spécifié.

```cpp
void System::Drawing::Region::Exclude(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Un tracé qui définit une région à exclure |

## Region::Exclude(const SharedPtr\<Region\>\&) méthode

Remplace la région représentée par l'objet actuel par le résultat de l’exclusion de la région spécifiée.

```cpp
void System::Drawing::Region::Exclude(const SharedPtr<Region> &region)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Une région à exclure |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RectangleF](../../rectanglef/)
* Classe [Region](../)
* Classe [Rectangle](../../rectangle/)
* Classe [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)