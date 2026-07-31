---
title: Remove()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghapus kemunculan pertama dari objek tertentu dalam koleksi.
type: docs
weight: 92
url: /id/aspose.slides.mathtext/imathelementcollection/remove/
---
## IMathElementCollection::Remove(System::SharedPtr\<IMathElement\>) metode


Menghapus kemunculan pertama dari objek tertentu dalam koleksi.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Remove(System::SharedPtr<IMathElement> item)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Objek yang akan dihapus dari koleksi. |

### Nilai Kembalian

true jika *item* berhasil dihapus dari koleksi; jika tidak, false. Metode ini juga mengembalikan false jika *item* tidak ditemukan dalam koleksi asli.
## Catatan



Contoh: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->Remove(plusElement);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [IMathElementCollection](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)