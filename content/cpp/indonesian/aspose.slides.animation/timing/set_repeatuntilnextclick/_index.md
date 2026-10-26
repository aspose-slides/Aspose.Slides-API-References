---
title: set_RepeatUntilNextClick()
second_title: Referensi API Aspose.Slides untuk C++
description: Atribut ini menentukan apakah efek akan diulang hingga klik berikutnya. Tulis bool.
type: docs
weight: 170
url: /id/aspose.slides.animation/timing/set_repeatuntilnextclick/
---
## Timing::set_RepeatUntilNextClick(bool) metode

Atribut ini menentukan apakah efek akan diulang hingga klik berikutnya. Tulis **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilNextClick(bool value) override
```

## Catatan

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Lihat Juga

* Kelas [Timing](../)
* Namespace [Aspose::Slides::Animation](../../)
* Perpustakaan [Aspose.Slides](../../../)