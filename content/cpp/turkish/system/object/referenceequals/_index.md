---
title: ReferenceEquals()
second_title: Aspose.Slides for C++ API Referansı
description: "String ve nullptr durumu için Object::ReferenceEquals'nin uzmanlaştırması."
type: docs
weight: 261
url: /tr/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) metodu

[Object::ReferenceEquals](./)'nin string ve nullptr durumları için uzmanlaştırması.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) nullptr ile karşılaştırmak için. |

### Dönüş Değeri

string null ise true, aksi takdirde false.

## Object::ReferenceEquals(String const\&, String const\&) metodu

[Object::ReferenceEquals](./)'nin string durumları için uzmanlaştırması.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | Karşılaştırılacak ilk string. |
| str2 | [String](../../string/) const\& | Karşılaştırılacak ikinci string. |

### Dönüş Değeri

string'ler eşleşiyorsa true, aksi takdirde false.

## Object::ReferenceEquals(ptr const\&, ptr const\&) metodu

Nesneleri referansla karşılaştırır.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | Karşılaştırılacak ilk gösterici. |
| objB | [ptr](../ptr/) const\& | Karşılaştırılacak ikinci gösterici. |

### Dönüş Değeri

Göstericiler eşleşiyorsa true, aksi takdirde false.

## Object::ReferenceEquals(T const\&, T const\&) metodu

Nesneleri referansla karşılaştırır.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Karşılaştırılacak nesnelerin türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| objA | T const\& | Karşılaştırılacak ilk nesne. |
| objB | T const\& | Karşılaştırılacak ikinci nesne. |

### Dönüş Değeri

Nesne adresleri eşleşiyorsa true, aksi takdirde false.

## Object::ReferenceEquals(T const\&, std::nullptr_t) metodu

Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Karşılaştırılacak nesnenin türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| objA | T const\& | Karşılaştırılacak ilk nesne. |

### Dönüş Değeri

Değer tipleri null olamayacağı için her zaman false döner.

## Bakınız

* Typedef [ptr](../ptr/)
* Class [String](../../string/)
* Class [Object](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)