---
title: set_RepeatUntilNextClick()
second_title: Referensi API Aspose.Slides untuk C++
description: Atribut ini menentukan apakah efek akan diulang hingga klik berikutnya. Tulis bool.
type: docs
weight: 170
url: /id/aspose.slides.animation/itiming/set_repeatuntilnextclick/
---
## ITiming::set_RepeatUntilNextClick(bool) metode

Atribut ini menentukan apakah efek akan diulang hingga klik berikutnya. Tulis **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilNextClick(bool value)=0
```

## Catatan

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Mendapatkan urutan efek untuk slide pertama
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Mendapatkan efek pertama dari urutan utama.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Mengubah Timing/Repeat efek menjadi "Sampai Akhir Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Lihat Juga

* Kelas [ITiming](../)
* Ruang Nama [Aspose::Slides::Animation](../../)
* Perpustakaan [Aspose.Slides](../../../)