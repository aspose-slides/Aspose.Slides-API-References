---
title: GraphicsPath()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une nouvelle instance de la classe GraphicsPath avec le mode de remplissage spécifié.
type: docs
weight: 1
url: /fr/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) constructeur

Construit une nouvelle instance de la classe [GraphicsPath](../) avec le mode de remplissage spécifié.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | Spécifie comment l'intérieur du chemin fermé représenté par l'objet en cours de création doit être rempli |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) constructeur

Construit une nouvelle instance de l'objet [GraphicsPath](../) qui représente le chemin spécifié.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Un tableau contenant les points qui spécifient le chemin à représenter par l'objet en cours de création |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Un tableau contenant les valeurs qui spécifient les types des points correspondants dans le tableau **pts** |
| fillMode | [FillMode](../../fillmode/) | Spécifie comment l'intérieur du chemin fermé représenté par l'objet en cours de création doit être rempli |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) constructeur

Construit une nouvelle instance de l'objet [GraphicsPath](../) qui représente le chemin spécifié.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Un tableau contenant les points qui spécifient le chemin à représenter par l'objet en cours de création |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Un tableau contenant les valeurs qui spécifient les types des points correspondants dans le tableau **pts** |
| fillMode | [FillMode](../../fillmode/) | Spécifie comment l'intérieur du chemin fermé représenté par l'objet en cours de création doit être rempli |

## GraphicsPath::GraphicsPath(const SkPath\&) constructeur

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## Voir aussi

* Enum [FillMode](../../fillmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [GraphicsPath](../)
* Class [Point](../../../system.drawing/point/)
* Class [PointF](../../../system.drawing/pointf/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)