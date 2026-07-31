---
title: SetColumnAlignment()
second_title: Referensi API Aspose.Slides untuk C++
description: Atur perataan horizontal kolom yang ditentukan
type: docs
weight: 261
url: /id/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) metode

Atur perataan horizontal kolom yang ditentukan

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnIndex | **int32_t** | Indeks kolom berbasis nol |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nilai baru dari perataan horizontal kolom yang ditentukan |
## Catatan

Contoh: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## Lihat Juga

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Kelas [MathMatrix](../)
* Ruang nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)