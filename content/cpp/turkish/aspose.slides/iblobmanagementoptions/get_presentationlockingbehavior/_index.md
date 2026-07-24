---
title: get_PresentationLockingBehavior()
second_title: Aspose.Slides for C++ API Referansı
description: "Bu özellik, Presentation sınıfının bir örneğinin ömür süresi boyunca kaynağın - dosya ya da akışın - sahibi olup olamayacağını tanımlar. Örnek bir sahip olduğunda kaynak kilitlenir. Bu, BLOB'larla çalışırken bellek tüketimini ve performansı artırmaya yardımcı olur, ancak kaynak (akış veya dosya) Presentation örneğinin ömrü boyunca değiştirilemez. Bu bir örnektir:"
type: docs
weight: 1
url: /tr/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() yöntemi


Bu özellik, [Presentation](../../presentation/) sınıfının bir örneğinin ömür süresi boyunca kaynağın - dosya ya da akışın - sahibi olup olamayacağını tanımlar. Örnek bir sahip olduğunda kaynak kilitlenir. Bu, BLOB'larla çalışırken bellek tüketimini ve performansı artırmaya yardımcı olur, ancak kaynak (akış veya dosya) [Presentation](../../presentation/) örneğinin ömrü boyunca değiştirilemez. Bu bir örnektir:

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
```

## Açıklamalar



```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // IOException, pres.pptx bir Presentation ömrü boyunca kilitli olduğu için fırlatılacaktır
    // File::Delete(u"pres.pptx");
}
// Presentation nesnesi yok edildiğinde dosyanın kilidi kaldırılır ve silinebilir
IO::File::Delete(u"pres.pptx");
```

## Diğer Bağlantılar

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Sınıf [IBlobManagementOptions](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)