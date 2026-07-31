---
title: get_AfterAnimationType()
second_title: Referensi API Aspose.Slides untuk C++
description: Menetapkan jenis animasi setelah untuk efek. Baca AfterAnimationType.
type: docs
weight: 222
url: /id/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() metode


Menetapkan jenis animasi setelah untuk efek. Baca [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## Catatan



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Dapatkan efek pertama dari slide pertama.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Ubah efek After animation menjadi "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Lihat Juga

* Enum [AfterAnimationType](../../afteranimationtype/)
* Kelas [IEffect](../)
* Ruang Nama [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)