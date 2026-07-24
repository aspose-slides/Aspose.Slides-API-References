---
title: AreNotEqualImpl()
second_title: Aspose.Slides for C++ API Referansı
description: Eşit olmayan karşılaştırma, değerlerden birinin veya ikisinin Decimal olması durumunda yapılır.
type: docs
weight: 53
url: /tr/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) fonksiyon

Eşit olmayan karşılaştırma, değerlerden birinin ya da her ikisinin [Decimal](../../system/decimal/) olması durumunda yapılır.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Sol taraf nesne tipi. |
| T2 | Sağ taraf nesne tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | const T1\& | Sol taraf değeri. |
| rhs | const T2\& | Sağ taraf değeri. |
| s | long long | Uygulamanın seçicisi olarak hizmet eden bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) fonksiyon

Eşit olmayan karşılaştırma, sağlanan Equals yöntemi kullanılarak işaretçi olmayan türler için yapılır.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | const T\& | Sol taraf değeri. |
| rhs | const T\& | Sağ taraf değeri. |
| s | long long | Uygulamanın seçicisi olarak hizmet eden bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) fonksiyon

Eşit olmayan karşılaştırma, sağlanan Equals yöntemi kullanılarak işaretçi olmayan türler için yapılır.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | T\& | Sol taraf değeri. |
| rhs | const T\& | Sağ taraf değeri. |
| s | long long | Uygulamanın seçicisi olarak hizmet eden bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) fonksiyon

Eşit olmayan karşılaştırma, sağlanan != operatörü kullanılarak işaretçi olmayan türler için yapılır.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | const T\& | Sol taraf değeri. |
| rhs | const T\& | Sağ taraf değeri. |
| s | long long | Uygulamanın seçicisi olarak hizmet eden bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) fonksiyon

Eşit olmayan karşılaştırma, [SmartPtr](../../system/smartptr/) değerleriyle kutulanabilir nesneleri kutudan çıkarma kullanarak yapar.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | T | Sol taraf değeri. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Sağ taraf değeri. |
| s | long long | Uygulamanın seçicisi olarak hizmet eden bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) fonksiyon

Eşit olmayan karşılaştırma, [SmartPtr](../../system/smartptr/) değerleriyle kutulanabilir nesneleri kutudan çıkarma kullanarak yapar.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Sol taraf değeri. |
| rhs | T | Sağ taraf değeri. |
| s | long long | Uygulamanın seçicisi olarak hizmet eden bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) fonksiyon

Eşit olmayan karşılaştırma, rastgele bir tip ile nullptr'ı karşılaştırır.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | T | Sol taraf değeri. |
| s | std::nullptr_t | Uygulamanın seçicisi olarak hizmet eden bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) fonksiyon

Eşit olmayan karşılaştırma, rastgele bir tip ile nullptr'ı karşılaştırır.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| rhs | std::nullptr_t | Sağ taraf değeri. |
| s | T | Uygulamanın seçicisi olarak hizmet eden bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) fonksiyon

Eşit karşılaştırma işaretçi tiplerini.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Sol taraf tipi. |
| T2 | Sağ taraf tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | const T1\& | Sol taraf değeri. |
| rhs | const T2\& | Sağ taraf değeri. |
| s | long long | Uygulamanın seçicisi olarak hizmet eden bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) fonksiyon

Eşit karşılaştırma, gtest algoritmaları kullanarak rastgele tipleri karşılaştırır.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Sol taraf tipi. |
| T2 | Sağ taraf tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | Sol taraf ifadesi. |
| rhs_expr | const char * | Sağ taraf ifadesi. |
| lhs | T1 | Sol taraf değeri. |
| rhs | T2 | Sağ taraf değeri. |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## Bakınız

* Tip tanımı [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Tip tanımı [SharedPtr](../../system/sharedptr/)
* Sınıf [Object](../../system/object/)
* Yapı [IsSmartPtr](../../system/issmartptr/)
* Yapı [IsBoxable](../../system/isboxable/)
* Ad alanı [System::TestPredicates](../)
* Kütüphane [Aspose.Slides](../../)