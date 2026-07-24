---
title: AreEqualData()
second_title: C++ için Aspose.Slides API Referansı
description: "Öğeler üzerinde System::Object::Equals kullanarak iki kapsayıcıyı eşitlik karşılaştırması yapar. SmartPtr öğeleri için çalışır."
type: docs
weight: 14
url: /tr/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) fonksiyon


İki kapsayıcıyı öğeler üzerinde [System::Object::Equals](../../system/object/equals/) kullanarak eşitlik karşılaştırması yapar. [SmartPtr](../../system/smartptr/) öğeler için çalışır.

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS kapsayıcı türü. |
| T2 | RHS kapsayıcı türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | const T1\& | LHS kapsayıcı referansı. |
| rhs | const T2\& | RHS kapsayıcı referansı. |

### Dönüş Değeri

İçerdiği öğeler ve boyutlar eşleşiyorsa doğru, aksi takdirde yanlış.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) fonksiyon


İki kapsayıcıyı öğeler üzerinde operator == kullanarak eşitlik karşılaştırması yapar. SmartPtr olmayan öğeler için çalışır.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS kapsayıcı türü. |
| T2 | RHS kapsayıcı türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | const T1\& | LHS kapsayıcı. |
| rhs | const T2\& | RHS kapsayıcı. |

### Dönüş Değeri

İçerdiği öğeler ve boyutlar eşleşiyorsa doğru, aksi takdirde yanlış.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T\&, const T\&) fonksiyon


Aynı türe sahip iki kapsayıcıyı eşitlik karşılaştırması yapar. SmartPtr olmayan öğeler için çalışır.

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS kapsayıcı türü. |
| T2 | RHS kapsayıcı türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | const T\& | LHS kapsayıcı. |
| rhs | const T\& | RHS kapsayıcı. |

### Dönüş Değeri

İçerdiği öğeler ve boyutlar eşleşiyorsa doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Yapı [IsSmartPtr](../../system/issmartptr/)
* Ad Alanı [System::TestPredicates::Details::SharedPtrAsserts](../)
* Kütüphane [Aspose.Slides](../../)