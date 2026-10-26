---
title: get_Arguments()
second_title: Referensi API Aspose.Slides untuk C++
description: Kumpulan item dalam array
type: docs
weight: 1
url: /id/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() metode


Kumpulan item dalam array

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
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
* Kelas [IMathArray](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)