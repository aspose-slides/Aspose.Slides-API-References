---
title: SetColumnsAlignment()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur perataan horizontal kolom yang ditentukan
type: docs
weight: 274
url: /id/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) metode

Atur perataan horizontal kolom yang ditentukan

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnIndex | **int32_t** | Indeks berbasis nol dari kolom pertama untuk mengatur perataan |
| columnsCount | **uint32_t** | Jumlah kolom untuk menentukan perataan |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nilai baru perataan horizontal kolom yang ditentukan |
## Catatan



Contoh: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Lihat Juga

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)