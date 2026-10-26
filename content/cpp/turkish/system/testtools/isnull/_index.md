---
title: IsNull()
second_title: Aspose.Slides için C++ API Referansı
description: Belirli bir değerin null olup olmadığını denetler. Aritmetik ve enum tipleri için sürüm.
type: docs
weight: 1
url: /tr/system/testtools/isnull/
---
## TestTools::IsNull(T) yöntemi


Belirli bir değerin null olup olmadığını denetler. [Version](../../version/) aritmetik ve enum türleri için.

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```


### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | Type of value being checked. |

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | Value to check for null. |

### Dönüş Değeri

Her zaman false döndürür.

## TestTools::IsNull(const T\&) yöntemi


Belirli bir değerin null olup olmadığını denetler. [Version](../../version/) aritmetik olmayan ve enum olmayan değer tipleri için.

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```


### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | Type of value being checked. |

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | Value to check for null. |

### Dönüş Değeri

Nesne nullptr ile karşılaştırıldığında true, aksi takdirde false.

## TestTools::IsNull(const SharedPtr\<T\>\&) yöntemi


Belirli bir değerin null olup olmadığını denetler. [Version](../../version/) aritmetik olmayan değer tipleri için.

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```


### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | Type of value being checked. |

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | Value to check for null. |

### Dönüş Değeri

Nesne nullptr ile karşılaştırıldığında true, aksi takdirde false.

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) yöntemi


Belirli bir değerin null olup olmadığını denetler. [Version](../../version/) anahtar-değer çiftleri için.

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```


### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| K | Key type. |
| V | Value type. |

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | Pair object. |

### Dönüş Değeri

Çift null olarak kabul edilirse true, aksi takdirde false.

## TestTools::IsNull(const System::String\&) yöntemi


Dizginin null olup olmadığını denetler.

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) denetlenecek. |

### Dönüş Değeri

Dize null olarak kabul edilirse true, aksi takdirde false.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)