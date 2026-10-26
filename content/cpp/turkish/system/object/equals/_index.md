---
title: Equals()
second_title: Aspose.Slides for C++ API Referansı
description: C# Object.Equals söz dizimini kullanarak nesneleri karşılaştırır.
type: docs
weight: 157
url: /tr/system/object/equals/
---
## Object::Equals(ptr) yöntemi


C# [Object.Equals](./) sözdizimi kullanarak nesneleri karşılaştırır.

```cpp
virtual bool System::Object::Equals(ptr obj)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) mevcut nesneyle karşılaştırmak için. |

### Dönüş Değeri

Nesneler eşit kabul ediliyorsa true, aksi takdirde false.

## Object::Equals(T1 const\&, T2 const\&) yöntemi


Referans tipi nesneleri C# tarzında karşılaştırır.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Karşılaştırılacak ilk nesnenin türü. |
| T2 | Karşılaştırılacak ikinci nesnenin türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| objA | T1 const\& | Karşılaştırılacak ilk nesne. |
| objB | T2 const\& | Karşılaştırılacak ikinci nesne. |

### Dönüş Değeri

Nesneler referans veya anlamsal olarak ([Object.Equals](./) benzeri karşılaştırma ile) eşleşiyorsa true, aksi takdirde false.

## Object::Equals(T1 const\&, T2 const\&) yöntemi


Değer tipi nesneleri C# tarzında karşılaştırır.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Karşılaştırılacak ilk nesnenin türü. |
| T2 | Karşılaştırılacak ikinci nesnenin türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| objA | T1 const\& | Karşılaştırılacak ilk nesne. |
| objB | T2 const\& | Karşılaştırılacak ikinci nesne. |

### Dönüş Değeri

Mevcut eşitlik operatörü ile nesneler eşit kabul ediliyorsa true, aksi takdirde false.

## Object::Equals(float const\&, float const\&) yöntemi


IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| objA | **float** const\& | Sol taraf kayan nokta değeri. |
| objB | **float** const\& | Sağ taraf kayan nokta değeri. |

### Dönüş Değeri

**objA** ve **objB** her ikisi de NaN ise veya eşitse true, aksi takdirde false.

## Object::Equals(double const\&, double const\&) yöntemi


IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| objA | **double** const\& | Sol taraf kayan nokta değeri. |
| objB | **double** const\& | Sağ taraf kayan nokta değeri. |

### Dönüş Değeri

**objA** ve **objB** her ikisi de NaN ise veya eşitse true, aksi takdirde false.

## See Also

* Typedef [ptr](../ptr/)
* Sınıf [Object](../)
* Yapı [IsSmartPtr](../../issmartptr/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)