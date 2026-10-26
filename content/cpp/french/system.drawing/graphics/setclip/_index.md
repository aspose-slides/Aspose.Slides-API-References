---
title: SetClip()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Définit la région de découpage de la surface de dessin représentée par l'objet Graphics actuel sur le résultat de l'opération spécifiée qui combine la région de découpage actuelle et la région spécifiée.
type: docs
weight: 690
url: /fr/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) method

Définit la région de découpage de la surface de dessin représentée par l'objet [Graphics](../) actuel sur le résultat de l'opération spécifiée qui combine la région de découpage actuelle et la région spécifiée.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | Specifies a region to combine |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifies the combining operation |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) method

Définit la région de découpage de la surface de dessin représentée par l'objet [Graphics](../) actuel sur le résultat de l'opération spécifiée qui combine la région de découpage actuelle et la région spécifiée.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Specifies a region to combine |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifies the combining operation |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) method

Définit la région de découpage de la surface de dessin représentée par l'objet [Graphics](../) actuel sur le résultat de l'opération spécifiée qui combine la région de découpage actuelle et la région spécifiée.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Specifies a region to combine |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifies the combining operation |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) method

NON IMPLEMENTÉ.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) method

Définit la région de découpage de la surface de dessin représentée par l'objet [Graphics](../) actuel sur le résultat de l'opération spécifiée qui combine la région de découpage actuelle et la région spécifiée par un chemin graphique.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Specifies a region to combine |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifies the combining operation |

## Voir aussi

* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Region](../../region/)
* Classe [Graphics](../)
* Classe [Rectangle](../../rectangle/)
* Classe [RectangleF](../../rectanglef/)
* Classe [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Espace de noms [System::Drawing](../../)
* Library [Aspose.Slides](../../../)