---
title: RemoveAt()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghapus elemen pada indeks yang ditentukan dalam koleksi.
type: docs
weight: 170
url: /id/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock::RemoveAt(int32_t) metode

Menghapus elemen pada indeks yang ditentukan dalam koleksi.

```cpp
void Aspose::Slides::MathText::MathBlock::RemoveAt(int32_t index) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol dari elemen yang akan dihapus. |
## Catatan



Contoh: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->RemoveAt(2);
```

## Lihat Juga

* Kelas [MathBlock](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)