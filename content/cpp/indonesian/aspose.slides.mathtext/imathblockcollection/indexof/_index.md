---
title: IndexOf()
second_title: Aspose.Slides untuk C++ Referensi API
description: Menentukan indeks dari IMathBlock tertentu dalam koleksi.
type: docs
weight: 79
url: /id/aspose.slides.mathtext/imathblockcollection/indexof/
---
## IMathBlockCollection::IndexOf(System::SharedPtr\<IMathBlock\>) metode

Menentukan indeks dari [IMathBlock](../../imathblock/) tertentu dalam koleksi.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::IndexOf(System::SharedPtr<IMathBlock> item)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Item yang akan dicari dalam koleksi. |

### Nilai Kembali

Indeks dari *item* jika ditemukan dalam koleksi; jika tidak, -1.

## Keterangan

Contoh:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
int32_t index = blockCollection->IndexOf(block);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathBlock](../../imathblock/)
* Kelas [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)