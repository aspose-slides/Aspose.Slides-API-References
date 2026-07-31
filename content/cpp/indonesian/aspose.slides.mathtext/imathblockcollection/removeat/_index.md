---
title: RemoveAt()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghapus item pada indeks yang ditentukan dalam koleksi.
type: docs
weight: 53
url: /id/aspose.slides.mathtext/imathblockcollection/removeat/
---
## IMathBlockCollection::RemoveAt(int32_t) metode

Menghapus sebuah item pada indeks yang ditentukan dalam koleksi.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::RemoveAt(int32_t index)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol dari item yang akan dihapus. |
## Catatan



Contoh: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->RemoveAt(0);
```

## Lihat Juga

* Kelas [IMathBlockCollection](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)