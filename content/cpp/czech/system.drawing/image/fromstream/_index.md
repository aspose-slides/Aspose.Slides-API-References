---
title: FromStream()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří objekt Image ze zadaného proudu.
type: docs
weight: 339
url: /cs/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) metoda

Vytvoří objekt [Image](../) ze zadaného proudu.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Proud, který obsahuje data obrázku |
| use_embedded_color_management | **bool** | IGNORED |
| validate_image_data | **bool** | IGNORED |

### Return Value

Sdílený ukazatel na vytvořený objekt [Image](../).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Image](../)
* Třída [Stream](../../../system.io/stream/)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)