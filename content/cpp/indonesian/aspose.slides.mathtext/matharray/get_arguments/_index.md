---
title: get_Arguments()
second_title: Referensi API Aspose.Slides untuk C++
description: Kumpulan item dalam array
type: docs
weight: 1
url: /id/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() metode

Kumpulan item dalam array

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
```

## Catatan

Contoh: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElementCollection](../../imathelementcollection/)
* Kelas [MathArray](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)