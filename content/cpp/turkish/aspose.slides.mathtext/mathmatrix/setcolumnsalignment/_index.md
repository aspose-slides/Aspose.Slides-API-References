---
title: SetColumnsAlignment()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen sütunların yatay hizalamasını ayarlar
type: docs
weight: 274
url: /tr/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) yöntemi

Belirtilen sütunların yatay hizalamasını ayarlar

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnIndex | **int32_t** | Hizalamanın ayarlanacağı ilk sütunun sıfır tabanlı indeksi |
| columnsCount | **uint32_t** | Hizalamanın belirtileceği sütun sayısı |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Belirtilen sütunun yeni yatay hizalama değeri |
## Açıklamalar

Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Ayrıca Bakınız

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Sınıf [MathMatrix](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)