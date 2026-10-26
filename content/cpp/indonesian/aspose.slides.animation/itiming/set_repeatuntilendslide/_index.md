---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides untuk Referensi API C++
description: Atribut ini menentukan apakah efek akan diulang sampai akhir slide. Tulis bool.
type: docs
weight: 144
url: /id/aspose.slides.animation/itiming/set_repeatuntilendslide/
---
## ITiming::set_RepeatUntilEndSlide(bool) metode

Atribut ini menentukan apakah efek akan diulang sampai akhir slide. Tulis **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilEndSlide(bool value)=0
```

## Keterangan



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Lihat Juga

* Kelas [ITiming](../)
* Ruang Nama [Aspose::Slides::Animation](../../)
* Perpustakaan [Aspose.Slides](../../../)