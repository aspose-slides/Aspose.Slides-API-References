---
title: Remove()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghapus kemunculan pertama objek tertentu dari koleksi/>
type: docs
weight: 40
url: /id/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove(System::SharedPtr\<IMathBlock\>) metode

Menghapus kemunculan pertama objek tertentu dari koleksi/>.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Objek yang akan dihapus dari koleksi. |

### Nilai Kembalian

true jika *item* berhasil dihapus dari koleksi; jika tidak, false. Metode ini juga mengembalikan false jika *item* tidak ditemukan dalam koleksi asli/>.

## Catatan



Contoh: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathBlock](../../imathblock/)
* Kelas [IMathBlockCollection](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)