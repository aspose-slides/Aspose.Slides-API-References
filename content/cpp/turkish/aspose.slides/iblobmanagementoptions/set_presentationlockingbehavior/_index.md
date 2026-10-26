---
title: set_PresentationLockingBehavior()
second_title: Aspose.Slides için C++ API Referansı
description: "Bu özellik, Presentation sınıfının bir örneğinin örnek ömrü boyunca kaynağın - dosya veya akış sahibi olup olamayacağını tanımlar. Örnek sahibi ise kaynağı kilitler. Bu, BLOB'larla çalışırken bellek tüketimini ve performansı artırmaya yardımcı olur, ancak kaynak (akış veya dosya) Presentation'ın örnek ömrü boyunca değiştirilemez. Bu bir örnek:"
type: docs
weight: 14
url: /tr/aspose.slides/iblobmanagementoptions/set_presentationlockingbehavior/
---
## IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior) metot

Bu özellik, [Presentation](../../presentation/) sınıfının bir örneğinin örnek ömrü boyunca kaynağın - dosya veya akış sahibi olup olamayacağını tanımlar. Örnek sahibi ise kaynağı kilitler. Bu, BLOB'larla çalışırken bellek tüketimini ve performansı artırmaya yardımcı olur, ancak kaynak (akış veya dosya) [Presentation](../../presentation/)'ın örnek ömrü boyunca değiştirilemez. Bu bir örnek:

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior value)=0
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
// Presentation nesnesi yok edildikten sonra dosya kilidi açılır ve silinebilir
IO::File::Delete(u"pres.pptx");
```

## Bakınız

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Sınıf [IBlobManagementOptions](../)
* İsim uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)