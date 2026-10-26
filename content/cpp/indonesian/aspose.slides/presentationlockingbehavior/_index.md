---
title: PresentationLockingBehavior
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili perilaku dalam memperlakukan sumber IPresentation (file atau System::IO::Stream) saat memuat dan bekerja dengan sebuah instance IPresentation."
type: docs
weight: 6748
url: /id/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enum

Mewakili perilaku dalam memperlakukan sumber [IPresentation](../ipresentation/) (file atau [System::IO::Stream](../../system.io/stream/)) saat memuat dan bekerja dengan sebuah instance [IPresentation](../ipresentation/).

```cpp
enum class PresentationLockingBehavior
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| LoadAndRelease | 0 | Sumber akan dikunci hanya selama eksekusi konstruktor [IPresentation](../ipresentation/). |
| KeepLocked | 1 | Sumber akan dikunci selama seluruh masa hidup instance [IPresentation](../ipresentation/), sampai dibuang. |

## Catatan

Sumber adalah parameter yang diberikan ke konstruktor [IPresentation](../ipresentation/). Pada contoh di bawah, sumber adalah file "pres.pptx": 

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```

Untuk contoh ini, sumber ("pres.pptx" file) akan dikunci selama masa hidup instance [IPresentation](../ipresentation/), yaitu tidak dapat diubah atau dihapus oleh proses lain. 

## Lihat Juga

* Ruang nama [Aspose::Slides](../)
* Perpustakaan [Aspose.Slides](../../)