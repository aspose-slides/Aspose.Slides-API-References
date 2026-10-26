---
title: SetColumnAlignment()
second_title: Referensi API Aspose.Slides untuk C++
description: Atur perataan horizontal kolom yang ditentukan
type: docs
weight: 248
url: /id/aspose.slides.mathtext/imathmatrix/setcolumnalignment/
---
## IMathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) metode

Atur perataan horizontal kolom yang ditentukan

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val)=0
```

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnIndex | **int32_t** | Indeks kolom berbasis nol |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nilai baru perataan horizontal kolom yang ditentukan |
## Catatan



Contoh: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## Lihat Juga

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Kelas [IMathMatrix](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)