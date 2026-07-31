---
title: get_Sound()
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili suara yang diputar pada hyperlink. Baca IAudio.
type: docs
weight: 183
url: /id/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() metode


Mewakili suara yang diputar pada hyperlink. Baca [IAudio](../../iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
```

## Catatan


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Dapatkan hyperlink bentuk pertama
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // Ekstrak suara hyperlink ke dalam array byte
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```


## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAudio](../../iaudio/)
* Kelas [IHyperlink](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)