---
title: SaveAdd()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt einen Frame zur Datei oder zum Stream hinzu, die in einem vorherigen Aufruf der Save()-Methode angegeben wurde.
type: docs
weight: 14
url: /de/system.drawing/image/saveadd/
---
## Image::SaveAdd(const Imaging::EncoderParametersPtr\&) Methode

Fügt einen Frame zur Datei oder zum Stream hinzu, die in einem vorherigen Aufruf der [Save()](../save/) Methode angegeben wurden.

```cpp
void System::Drawing::Image::SaveAdd(const Imaging::EncoderParametersPtr &encoder_params)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Die Parameter des zu verwendenden Encoders |

## Image::SaveAdd(const SharedPtr\<Image\>\&, const Imaging::EncoderParametersPtr\&) Methode

Fügt einen Frame zur Datei oder zum Stream hinzu, die in einem vorherigen Aufruf der [Save()](../save/) Methode angegeben wurden.

```cpp
void System::Drawing::Image::SaveAdd(const SharedPtr<Image> &image, const Imaging::EncoderParametersPtr &encoder_params)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../)\>\& | Ein [Image](../) Objekt, das den hinzuzufügenden Frame enthält |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Die Parameter des zu verwendenden Encoders |

## Siehe auch

* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Image](../)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)