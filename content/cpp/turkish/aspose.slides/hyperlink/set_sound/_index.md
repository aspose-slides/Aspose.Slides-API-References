---
title: set_Sound()
second_title: Aspose.Slides için C++ API Referansı
description: Hiperlinkin çalan sesini temsil eder. IAudio yazın.
type: docs
weight: 300
url: /tr/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) metot

Hyperlink'in çalan sesini temsil eder. [IAudio](../../iaudio/) yazın.

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
```

## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// İlk şekil hiperlinkini al
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Hiperlink sesini bayt dizisi olarak ayıkla
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudio](../../iaudio/)
* Class [Hyperlink](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)