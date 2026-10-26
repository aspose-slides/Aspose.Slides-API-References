---
title: idx_get()
second_title: Aspose.Slides için C++ API Referansı
description: Matris öğesi
type: docs
weight: 209
url: /tr/aspose.slides.mathtext/mathmatrix/idx_get/
---
## MathMatrix::idx_get(int32_t, int32_t) yöntemi

Matris öğesi

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathMatrix::idx_get(int32_t row, int32_t column) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| row | **int32_t** | Öğeyi almak için satırın sıfır tabanlı indeksi |
| column | **int32_t** | Öğeyi almak için sütunun sıfır tabanlı indeksi |

### Dönüş Değeri


## Açıklamalar



Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathMatrix](../)
* İsim Uzayı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)