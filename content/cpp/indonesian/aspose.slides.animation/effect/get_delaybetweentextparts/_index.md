---
title: get_DelayBetweenTextParts()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan penundaan antara bagian teks beranimasi (kata atau huruf). Nilai positif menentukan persentase durasi efek. Nilai negatif menentukan penundaan dalam detik. Baca float.
type: docs
weight: 300
url: /id/aspose.slides.animation/effect/get_delaybetweentextparts/
---
## Effect::get_DelayBetweenTextParts() metode


Mendefinisikan penundaan antara bagian teks beranimasi (kata atau huruf). Nilai positif menentukan persentase durasi efek. Nilai negatif menentukan penundaan dalam detik. Baca **float**.

```cpp
float Aspose::Slides::Animation::Effect::get_DelayBetweenTextParts() override
```

## Catatan



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## Lihat Juga

* Kelas [Effect](../)
* Ruang Nama [Aspose::Slides::Animation](../../)
* Pustaka [Aspose.Slides](../../../)