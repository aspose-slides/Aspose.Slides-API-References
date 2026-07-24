---
title: FromStream()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen akıştan bir Image nesnesi oluşturur.
type: docs
weight: 339
url: /tr/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) yöntemi

Belirtilen akıştan bir [Image](../) nesnesi oluşturur.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Görüntü verilerini içeren bir akış |
| use_embedded_color_management | **bool** | YOK SAYILDI |
| validate_image_data | **bool** | YOK SAYILDI |

### Dönüş Değeri

Oluşturulan [Image](../) nesnesine bir paylaşılan işaretçi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)