---
title: set_Sound()
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili suara pemutaran hyperlink. Tulis IAudio.
type: docs
weight: 300
url: /id/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) metode

Mewakili suara pemutaran hyperlink. Tulis [IAudio](../../iaudio/).

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
```

## Catatan



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Dapatkan hyperlink bentuk pertama
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Ekstrak suara hyperlink dalam array byte
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAudio](../../iaudio/)
* Kelas [Hyperlink](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)