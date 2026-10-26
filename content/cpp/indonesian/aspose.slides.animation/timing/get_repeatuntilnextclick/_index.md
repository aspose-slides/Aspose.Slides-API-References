---
title: get_RepeatUntilNextClick()
second_title: Referensi API Aspose.Slides untuk C++
description: Atribut ini menentukan apakah efek akan diulang hingga klik berikutnya. Baca bool.
type: docs
weight: 157
url: /id/aspose.slides.animation/timing/get_repeatuntilnextclick/
---
## Timing::get_RepeatUntilNextClick() metode


Atribut ini menentukan apakah efek akan diulang hingga klik berikutnya. Baca **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilNextClick() override
```

## Catatan



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Mendapatkan urutan efek untuk slide pertama
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Mendapatkan efek pertama dari urutan utama.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Mengubah efek Timing/Repeat menjadi "Sampai Akhir Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Lihat Juga

* Kelas [Timing](../)
* Ruang Nama [Aspose::Slides::Animation](../../)
* Pustaka [Aspose.Slides](../../../)