---
title: get_PresentationLockingBehavior()
second_title: Referensi API Aspose.Slides untuk C++
description: "Properti ini menentukan apakah sebuah instance dari kelas Presentation dapat menjadi pemilik sumber - file atau stream selama masa hidup instance. Jika instance tersebut adalah pemilik, ia mengunci sumber. Hal ini membantu meningkatkan konsumsi memori dan kinerja saat bekerja dengan BLOB, namun sumber (stream atau file) tidak dapat diubah selama masa hidup instance Presentation. Berikut contoh:"
type: docs
weight: 1
url: /id/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() metode

Properti ini menentukan apakah sebuah instance dari kelas [Presentation](../../presentation/) dapat menjadi pemilik sumber - file atau stream selama masa hidup instance. Jika instance tersebut adalah pemilik, ia mengunci sumber. Hal ini membantu meningkatkan konsumsi memori dan kinerja saat bekerja dengan BLOB, namun sumber (stream atau file) tidak dapat diubah selama masa hidup instance [Presentation](../../presentation/). Berikut contoh:

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
```

## Catatan

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // IOException akan dilempar karena pres.pptx dikunci selama masa hidup Presentation
    // File::Delete(u"pres.pptx");
}
// setelah objek Presentation dihancurkan, file tidak terkunci lagi dan dapat dihapus
IO::File::Delete(u"pres.pptx");
```

## Lihat Juga

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Class [IBlobManagementOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)