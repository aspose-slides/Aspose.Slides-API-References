---
title: AreSameImpl()
second_title: C++ için Aspose.Slides API Referansı
description: Aynı-olduklarını akıllı işaretçilerle karşılaştırır.
type: docs
weight: 79
url: /tr/system.testpredicates/aresameimpl/
---
## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) fonksiyon

Aynı-olduklarını akıllı işaretçilerle karşılaştırır.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| s | long long | Uygulamanın seçicisi olarak hizmet eden bir servis parametresi; parametrenin değeri yok sayılır |

### Dönüş Değeri

gtest-styled doğrulama sonucu.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) fonksiyon

Aynı-olduklarını istisnalarla karşılaştırır.

```cpp
template<typename T1,typename T2> std::enable_if<IsExceptionWrapper<T1>::value &&IsExceptionWrapper<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| s | long long | Uygulamanın seçicisi olarak hizmet eden bir servis parametresi; parametrenin değeri yok sayılır |

### Dönüş Değeri

gtest-styled doğrulama sonucu.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, int) fonksiyon

Aynı-olduklarını işaretçi olmayan değerlerle karşılaştırır.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
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

### Dönüş Değeri

gtest-styled doğrulama sonucu.

## See Also

* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsExceptionWrapper](../../system/isexceptionwrapper/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)