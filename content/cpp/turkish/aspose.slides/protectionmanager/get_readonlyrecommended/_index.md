---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides için C++ API Referansı
description: Salt okunur öneriyi alır. Okunur bool.
type: docs
weight: 79
url: /tr/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() metodu


Salt okunur öneriyi alır. Okunur **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
```

## Açıklamalar


Aşağıdaki örnek kod, [Presentation](../../presentation/) PowerPoint sunumunu C# içinde [Aspose.Slides](../../) kullanarak Salt Okunur olarak ayarlamanın nasıl yapılacağını gösterir.
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Diğer Bağlantılar

* Sınıf [ProtectionManager](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)