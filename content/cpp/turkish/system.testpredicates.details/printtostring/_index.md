---
title: PrintToString()
second_title: Aspose.Slides for C++ API Referansı
description: Uygun serileştirici fonksiyonunu seçerek nesneyi dizeye yazar.
type: docs
weight: 1
url: /tr/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T&) fonksiyonu


Uygun serileştirici fonksiyonunu seçerek nesneyi dizeye yazdırır.

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) türü. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const T& | [Object](../../system/object/) yazdırmak için. |

### Dönüş Değeri

[String](../../system/string/) nesnenin temsili.

## System::TestPredicates::Details::PrintToString(const T&) fonksiyonu


Elemanlarını (en fazla 32) yazarak ICollection tarzı kapsayıcıları dizeye yazdırır.

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) türü. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const T& | [Object](../../system/object/) yazdırmak için. |

### Dönüş Değeri

İçerilen elemanların birleşik dize temsilleri.

## System::TestPredicates::Details::PrintToString(std::nullptr_t) fonksiyonu


nullptr'ı dizeye yazar.

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```


### Dönüş Değeri

"nullptr" dizesi.

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>\&) fonksiyonu


[IEnumerable<bool>](../../system.collections.generic/ienumerable/) koleksiyonlarını elemanlarını (en fazla 32) yazarak dizeye yazdırır.

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) türü. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)<**bool**>& | [Object](../../system/object/) yazdırmak için. |

### Dönüş Değeri

İçerilen elemanların birleşik dize temsilleri.

## Ayrıca Bakınız

* Sınıf [IEnumerable](../../system.collections.generic/ienumerable/)
* Yapı [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Ad alanı [System::TestPredicates::Details](../)
* Kütüphane [Aspose.Slides](../../)