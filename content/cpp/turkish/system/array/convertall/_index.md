---
title: ConvertAll()
second_title: Aspose.Slides C++ API Referansı
description: Yeni bir Array nesnesi oluşturur ve belirtilen dizi öğelerini, belirtilen converter delegate kullanılarak OutputType türüne dönüştürerek doldurur.
type: docs
weight: 625
url: /tr/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) metodu

Belirtilen dönüştürücü temsilcisi kullanılarak, belirtilen dizinin öğeleri **OutputType** türüne dönüştürülür ve yeni bir [Array](../) nesnesi oluşturularak doldurulur.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| InputType | Girdi dizisinin öğelerinin türü |
| OutputType | Sonuç dizisinin öğelerinin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Bir [Array](../) nesnesi |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | Girdi dizisinin her bir öğesini **OutputType** türündeki eşdeğer değerlere dönüştürmek için kullanılan bir Converter nesnesi |

### Dönüş Değeri

Yeni bir dizi; **input_array** değerlerine eşdeğer **OutputType** türündeki değerleri içerir.

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) metodu

Belirtilen dönüştürücü fonksiyon nesnesi kullanılarak, belirtilen dizinin öğeleri **OutputType** türüne dönüştürülür ve yeni bir [Array](../) nesnesi oluşturularak doldurulur.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| InputType | Girdi dizisinin öğelerinin türü |
| OutputType | Sonuç dizisinin öğelerinin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Bir [Array](../) nesnesi |
| converter | std::function\<OutputType(InputType)> | Girdi dizisinin her bir öğesini **OutputType** türündeki eşdeğer değerlere dönüştürmek için kullanılan bir fonksiyon nesnesi |

### Dönüş Değeri

Yeni bir dizi; **input_array** değerlerine eşdeğer **OutputType** türündeki değerleri içerir.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)