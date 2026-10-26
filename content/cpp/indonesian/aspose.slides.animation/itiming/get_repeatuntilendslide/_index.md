---
title: get_RepeatUntilEndSlide()
second_title: Referensi API Aspose.Slides untuk C++
description: Atribut ini menentukan apakah efek akan diulang hingga akhir slide. Baca bool.
type: docs
weight: 131
url: /id/aspose.slides.animation/itiming/get_repeatuntilendslide/
---
## ITiming::get_RepeatUntilEndSlide() metode

Atribut ini menentukan apakah efek akan diulang hingga akhir slide. Baca **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilEndSlide()=0
```

## Catatan

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Mendapatkan urutan efek untuk slide pertama
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Mendapatkan efek pertama dari urutan utama.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Mengubah Timing/Ulangi efek menjadi "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Lihat Juga

* Kelas [ITiming](../)
* Ruang Nama [Aspose::Slides::Animation](../../)
* Pustaka [Aspose.Slides](../../../)