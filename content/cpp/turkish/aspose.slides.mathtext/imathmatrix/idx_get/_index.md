---
title: idx_get()
second_title: Aspose.Slides C++ için API Referansı
description: Matrisin elemanları
type: docs
weight: 209
url: /tr/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) metod


Matrisin elemanları

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| row | **int32_t** | Öğeyi almak için satırın sıfırdan başlayan dizini |
| column | **int32_t** | Öğeyi almak için sütunun sıfırdan başlayan dizini |

### Dönüş Değeri


## Açıklamalar



Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathMatrix](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)