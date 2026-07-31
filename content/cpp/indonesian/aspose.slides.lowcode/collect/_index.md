---
title: Collect
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili sekelompok metode yang dimaksudkan untuk mengumpulkan objek model dari berbagai tipe dari Presentation.
type: docs
weight: 1
url: /id/aspose.slides.lowcode/collect/
---
## Collect kelas


Mewakili sekelompok metode yang dimaksudkan untuk mengumpulkan objek model dari berbagai tipe dari [Presentation](../../aspose.slides/presentation/).

```cpp
class Collect
```

## Metode

| Metode | Deskripsi |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Mengumpulkan semua instance dari [Shape](../../aspose.slides/shape/) di [Presentation](../../aspose.slides/presentation/). |
## Catatan



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... ubah format shape atau properti lain
}
```

## Lihat Juga

* Namespace [Aspose::Slides::LowCode](../)
* Perpustakaan [Aspose.Slides](../../)