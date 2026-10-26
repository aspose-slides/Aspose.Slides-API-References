---
title: AreEqualImpl()
second_title: Aspose.Slides for C++ API 參考
description: 比較浮點數與算術類型的相等性。
type: docs
weight: 27
url: /zh-hant/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) 函式


比較浮點數與算術類型的相等性。

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T1 | 左側物件型別。 |
| T2 | 右側物件型別。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const T1 | 左側值。 |
| rhs | const T2 | 右側值。 |
| s | long long | 一個服務參數，用於選擇函式的實作；此參數的值會被忽略。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) 函式


比較值相等，至少有一個為 [Decimal](../../system/decimal/)。

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T1 | 左側物件型別。 |
| T2 | 右側物件型別。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const T1& | 左側值。 |
| rhs | const T2& | 右側值。 |
| s | long long | 一個服務參數，用於選擇函式的實作；此參數的值會被忽略。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T&, const T&, long long) 函式


使用提供的 Equals 方法比較非指標類型的相等性。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 型別。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const T& | 左側值。 |
| rhs | const T& | 右側值。 |
| s | long long | 一個服務參數，用於選擇函式的實作；此參數的值會被忽略。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T&, const T&, long long) 函式


使用提供的 Equals 方法比較非指標類型的相等性。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 型別。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | T& | 左側值。 |
| rhs | const T& | 右側值。 |
| s | long long | 一個服務參數，用於選擇函式的實作；此參數的值會被忽略。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T&, const T&, long long) 函式


使用提供的 == 運算子比較非指標類型的相等性。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 型別。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const T& | 左側值。 |
| rhs | const T& | 右側值。 |
| s | long long | 一個服務參數，用於選擇函式的實作；此參數的值會被忽略。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr<Object>&, long long) 函式


比較可裝箱類型與 [SmartPtr](../../system/smartptr/) 值的相等性。

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 型別。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | T | 左側值。 |
| rhs | const [System::SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)>& | 右側值。 |
| s | long long | 一個服務參數，用於選擇函式的實作；此參數的值會被忽略。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr<Object>&, T, long long) 函式


比較可裝箱類型與 [SmartPtr](../../system/smartptr/) 值的相等性。

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 型別。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const [System::SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)>& | 左側值。 |
| rhs | T | 右側值。 |
| s | long long | 一個服務參數，用於選擇函式的實作；此參數的值會被忽略。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr<Object>&, long long) 函式


使用拆箱比較字串常量與 [SmartPtr](../../system/smartptr/) 值的相等性。

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const char16_t * | 左側值。 |
| rhs | const [System::SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)>& | 右側值。 |
| s | long long | 一個服務參數，用於選擇函式的實作；此參數的值會被忽略。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr<Object>&, const char16_t *, long long) 函式


使用拆箱比較字串常量與 [SmartPtr](../../system/smartptr/) 值的相等性。

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const [System::SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)>& | 左側值。 |
| rhs | const char16_t * | 右側值。 |
| s | long long | 一個服務參數，用於選擇函式的實作；此參數的值會被忽略。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) 函式


比較隨機類型與 nullptr 的相等性。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 型別。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | T | 左側值。 |
| s | std::nullptr_t | 一個服務參數，用於選擇函式的實作；此參數的值會被忽略。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) 函式


比較隨機類型與 nullptr 的相等性。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 型別。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| rhs | std::nullptr_t | 右側值。 |
| s | T | 一個服務參數，用於選擇函式的實作；此參數的值會被忽略。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) 函式


比較指標類型的相等性。

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T1 | 左側型別。 |
| T2 | 右側型別。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const T1& | 左側值。 |
| rhs | const T2& | 右側值。 |
| s | long long | 一個服務參數，用於選擇函式的實作；此參數的值會被忽略。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) 函式


比較指標類型的相等性。

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T1 | 左側型別。 |
| T2 | 右側型別。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const T1& | 左側值。 |
| rhs | const T2& | 右側值。 |
| s | long long | 一個服務參數，用於選擇函式的實作；此參數的值會被忽略。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable<T2>&, long long) 函式


比較隨機類型與 [Nullable](../../system/nullable/) 值的相等性。

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T1 | 左側型別。 |
| T2 | 右側型別。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | T1 | 左側值。 |
| rhs | const [Nullable](../../system/nullable/)<T2>& | 右側值。 |
| s | long long | 一個服務參數，用於選擇函式的實作；此參數的值會被忽略。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable<T1>&, T2, long long) 函式


比較 [Nullable](../../system/nullable/) 值與隨機類型的相等性。

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T1 | 左側型別。 |
| T2 | 右側型別。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const [Nullable](../../system/nullable/)<T1>& | 左側值。 |
| rhs | T2 | 右側值。 |
| s | long long | 一個服務參數，用於選擇函式的實作；此參數的值會被忽略。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) 函式


使用 gtest 演算法比較隨機類型的相等性。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T1 | 左側型別。 |
| T2 | 右側型別。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | T1 | 左側值。 |
| rhs | T2 | 右側值。 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T&, const T&, long long) 函式


比較兩個 [System::String](../../system/string/) 值，防止在空的 [String](../../system/string/) 上呼叫成員函式。此為模板（而非接受 const [String](../../system/string/)& 的普通重載），以使混合型別呼叫——例如將 char16_t 字串常量與 [String](../../system/string/) 比較——無法推導單一一致的 T，從而完全排除該候選，而不是透過 long long/int 選擇參數與通用 AreEqualImpl<T1,T2> 模板競爭，導致模糊的重載解析。

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 型別，受限於 [System::String](../../system/string/)。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const T& | 左側值。 |
| rhs | const T& | 右側值。 |
| s | long long | 一個服務參數，用於選擇函式的實作；此參數的值會被忽略。 |

### 返回值

gtest 風格的斷言結果。

## 另見

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* 類別 [String](../../system/string/)
* 類別 [Object](../../system/object/)
* 類別 [Stream](../../system.io/stream/)
* 類別 [Nullable](../../system/nullable/)
* 結構 [IsSmartPtr](../../system/issmartptr/)
* 結構 [IsBoxable](../../system/isboxable/)
* 結構 [IsStringByteSequence](../../system/isstringbytesequence/)
* 結構 [IsNullable](../../system/isnullable/)
* 命名空間 [System::TestPredicates](../)
* 函式庫 [Aspose.Slides](../../)