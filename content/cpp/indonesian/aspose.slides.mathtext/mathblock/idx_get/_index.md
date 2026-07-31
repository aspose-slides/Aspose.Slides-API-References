---
title: idx_get()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan IMathElement pada indeks yang ditentukan.
type: docs
weight: 27
url: /id/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) metode


Mendapatkan [IMathElement](../../imathelement/) pada indeks yang ditentukan.

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol dari item |

### Nilai Kembali

Elemen matematis.

## Catatan



Contoh: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathBlock](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)