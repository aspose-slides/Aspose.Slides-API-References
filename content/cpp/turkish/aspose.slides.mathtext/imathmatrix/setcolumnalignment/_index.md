---
title: SetColumnAlignment()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sütunun yatay hizalanmasını ayarlar
type: docs
weight: 248
url: /tr/aspose.slides.mathtext/imathmatrix/setcolumnalignment/
---
## IMathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) method


Belirtilen sütunun yatay hizalanmasını ayarlar

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnIndex | **int32_t** | Sıfır tabanlı sütun indeksi |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Belirtilen sütunun yatay hizalanmasının yeni değeri |
## Açıklamalar



Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## Ayrıca Bakınız

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Sınıf [IMathMatrix](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)