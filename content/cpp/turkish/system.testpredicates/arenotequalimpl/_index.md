---
title: AreNotEqualImpl()
second_title: Aspose.Slides for C++ API Referansı
description: Eşit-değil, değerlerden birini veya ikisini Decimal olarak karşılaştırır.
type: docs
weight: 53
url: /tr/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Eşit-değil, değerlerden birini veya ikisini [Decimal](../../system/decimal/) olarak karşılaştırır.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS nesne türü. |
| T2 | RHS nesne türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const T1\& | LHS değeri. |
| rhs | const T2\& | RHS değeri. |
| s | long long | Bir hizmet parametresi, fonksiyonun uygulanmasını seçen bir seçici olarak hizmet eder; parametrenin değeri yok sayılır |

### Dönüş Değeri

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

Eşit-değil, iki [System::String](../../system/string/) değerini karşılaştırır ve bir üye işlevini null [String](../../system/string/) üzerinde çağırmaktan korur. Aynı tümdengelim tabanlı dışlama nedenleri için AreEqualImpl [String](../../system/string/) aşırı yüklemesi gibi şablonlanmıştır.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tür, [System::String](../../system/string/) ile sınırlı. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const T\& | LHS değeri. |
| rhs | const T\& | RHS değeri. |
| s | long long | Bir hizmet parametresi, fonksiyonun uygulanmasını seçen bir seçici olarak hizmet eder; parametrenin değeri yok sayılır |

### Dönüş Değeri

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

Eşit-değil, sağlanan Equals yöntemi kullanılarak işaretçi olmayan türleri karşılaştırır.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const T\& | LHS değeri. |
| rhs | const T\& | RHS değeri. |
| s | long long | Bir hizmet parametresi, fonksiyonun uygulanmasını seçen bir seçici olarak hizmet eder; parametrenin değeri yok sayılır |

### Dönüş Değeri

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) function

Eşit-değil, sağlanan Equals yöntemi kullanılarak işaretçi olmayan türleri karşılaştırır.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | T\& | LHS değeri. |
| rhs | const T\& | RHS değeri. |
| s | long long | Bir hizmet parametresi, fonksiyonun uygulanmasını seçen bir seçici olarak hizmet eder; parametrenin değeri yok sayılır |

### Dönüş Değeri

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

Eşit-değil, sağlanan != operatörü kullanılarak işaretçi olmayan türleri karşılaştırır.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const T\& | LHS değeri. |
| rhs | const T\& | RHS değeri. |
| s | long long | Bir hizmet parametresi, fonksiyonun uygulanmasını seçen bir seçici olarak hizmet eder; parametrenin değeri yok sayılır |

### Dönüş Değeri

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) function

Eşit-değil, kutulanabilir [SmartPtr](../../system/smartptr/) değerleri çözerek karşılaştırır.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | T | LHS değeri. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS değeri. |
| s | long long | Bir hizmet parametresi, fonksiyonun uygulanmasını seçen bir seçici olarak hizmet eder; parametrenin değeri yok sayılır |

### Dönüş Değeri

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) function

Eşit-değil, kutulanabilir [SmartPtr](../../system/smartptr/) değerleri çözerek karşılaştırır.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS değeri. |
| rhs | T | RHS değeri. |
| s | long long | Bir hizmet parametresi, fonksiyonun uygulanmasını seçen bir seçici olarak hizmet eder; parametrenin değeri yok sayılır |

### Dönüş Değeri

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) function

Eşit-değil, rastgele bir türü nullptr ile karşılaştırır.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | T | LHS değeri. |
| s | std::nullptr_t | Bir hizmet parametresi, fonksiyonun uygulanmasını seçen bir seçici olarak hizmet eder; parametrenin değeri yok sayılır |

### Dönüş Değeri

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) function

Eşit-değil, rastgele bir türü nullptr ile karşılaştırır.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../system/object/) tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| rhs | std::nullptr_t | RHS değeri. |
| s | T | Bir hizmet parametresi, fonksiyonun uygulanmasını seçen bir seçici olarak hizmet eder; parametrenin değeri yok sayılır |

### Dönüş Değeri

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Eşit-değil, işaretçi türlerini karşılaştırır.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS türü. |
| T2 | RHS türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | const T1\& | LHS değeri. |
| rhs | const T2\& | RHS değeri. |
| s | long long | Bir hizmet parametresi, fonksiyonun uygulanmasını seçen bir seçici olarak hizmet eder; parametrenin değeri yok sayılır |

### Dönüş Değeri

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) function

Eşit-değil, rastgele türleri gtest algoritmaları kullanarak karşılaştırır.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | LHS türü. |
| T2 | RHS türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs_expr | const char * | LHS ifadesi. |
| rhs_expr | const char * | RHS ifadesi. |
| lhs | T1 | LHS değeri. |
| rhs | T2 | RHS değeri. |

### Dönüş Değeri

gtest-styled assertion result.

## Bakınız

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Sınıf [String](../../system/string/)
* Sınıf [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Ad Alanı [System::TestPredicates](../)
* Library [Aspose.Slides](../../)