---
title: AreNotEqualImpl()
second_title: Aspose.Slides for C++ API 參考
description: 非等比較值，當其中一個或兩個皆為 Decimal 時。
type: docs
weight: 53
url: /zh-hant/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function


非等比較值其中一個或兩個為 [Decimal](../../system/decimal/)。

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左側物件類型。 |
| T2 | 右側物件類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | const T1\& | 左側值。 |
| rhs | const T2\& | 右側值。 |
| s | long long | 服務參數，用於選擇函式的實作；此參數的值會被忽略 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function


非等比較非指標類型，使用提供的 Equals 方法。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | const T\& | 左側值。 |
| rhs | const T\& | 右側值。 |
| s | long long | 服務參數，用於選擇函式的實作；此參數的值會被忽略 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) function


非等比較非指標類型，使用提供的 Equals 方法。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | T\& | 左側值。 |
| rhs | const T\& | 右側值。 |
| s | long long | 服務參數，用於選擇函式的實作；此參數的值會被忽略 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function


非等比較非指標類型，使用 operator != 提供的比較。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | const T\& | 左側值。 |
| rhs | const T\& | 右側值。 |
| s | long long | 服務參數，用於選擇函式的實作；此參數的值會被忽略 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) function


非等比較可裝箱的 [SmartPtr](../../system/smartptr/) 值，透過解除裝箱。

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | T | 左側值。 |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | 右側值。 |
| s | long long | 服務參數，用於選擇函式的實作；此參數的值會被忽略 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) function


非等比較可裝箱的 [SmartPtr](../../system/smartptr/) 值，透過解除裝箱。

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | 左側值。 |
| rhs | T | 右側值。 |
| s | long long | 服務參數，用於選擇函式的實作；此參數的值會被忽略 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) function


非等比較隨機類型與 nullptr。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | T | 左側值。 |
| s | std::nullptr_t | 服務參數，用於選擇函式的實作；此參數的值會被忽略 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) function


非等比較隨機類型與 nullptr。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| rhs | std::nullptr_t | 右側值。 |
| s | T | 服務參數，用於選擇函式的實作；此參數的值會被忽略 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function


相等比較指標類型。

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左側類型。 |
| T2 | 右側類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | const T1\& | 左側值。 |
| rhs | const T2\& | 右側值。 |
| s | long long | 服務參數，用於選擇函式的實作；此參數的值會被忽略 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) function


相等比較隨機類型，使用 gtest 演算法。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左側類型。 |
| T2 | 右側類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | T1 | 左側值。 |
| rhs | T2 | 右側值。 |

### 回傳值

gtest 風格的斷言結果。

## 參見

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)