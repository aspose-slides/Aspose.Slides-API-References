---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan IMathBlock ke akhir koleksi.
type: docs
weight: 14
url: /id/aspose.slides.mathtext/imathblockcollection/add/
---
## IMathBlockCollection::Add(System::SharedPtr\<IMathBlock\>) metode

Menambahkan [IMathBlock](../../imathblock/) ke akhir koleksi.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Add(System::SharedPtr<IMathBlock> item)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Sebuah blok matematika yang akan ditambahkan ke akhir koleksi |

## Keterangan

Contoh:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathBlock](../../imathblock/)
* Kelas [IMathBlockCollection](../)
* Ruang nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)