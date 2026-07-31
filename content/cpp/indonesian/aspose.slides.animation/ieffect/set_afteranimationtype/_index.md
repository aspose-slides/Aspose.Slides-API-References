---
title: set_AfterAnimationType()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan tipe animasi setelah untuk efek. Tulis AfterAnimationType.
type: docs
weight: 235
url: /id/aspose.slides.animation/ieffect/set_afteranimationtype/
---
## IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) metode


Mendefinisikan tipe animasi setelah untuk efek. Tulis [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value)=0
```

## Catatan



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation to "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Lihat Juga

* Enum [AfterAnimationType](../../afteranimationtype/)
* Kelas [IEffect](../)
* Ruang Nama [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)