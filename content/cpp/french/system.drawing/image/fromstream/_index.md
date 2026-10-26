---
title: FromStream()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un objet Image à partir du flux spécifié.
type: docs
weight: 339
url: /fr/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) method

Crée un objet [Image](../) à partir du flux spécifié.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Un flux contenant des données d'image |
| use_embedded_color_management | **bool** | IGNORÉ |
| validate_image_data | **bool** | IGNORÉ |

### Valeur de retour

Un pointeur partagé vers l'objet [Image](../) créé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)