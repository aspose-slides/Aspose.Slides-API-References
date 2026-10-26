---
title: get_AfterAnimationType()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan jenis animasi setelah untuk efek. Baca AfterAnimationType.
type: docs
weight: 222
url: /id/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() metode


Mendefinisikan jenis animasi setelah untuk efek. Baca [AfterAnimationType](../../afteranimationtype/).

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
```

## Catatan



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Dapatkan efek pertama dari slide pertama.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Ubah After animation menjadi "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Lihat Juga

* Enum [AfterAnimationType](../../afteranimationtype/)
* Class [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)