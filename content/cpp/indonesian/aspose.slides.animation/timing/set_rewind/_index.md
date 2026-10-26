---
title: set_Rewind()
second_title: Referensi API Aspose.Slides untuk C++
description: Atribut ini menentukan apakah efek akan diputar mundur setelah selesai diputar. Tulis bool.
type: docs
weight: 248
url: /id/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) metode


Atribut ini menentukan apakah efek akan diputar mundur setelah selesai diputar. Tulis **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
```

## Catatan



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## Lihat Juga

* Kelas [Timing](../)
* Ruang Nama [Aspose::Slides::Animation](../../)
* Pustaka [Aspose.Slides](../../../)