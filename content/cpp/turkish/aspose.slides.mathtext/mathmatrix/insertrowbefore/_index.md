---
title: InsertRowBefore()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen satırın önüne yeni bir satır ekler. Yeni satırdaki tüm öğeler başlangıçta null'dur.
type: docs
weight: 287
url: /tr/aspose.slides.mathtext/mathmatrix/insertrowbefore/
---
## MathMatrix::InsertRowBefore(int32_t) metodu

Yeni bir satır ekler belirtilen satırın önüne. Yeni satırdaki tüm öğeler başlangıçta null'dur.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowBefore(int32_t rowIndex) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rowIndex | **int32_t** | Yeni bir satır eklenmeden önceki satırın indeksi |
## Açıklamalar

Örnek:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## Ayrıca Bakınız

* Sınıf [MathMatrix](../)
* İsim Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)