---
title: set_Rewind()
second_title: Aspose.Slides untuk Referensi API C++
description: Atribut ini menentukan apakah efek akan diputar mundur setelah selesai diputar. Tulis bool.
type: docs
weight: 326
url: /id/aspose.slides.animation/itiming/set_rewind/
---
## ITiming::set_Rewind(bool) metode


Atribut ini menentukan apakah efek akan diputar mundur setelah selesai diputar. Tulis **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_Rewind(bool value)=0
```

## Catatan



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Dapatkan urutan efek untuk slide pertama
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Dapatkan efek pertama dari urutan utama.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Aktifkan Timing/Rewind efek.
effect->get_Timing()->set_Rewind(true);
```

## Lihat Juga

* Kelas [ITiming](../)
* Ruang Nama [Aspose::Slides::Animation](../../)
* Perpustakaan [Aspose.Slides](../../../)