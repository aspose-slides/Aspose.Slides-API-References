---
title: InsertColumnBefore()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen sütunun önüne yeni bir sütun ekler. Yeni sütundaki tüm öğeler başlangıçta null'dir.
type: docs
weight: 326
url: /tr/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) yöntemi


Belirtilen sütunun önüne yeni bir sütun ekler. Yeni sütundaki tüm öğeler başlangıçta null'dir.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnIndex | **int32_t** | Yeni bir sütun eklemeden önceki sütunun indeksi |
## Açıklamalar



Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Bakınız

* Sınıf [MathMatrix](../)
* İsim Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)