---
title: set_PresentationLockingBehavior()
second_title: Referensi API Aspose.Slides untuk C++
description: "Properti ini menentukan apakah sebuah instance dari kelas Presentation dapat menjadi pemilik sumber - file atau stream selama masa hidup instance. Jika instance menjadi pemilik, ia mengunci sumber. Hal ini membantu meningkatkan konsumsi memori dan kinerja saat bekerja dengan BLOB, tetapi sumber (stream atau file) tidak dapat diubah selama masa hidup instance Presentation. Berikut ini contohnya:"
type: docs
weight: 14
url: /id/aspose.slides/iblobmanagementoptions/set_presentationlockingbehavior/
---
## IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior) metode

Properti ini menentukan apakah sebuah instance dari kelas [Presentation](../../presentation/) dapat menjadi pemilik sumber - file atau stream selama masa hidup instance. Jika instance menjadi pemilik, ia mengunci sumber. Hal ini membantu meningkatkan konsumsi memori dan kinerja saat bekerja dengan BLOB, tetapi sumber (stream atau file) tidak dapat diubah selama masa hidup instance [Presentation](../../presentation/)'s. Berikut adalah contoh:

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior value)=0
```

## Catatan

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // IOException akan dilempar karena pres.pptx terkunci selama masa hidup Presentation
    // File::Delete(u"pres.pptx");
}
// setelah objek Presentation dihancurkan, file tidak terkunci lagi dan dapat dihapus
IO::File::Delete(u"pres.pptx");
```

## Lihat Juga

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Kelas [IBlobManagementOptions](../)
* Ruang nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)