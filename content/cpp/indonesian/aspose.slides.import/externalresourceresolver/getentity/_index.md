---
title: GetEntity()
second_title: Referensi API Aspose.Slides untuk C++
description: Memetakan URI ke objek yang berisi sumber daya sebenarnya.
type: docs
weight: 14
url: /id/aspose.slides.import/externalresourceresolver/getentity/
---
## ExternalResourceResolver::GetEntity(System::String) metode


Memetakan URI ke objek yang berisi sumber daya sebenarnya.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::ExternalResourceResolver::GetEntity(System::String absoluteUri) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | URI absolut ke objek. |

### Nilai Kembalian

Objek [System::IO::Stream](../../../system.io/stream/) atau null jika sumber daya tidak dapat diputar alir.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ExternalResourceResolver](../)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)