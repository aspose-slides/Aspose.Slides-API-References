---
title: get_Sound()
second_title: Aspose.Slides for C++ API Referansı
description: Hipermetin bağlantısının çalan sesini temsil eder. IAudio'yu okuyun.
type: docs
weight: 287
url: /tr/aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() metod


Hipermetin bağlantısının çalan sesini temsil eder. [IAudio](../../iaudio/)'yi okuyun.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// İlk şekil hiperlinkini al
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Hipermetin bağlantısı sesini bayt dizisi olarak çıkar
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## Ayrıca

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAudio](../../iaudio/)
* Sınıf [Hyperlink](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)