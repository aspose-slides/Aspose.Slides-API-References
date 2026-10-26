---
title: get_Count()
second_title: Aspose.Slides untuk Referensi API C++
description: Mendapatkan jumlah elemen yang sebenarnya terdapat dalam koleksi. Hanya-baca int32_t.
type: docs
weight: 1
url: /id/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() metode


Mendapatkan jumlah elemen yang sebenarnya terdapat dalam koleksi. Hanya-baca **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## Keterangan


Contoh: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## Lihat Juga

* Kelas [IMathBlockCollection](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)