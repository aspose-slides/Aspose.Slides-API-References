---
title: idx_set()
second_title: Aspose.Slides for C++ API Referansı
description: Matrisin öğeleri
type: docs
weight: 222
url: /tr/aspose.slides.mathtext/imathmatrix/idx_set/
---
## IMathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) yöntem

Matrisin öğeleri

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
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

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathMatrix](../)
* İsim alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)