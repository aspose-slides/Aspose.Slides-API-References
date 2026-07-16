---
title: FillPolygon()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Remplit l'intérieur du polygone spécifié en utilisant le brush spécifié.
type: docs
weight: 417
url: /fr/system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) method

Remplit l'intérieur du polygone spécifié en utilisant le Brush spécifié.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un objet [Brush](../../brush/) qui spécifie les paramètres du remplissage |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Un tableau contenant les points qui définissent le polygone |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | Le mode de remplissage |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) method

Remplit l'intérieur du polygone spécifié en utilisant le Brush spécifié.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un objet [Brush](../../brush/) qui spécifie les paramètres du remplissage |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Un tableau contenant les points qui définissent le polygone |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | Le mode de remplissage |

## Voir aussi

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Brush](../../brush/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)