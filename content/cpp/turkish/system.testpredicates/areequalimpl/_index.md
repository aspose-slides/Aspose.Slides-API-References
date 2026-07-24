---
title: AreEqualImpl()
second_title: Aspose.Slides for C++ API Referansı
description: Kayan nokta sayıları, aritmetik tiplerle eşit karşılaştırır.
type: docs
weight: 27
url: /tr/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) fonksiyon

Kayan nokta tiplerini aritmetik tiplerle eşit karşılaştırır.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const T1 | LHS değeri. |
| rhs | const T2 | RHS değeri. |
| s | long long | Fonksiyonun uygulanmasını seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) fonksiyon

Değerleri eşit karşılaştırır; bir veya ikisi de [Decimal](../../system/decimal/) olabilir.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const T1\& | LHS değeri. |
| rhs | const T2\& | RHS değeri. |
| s | long long | Fonksiyonun uygulanmasını seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) fonksiyon

Sağlanan Equals yöntemi kullanılarak işaretçi olmayan tipleri eşit karşılaştırır.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const T\& | LHS değeri. |
| rhs | const T\& | RHS değeri. |
| s | long long | Fonksiyonun uygulanmasını seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) fonksiyon

Sağlanan Equals yöntemi kullanılarak işaretçi olmayan tipleri eşit karşılaştırır.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | T\& | LHS değeri. |
| rhs | const T\& | RHS değeri. |
| s | long long | Fonksiyonun uygulanmasını seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) fonksiyon

Sağlanan operator == kullanılarak işaretçi olmayan tipleri eşit karşılaştırır.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const T\& | LHS değeri. |
| rhs | const T\& | RHS değeri. |
| s | long long | Fonksiyonun uygulanmasını seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) fonksiyon

Boxable tipleri [SmartPtr](../../system/smartptr/) değerleriyle eşit karşılaştırır.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | T | LHS değeri. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS değeri. |
| s | long long | Fonksiyonun uygulanmasını seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) fonksiyon

Boxable tipleri [SmartPtr](../../system/smartptr/) değerleriyle eşit karşılaştırır.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS değeri. |
| rhs | T | RHS değeri. |
| s | long long | Fonksiyonun uygulanmasını seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) fonksiyon

String literal'ı [SmartPtr](../../system/smartptr/) değerleriyle unboxing kullanarak eşit karşılaştırır.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const char16_t * | LHS değeri. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS değeri. |
| s | long long | Fonksiyonun uygulanmasını seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) fonksiyon

String literal'ı [SmartPtr](../../system/smartptr/) değerleriyle unboxing kullanarak eşit karşılaştırır.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS değeri. |
| rhs | const char16_t * | RHS değeri. |
| s | long long | Fonksiyonun uygulanmasını seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) fonksiyon

Rastgele tipi nullptr ile eşit karşılaştırır.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | T | LHS değeri. |
| s | std::nullptr_t | Fonksiyonun uygulanmasını seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) fonksiyon

Rastgele tip nullptr ile eşit karşılaştırır.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| rhs | std::nullptr_t | RHS değeri. |
| s | T | Fonksiyonun uygulanmasını seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) fonksiyon

Pointer tiplerini eşit karşılaştırır.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS tipi. |
| T2 | RHS tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const T1\& | LHS değeri. |
| rhs | const T2\& | RHS değeri. |
| s | long long | Fonksiyonun uygulanmasını seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) fonksiyon

Pointer tiplerini eşit karşılaştırır.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS tipi. |
| T2 | RHS tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const T1\& | LHS değeri. |
| rhs | const T2\& | RHS değeri. |
| s | long long | Fonksiyonun uygulanmasını seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) fonksiyon

Rastgele bir tipi [Nullable](../../system/nullable/) değeriyle eşit karşılaştırır.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS tipi. |
| T2 | RHS tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | T1 | LHS değeri. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | RHS değeri. |
| s | long long | Fonksiyonun uygulanmasını seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) fonksiyon

[Nullable](../../system/nullable/) değerini rastgele bir tip ile eşit karşılaştırır.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS tipi. |
| T2 | RHS tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | LHS değeri. |
| rhs | T2 | RHS değeri. |
| s | long long | Fonksiyonun uygulanmasını seçen bir hizmet parametresi; parametrenin değeri göz ardı edilir |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) fonksiyon

Rastgele tipleri gtest algoritmaları kullanarak eşit karşılaştırır.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS tipi. |
| T2 | RHS tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | T1 | LHS değeri. |
| rhs | T2 | RHS değeri. |

### Dönüş Değeri

gtest tarzı doğrulama sonucu.

## Ayrıca Bakınız

* Tip Tanımlama [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Tip Tanımlama [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Tip Tanımlama [SharedPtr](../../system/sharedptr/)
* Sınıf [Object](../../system/object/)
* Sınıf [Stream](../../system.io/stream/)
* Sınıf [Nullable](../../system/nullable/)
* Yapı [IsSmartPtr](../../system/issmartptr/)
* Yapı [IsBoxable](../../system/isboxable/)
* Yapı [IsStringByteSequence](../../system/isstringbytesequence/)
* Yapı [IsNullable](../../system/isnullable/)
* AdAlanı [System::TestPredicates](../)
* Kütüphane [Aspose.Slides](../../)