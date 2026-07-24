---
title: RemoveWriteProtection()
second_title: C++ için Aspose.Slides API Referansı
description: Bu sunum için yazma korumasını kaldırır.
type: docs
weight: 144
url: /tr/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() yöntemi

Bu sunum için yazma korumasını kaldırır.

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## Açıklamalar

Bu örnek kod, bir PowerPoint [Presentation](../../presentation/) üzerindeki yazma korumasını nasıl kaldıracağınızı gösterir.
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Sınıf [ProtectionManager](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)