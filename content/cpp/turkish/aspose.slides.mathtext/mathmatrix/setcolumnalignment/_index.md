---
title: SetColumnAlignment()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sütunun yatay hizalamasını ayarlar
type: docs
weight: 261
url: /tr/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) method


Belirtilen sütunun yatay hizalamasını ayarlar

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnIndex | **int32_t** | Sıfır tabanlı sütun indeksi |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Belirtilen sütunun yatay hizalamasının yeni değeri |
## Açıklamalar



Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## İlgili

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Sınıf [MathMatrix](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)