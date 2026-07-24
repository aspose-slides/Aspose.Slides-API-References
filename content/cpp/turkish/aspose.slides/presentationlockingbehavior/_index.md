---
title: PresentationLockingBehavior
second_title: Aspose.Slides for C++ API Referansı
description: "IPresentation kaynağını (dosya veya System::IO::Stream) yüklerken ve bir IPresentation örneğiyle çalışırken ele almayı ilgili davranışı temsil eder."
type: docs
weight: 6748
url: /tr/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enum

Yükleme ve [IPresentation](../ipresentation/) örneği ile çalışırken [IPresentation](../ipresentation/) kaynağını (dosya veya [System::IO::Stream](../../system.io/stream/)) ele almayı ilgili davranışı temsil eder.

```cpp
enum class PresentationLockingBehavior
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| LoadAndRelease | 0 | Kaynak, yalnızca [IPresentation](../ipresentation/) yapıcı yürütmesi süresince kilitlenecek. |
| KeepLocked | 1 | Kaynak, [IPresentation](../ipresentation/) örneğinin tüm ömrü boyunca, yok edilene kadar kilitlenecek. |

## Açıklamalar

Kaynak, [IPresentation](../ipresentation/) yapıcısına geçirilen parametredir. Aşağıdaki örnekte, kaynak "pres.pptx" dosyasıdır:

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```

Bu örnek için, kaynak ("pres.pptx" dosyası) bir [IPresentation](../ipresentation/) örneği ömrü boyunca kilitlenecek, yani diğer işlem tarafından değiştirilemez veya silinemez. 

## İlgili

* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)