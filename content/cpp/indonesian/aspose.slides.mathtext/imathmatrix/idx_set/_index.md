---
title: idx_set()
second_title: Referensi API Aspose.Slides untuk C++
description: Elemen matriks
type: docs
weight: 222
url: /id/aspose.slides.mathtext/imathmatrix/idx_set/
---
## IMathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) metode

Elemen matriks

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value)=0
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| row | **int32_t** | Indeks berbasis nol dari baris untuk mendapatkan item |
| column | **int32_t** | Indeks berbasis nol dari kolom untuk mendapatkan item |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |
## Catatan



Contoh: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)