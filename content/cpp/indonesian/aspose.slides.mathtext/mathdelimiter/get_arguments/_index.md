---
title: get_Arguments()
second_title: Referensi API Aspose.Slides untuk C++
description: Satu atau beberapa elemen matematika yang dipisahkan oleh karakter pembatas
type: docs
weight: 1
url: /id/aspose.slides.mathtext/mathdelimiter/get_arguments/
---
## MathDelimiter::get_Arguments() metode


Satu atau beberapa elemen matematika yang dipisahkan oleh karakter pembatas

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathDelimiter::get_Arguments() override
```

## Catatan


Contoh: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElementCollection](../../imathelementcollection/)
* Kelas [MathDelimiter](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)