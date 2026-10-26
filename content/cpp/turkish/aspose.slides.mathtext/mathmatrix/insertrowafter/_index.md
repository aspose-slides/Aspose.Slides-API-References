---
title: InsertRowAfter()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen satırın sonrasına yeni bir satır ekler. Yeni satırdaki tüm elemanlar başlangıçta nulldır.
type: docs
weight: 300
url: /tr/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) metodu


Belirtilen satırın sonrasına yeni bir satır ekler. Yeni satırdaki tüm elemanlar başlangıçta nulldır.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rowIndex | **int32_t** | Yeni bir satır eklenmesi istenen satırın indeksi |
## Açıklamalar



Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Ayrıca Bakınız

* Sınıf [MathMatrix](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)