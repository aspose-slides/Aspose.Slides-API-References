---
title: PrintToStringImpl()
second_title: Aspose.Slides for C++ API Referansı
description: "System::Object alt sınıfını ToString() yöntemi kullanarak dizeye dönüştürür."
type: docs
weight: 14
url: /tr/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) fonksiyon

[System::Object](../../system/object/) alt sınıfını ToString() yöntemi kullanarak dizeye dönüştürür.

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Nihai sınıf türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Yazdırılacak nesnenin işaretçisi. |
| s | long long | Bu parametrenin türüne göre işlev aşırı yüklemesini seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir. |

### Dönüş Değeri

[String](../../system/string/) nesnenin temsili, **value** null ise "nullptr" döner.

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) fonksiyon

[System::Object](../../system/object/) alt sınıfını ToString() yöntemi kullanarak dizeye dönüştürür.

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Nihai sınıf türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | Yazdırılacak nesnenin işaretçisi. |
| s | long long | Bu parametrenin türüne göre işlev aşırı yüklemesini seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir. |

### Dönüş Değeri

[String](../../system/string/) nesnenin temsili, **value** null ise "nullptr" döner.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) fonksiyon

Nesneyi ToString() yöntemi kullanarak dizeye dönüştürür.

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) yazdırılacak. |
| s | long long | Bu parametrenin türüne göre işlev aşırı yüklemesini seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir. |

### Dönüş Değeri

[String](../../system/string/) nesnenin temsili.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) fonksiyon

Nesneyi PrintTo yöntemi kullanarak dizeye dönüştürür.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) yazdırılacak. |
| s | long long | Bu parametrenin türüne göre işlev aşırı yüklemesini seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir. |

### Dönüş Değeri

[String](../../system/string/) nesnenin temsili.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) fonksiyon

Nesneyi PrintTo yöntemi kullanarak dizeye dönüştürür.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) yazdırılacak. |
| s | long long | Bu parametrenin türüne göre işlev aşırı yüklemesini seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir. |

### Dönüş Değeri

[String](../../system/string/) nesnenin temsili.

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) fonksiyon

Çifti dizeye dönüştürür.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | İlk çift tür argümanı. |
| T2 | İkinci çift tür argümanı. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) yazdırılacak. |
| s | long long | Bu parametrenin türüne göre işlev aşırı yüklemesini seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir. |

### Dönüş Değeri

İlk ve ikinci çift bileşenlerinin birleşik dize temsilleri.

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) fonksiyon

Çifti dizeye dönüştürür.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | İlk çift tür argümanı. |
| T2 | İkinci çift tür argümanı. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) yazdırılacak. |
| s | long long | Bu parametrenin türüne göre işlev aşırı yüklemesini seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir. |

### Dönüş Değeri

İlk ve ikinci çift bileşenlerinin birleşik dize temsilleri.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) fonksiyon

STL benzeri kapsayıcıları (en fazla 32 öğe) öğelerini yazarak dizeye dönüştürür.

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) yazdırılacak. |
| s | long long | Bu parametrenin türüne göre işlev aşırı yüklemesini seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir. |

### Dönüş Değeri

İçerilen öğelerin birleşik dize temsilleri.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) fonksiyon

Diğer türleri gtest tarafından sağlanan fonksiyonlarla dizeye dönüştürür.

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) yazdırılacak. |
| s | int | Bu parametrenin türüne göre işlev aşırı yüklemesini seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir. |

### Dönüş Değeri

[String](../../system/string/) nesnenin temsilleri.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [WeakPtr](../../system/weakptr/)
* Class [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* Class [Object](../../system/object/)
* Struct [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* Struct [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Struct [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* Namespace [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)