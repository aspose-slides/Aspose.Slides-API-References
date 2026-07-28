---
title: FromStream()
second_title: Aspose.Slides C++ API hivatkozás
description: Létrehoz egy Image objektumot a megadott streamből.
type: docs
weight: 339
url: /hu/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) method

Létrehoz egy [Image](../) objektumot a megadott streamen.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Egy adatfolyam, amely képadatokat tartalmaz |
| use_embedded_color_management | **bool** | MELLŐZVE |
| validate_image_data | **bool** | MELLŐZVE |

### Visszatérési érték

Egy megosztott mutató a létrehozott [Image](../) objektumra.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Image](../)
* Osztály [Stream](../../../system.io/stream/)
* Névtér [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)