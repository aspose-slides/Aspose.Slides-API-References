---
title: FromStream()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein Image-Objekt aus dem angegebenen Stream.
type: docs
weight: 339
url: /de/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) Methode

Erstellt ein [Image](../)-Objekt aus dem angegebenen Stream.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Ein Stream, der Bilddaten enthält |
| use_embedded_color_management | **bool** | IGNORED |
| validate_image_data | **bool** | IGNORED |

### Rückgabewert

Ein Shared-Pointer auf das erstellte [Image](../)-Objekt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Image](../)
* Klasse [Stream](../../../system.io/stream/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)