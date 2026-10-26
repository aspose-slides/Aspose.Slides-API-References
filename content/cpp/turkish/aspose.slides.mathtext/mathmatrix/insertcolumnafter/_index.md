---
title: InsertColumnAfter()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sütunun ardından yeni bir sütun eklenir. Yeni sütundaki tüm öğeler başlangıçta null'dur.
type: docs
weight: 339
url: /tr/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) metot

Belirtilen sütunun ardından yeni bir sütun ekler. Yeni sütundaki tüm öğeler başlangıçta null'dur.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnIndex | **int32_t** | Yeni bir sütun eklenmesi gereken sütunun indeksi |
## Açıklamalar

Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Ayrıca Bakınız

* Sınıf [MathMatrix](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)