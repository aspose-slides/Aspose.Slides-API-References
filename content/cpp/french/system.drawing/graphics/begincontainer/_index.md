---
title: BeginContainer()
second_title: Référence API Aspose.Slides pour C++
description: Enregistre un conteneur avec l'état actuel de cet objet, ouvre et utilise un nouveau conteneur, puis renvoie le conteneur enregistré.
type: docs
weight: 976
url: /fr/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() méthode

Enregistre un conteneur avec l'état actuel de cet objet, ouvre et utilise un nouveau conteneur et renvoie le conteneur enregistré.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) méthode

Enregistre un conteneur avec l'état actuel de cet objet, ouvre et utilise un nouveau conteneur et renvoie le conteneur enregistré.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | The rectangle that specifies a scale transformation of the new container. Used together with **srcrect** |
| srcrect | [Rectangle](../../rectangle/) | The rectangle that specifies a scale transformation of the new container. Used together with **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | The value that specifies the unit of measure of the new container |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) méthode

Enregistre un conteneur avec l'état actuel de cet objet, ouvre et utilise un nouveau conteneur et renvoie le conteneur enregistré.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | The rectangle that specifies a scale transformation of the new container. Used together with **srcrect** |
| srcrect | [RectangleF](../../rectanglef/) | The rectangle that specifies a scale transformation of the new container. Used together with **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | The value that specifies the unit of measure of the new container |

## Voir aussi

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Classe [Graphics](../)
* Classe [Rectangle](../../rectangle/)
* Classe [RectangleF](../../rectanglef/)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)