---
title: GetThumbnail
second_title: Référence de l'API Aspose.Slides pour .NET
description: Renvoie la miniature de la forme. ShapeThumbnailBounds.Le type de limite de la miniature de la forme est utilisé par défaut.
type: docs
weight: 330
url: /fr/net/aspose.slides/shape/getthumbnail/
---
## GetThumbnail() {#getthumbnail}

Renvoie la miniature de la forme. ShapeThumbnailBounds.Le type de limite de la miniature de la forme est utilisé par défaut.

```csharp
public Bitmap GetThumbnail()
```

### Return_Value

Vignette de la forme.

### Voir également

* class [Shape](../../shape)
* espace de noms [Aspose.Slides](../../shape)
* Assemblée [Aspose.Slides](../../../)

---

## GetThumbnail(ShapeThumbnailBounds, float, float) {#getthumbnail_1}

Renvoie la vignette de la forme.

```csharp
public Bitmap GetThumbnail(ShapeThumbnailBounds bounds, float scaleX, float scaleY)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| bounds | ShapeThumbnailBounds | Type de limite de vignette de forme. |
| scaleX | Single | Échelle X |
| scaleY | Single | Échelle Y |

### Return_Value

Vignette de forme ou null dans le cas où ShapeThumbnailBounds.Appearance est utilisé et qu'une forme n'a pas d'éléments visibles.

### Voir également

* enum [ShapeThumbnailBounds](../../shapethumbnailbounds)
* class [Shape](../../shape)
* espace de noms [Aspose.Slides](../../shape)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->