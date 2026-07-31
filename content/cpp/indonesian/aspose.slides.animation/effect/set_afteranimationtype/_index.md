---
title: set_AfterAnimationType()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan tipe animasi setelah untuk efek. Tulis AfterAnimationType.
type: docs
weight: 235
url: /id/aspose.slides.animation/effect/set_afteranimationtype/
---
## Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) metode

Mendefinisikan tipe animasi setelah untuk efek. Tulis [AfterAnimationType](../../afteranimationtype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value) override
```

## Catatan



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Dapatkan efek pertama pada slide pertama.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Ubah After animation pada efek menjadi "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Lihat Juga

* Enum [AfterAnimationType](../../afteranimationtype/)
* Kelas [Effect](../)
* Ruang Nama [Aspose::Slides::Animation](../../)
* Perpustakaan [Aspose.Slides](../../../)