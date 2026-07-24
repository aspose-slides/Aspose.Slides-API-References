---
title: AreEqualContainer()
second_title: Aspose.Slides C++ API Referansı
description: Elemanlarda operator == kullanarak iki kapsayıcıyı eşit olarak karşılaştırır. SmartPtr olmayan elemanlar için çalışır.
type: docs
weight: 1
url: /tr/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1&, const T2&) fonksiyon

Elemanlarda operator == kullanarak iki kapsayıcıyı eşit olarak karşılaştırır. SmartPtr olmayan elemanlar için çalışır.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
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

İçerilen öğeler ve boyutlar eşleşiyorsa Doğru, aksi takdirde Yanlış.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1&, const T2&) fonksiyon

Elemanlarda [System::Object::Equals](../../system/object/equals/) kullanarak iki kapsayıcıyı eşit olarak karşılaştırır. [SmartPtr](../../system/smartptr/) öğeler için çalışır.

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
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

İçerilen öğeler ve boyutlar eşleşiyorsa Doğru, aksi takdirde Yanlış.

## İlgili

* Yapı [IsSmartPtr](../../system/issmartptr/)
* İsim Uzayı [System::TestPredicates::Details::SharedPtrAsserts](../)
* Kütüphane [Aspose.Slides](../../)