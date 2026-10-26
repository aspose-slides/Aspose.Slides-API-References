---
title: InsertRowAfter()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen satırdan sonra yeni bir satır ekler. Yeni satırdaki tüm öğeler başlangıçta null'dur.
type: docs
weight: 287
url: /tr/aspose.slides.mathtext/imathmatrix/insertrowafter/
---
## IMathMatrix::InsertRowAfter(int32_t) method


Belirtilen satırdan sonra yeni bir satır ekler. Yeni satırdaki tüm öğeler başlangıçta null’dur.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowAfter(int32_t rowIndex)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rowIndex | **int32_t** | Yeni bir satırın ekleneceği satırın indeksi |
## Açıklamalar



Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Ayrıca Bakınız

* Sınıf [IMathMatrix](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)