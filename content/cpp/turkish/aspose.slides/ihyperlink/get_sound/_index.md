---
title: get_Sound()
second_title: Aspose.Slides için C++ API Referansı
description: Hipermetin bağlantısının çalan sesini temsil eder. IAudio'yu okuyun.
type: docs
weight: 183
url: /tr/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() metodu

Hipermetin bağlantısının çalan sesini temsil eder. [IAudio](../../iaudio/) okuyun.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// İlk şekil hipermetin bağlantısını al
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Hipermetin bağlantısının sesini bayt dizisine çıkar
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```




## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudio](../../iaudio/)
* Class [IHyperlink](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)