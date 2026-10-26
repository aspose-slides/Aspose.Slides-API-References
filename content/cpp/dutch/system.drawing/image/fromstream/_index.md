---
title: FromStream()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een Image-object van de opgegeven stream.
type: docs
weight: 339
url: /nl/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) methode

Creëert een [Image](../) object van de opgegeven stream.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Een stream die beeldgegevens bevat |
| use_embedded_color_management | **bool** | IGNORED |
| validate_image_data | **bool** | IGNORED |

### Retourwaarde

Een gedeelde pointer naar het gemaakte [Image](../) object.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Image](../)
* Klasse [Stream](../../../system.io/stream/)
* Naamruimte [System::Drawing](../../)
* Bibliotheek [Aspose.Slides](../../../)