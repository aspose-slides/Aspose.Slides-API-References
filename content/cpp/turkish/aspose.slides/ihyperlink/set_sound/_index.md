---
title: set_Sound()
second_title: C++ için Aspose.Slides API Referansı
description: Köprünün oynatılan sesini temsil eder. IAudio yazın.
type: docs
weight: 196
url: /tr/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) yöntem


Köprünün oynatılan sesini temsil eder. Yaz [IAudio](../../iaudio/).

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// İlk şeklin hiperlinkini al
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Hiperlink sesini bayt dizisine çıkar
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```




## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAudio](../../iaudio/)
* Sınıf [IHyperlink](../)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)