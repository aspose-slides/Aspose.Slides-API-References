---
title: FromStream()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett Image-objekt från den angivna strömmen.
type: docs
weight: 339
url: /sv/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) metod


Skapar ett [Image](../)-objekt från den angivna strömmen.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | En ström som innehåller bilddata |
| use_embedded_color_management | **bool** | IGNORED |
| validate_image_data | **bool** | IGNORED |

### Returvärde

En delad pekare till det skapade [Image](../)-objektet.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Image](../)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)