---
title: SetColumnsAlignment()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sütunların yatay hizalamasını ayarlar
type: docs
weight: 261
url: /tr/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---
## IMathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) metot

Belirtilen sütunların yatay hizalamasını ayarlar

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnIndex | **int32_t** | Hizalama ayarlanacak ilk sütunun sıfırla başlayan indeksi |
| columnsCount | **uint32_t** | Hizalamanın belirleneceği sütun sayısı |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Belirtilen sütunun yeni yatay hizalama değeri |
## Açıklamalar



Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## İlgili

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Sınıf [IMathMatrix](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)