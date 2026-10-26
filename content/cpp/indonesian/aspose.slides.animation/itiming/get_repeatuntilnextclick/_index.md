---
title: get_RepeatUntilNextClick()
second_title: Referensi API Aspose.Slides untuk C++
description: Atribut ini menentukan apakah efek akan diulang sampai klik berikutnya. Baca bool.
type: docs
weight: 157
url: /id/aspose.slides.animation/itiming/get_repeatuntilnextclick/
---
## ITiming::get_RepeatUntilNextClick() metode

Atribut ini menentukan apakah efek akan diulang sampai klik berikutnya. Baca **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilNextClick()=0
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

* Kelas [ITiming](../)
* Ruang Nama [Aspose::Slides::Animation](../../)
* Perpustakaan [Aspose.Slides](../../../)