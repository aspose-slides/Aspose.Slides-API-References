---
title: get_Rewind()
second_title: Aspose.Slides untuk Referensi API C++
description: Atribut ini menentukan apakah efek akan diputar mundur setelah selesai diputar. Baca bool.
type: docs
weight: 313
url: /id/aspose.slides.animation/itiming/get_rewind/
---
## ITiming::get_Rewind() metode


Atribut ini menentukan apakah efek akan diputar mundur setelah selesai diputar. Baca **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_Rewind()=0
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

* Kelas [ITiming](../)
* Ruang Nama [Aspose::Slides::Animation](../../)
* Perpustakaan [Aspose.Slides](../../../)