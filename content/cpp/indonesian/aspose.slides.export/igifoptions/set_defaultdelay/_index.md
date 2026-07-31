---
title: set_DefaultDelay()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengatur waktu tunda default [ms]. Nilai ini akan digunakan bila metode ISlideShowTransition::set_AdvanceAfterTime() tidak dipanggil. Nilai defaultnya adalah 1000."
type: docs
weight: 92
url: /id/aspose.slides.export/igifoptions/set_defaultdelay/
---
## IGifOptions::set_DefaultDelay(int32_t) metode


Mengatur waktu tunda default [ms]. Nilai ini akan digunakan bila metode [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) tidak dipanggil. Nilai defaultnya adalah 1000.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_DefaultDelay(int32_t value)=0
```

## Catatan



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Lihat Juga

* Kelas [IGifOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)