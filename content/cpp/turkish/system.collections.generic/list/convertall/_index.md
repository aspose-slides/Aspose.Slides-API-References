---
title: ConvertAll()
second_title: Aspose.Slides for C++ API Referansı
description: Farklı bir türe dönüştürülmüş öğelerden bir liste oluşturur.
type: docs
weight: 352
url: /tr/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) metodu


Farklı bir tipe dönüştürülmüş öğelerden bir liste oluşturur.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| OutputType | Çıktı liste öğesi tipi. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | Öğeler dönüşümü için kullanılacak dönüştürücü. |

### Dönüş Değeri

Yeni oluşturulmuş dönüştürülmüş öğeler listesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Converter](../../../system/converter/)
* Sınıf [List](../)
* İsim Alanı [System::Collections::Generic](../../)
* Kütüphane [Aspose.Slides](../../../)