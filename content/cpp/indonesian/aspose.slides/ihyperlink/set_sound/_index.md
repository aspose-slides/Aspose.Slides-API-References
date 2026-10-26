---
title: set_Sound()
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili suara yang diputar pada hyperlink. Tulis IAudio.
type: docs
weight: 196
url: /id/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) metode


Mewakili suara yang diputar pada hyperlink. Tulis [IAudio](../../iaudio/).

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
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
* Kelas [IHyperlink](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)