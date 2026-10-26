---
title: get_Sound()
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili suara yang diputar pada hyperlink. Baca IAudio.
type: docs
weight: 287
url: /id/aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() metode

Mewakili suara yang diputar pada hyperlink. Baca [IAudio](../../iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
```

## Catatan



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Dapatkan hyperlink shape pertama
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