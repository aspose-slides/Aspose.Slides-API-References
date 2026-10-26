---
title: GetColumnAlignment()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sütunun yatay hizalamasını al
type: docs
weight: 235
url: /tr/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(int32_t) yöntemi

Belirtilen sütunun yatay hizalamasını al

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnIndex | **int32_t** | Sıfır tabanlı sütun indeksi |

### Dönüş Değeri

Belirtilen sütunun yatay hizalaması

## Açıklamalar

Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Diğer Bilgiler

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Sınıf [IMathMatrix](../)
* İsim Uzayı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)