---
title: InsertColumnAfter()
second_title: C++ için Aspose.Slides API Referansı
description: Belirtilen sütunun ardından yeni bir sütun ekler. Yeni sütundaki tüm öğeler başlangıçta null olur.
type: docs
weight: 326
url: /tr/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) method

Belirtilen sütunun ardından yeni bir sütun ekler. Yeni sütundaki tüm öğeler başlangıçta null olur.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnIndex | **int32_t** | Yeni bir sütun eklenmek istenen sütunun indeksi |
## Açıklamalar

Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Diğer Bağlantılar

* Sınıf [IMathMatrix](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)