---
title: idx_set()
second_title: Aspose.Slides for C++ API Referansı
description: Matrisin öğesi
type: docs
weight: 222
url: /tr/aspose.slides.mathtext/mathmatrix/idx_set/
---
## MathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) yöntem

Matrisin öğesi

```cpp
void Aspose::Slides::MathText::MathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value) override
```

### Parametreler

| Parameter | Type | Açıklama |
| --- | --- | --- |
| row | **int32_t** | Öğeyi almak için satırın sıfır tabanlı indeksi |
| column | **int32_t** | Öğeyi almak için sütunun sıfır tabanlı indeksi |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |
## Açıklamalar



Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathMatrix](../)
* İsim Uzayı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)