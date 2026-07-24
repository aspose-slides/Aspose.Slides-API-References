---
title: InsertRowBefore()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen satırın önüne yeni bir satır ekleyin. Yeni satırdaki tüm öğeler başlangıçta null'dur.
type: docs
weight: 274
url: /tr/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) metodu

Belirtilen satırın önüne yeni bir satır ekleyin. Yeni satırdaki tüm öğeler başlangıçta null'dur.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| rowIndex | **int32_t** | Yeni bir satır eklenmeden önceki satırın indeksi |
## Açıklamalar



Örnek:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## Ayrıca Bakınız

* Sınıf [IMathMatrix](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)