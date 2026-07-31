---
title: MathBox()
second_title: Referensi API Aspose.Slides untuk C++
description: Menginisialisasi MathBox dengan elemen yang ditentukan sebagai argumen
type: docs
weight: 144
url: /id/aspose.slides.mathtext/mathbox/mathbox/
---
## MathBox::MathBox(System::SharedPtr\<IMathElement\>) konstruktor


Menginisialisasi [MathBox](../) dengan elemen yang ditentukan sebagai argumen

```cpp
Aspose::Slides::MathText::MathBox::MathBox(System::SharedPtr<IMathElement> element)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemen dasar yang diterapkan pada kotak. Bisa null. |
## Catatan



Contoh: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)