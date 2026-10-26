---
title: InsertColumnBefore()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen sütundan önce yeni bir sütun ekleyin. Yeni sütundaki tüm öğeler başlangıçta null olur.
type: docs
weight: 313
url: /tr/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) metod


Belirtilen sütundan önce yeni bir sütun ekleyin. Yeni sütundaki tüm öğeler başlangıçta null olur.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnIndex | **int32_t** | Yeni bir sütun eklenmeden önceki sütunun indeksi |
## Açıklamalar



Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Ayrıca Bakınız

* Sınıf [IMathMatrix](../)
* İsim Uzayı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)