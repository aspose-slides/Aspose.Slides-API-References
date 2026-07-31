---
title: Clear()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghapus semua elemen dari koleksi.
type: docs
weight: 118
url: /id/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() metode


Menghapus semua elemen dari koleksi.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## Keterangan


Contoh:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## Lihat Juga

* Kelas [IMathBlockCollection](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)