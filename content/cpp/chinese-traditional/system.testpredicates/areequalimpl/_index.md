---
title: AreEqualImpl()
second_title: Aspose.Slides for C++ API 參考
description: 將浮點數與算術類型進行等值比較。
type: docs
weight: 27
url: /zh-hant/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) 函式


比較浮點數與算術類型的等值。

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左側物件類型。 |
| T2 | 右側物件類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const T1 | 左側值。 |
| rhs | const T2 | 右側值。 |
| s | long long | 用於作為函式實作選擇器的服務參數；此參數的值將被忽略。 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 函式


比較值的等值，當其中一個或兩個為 [Decimal](../../system/decimal/) 時。

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左側物件類型。 |
| T2 | 右側物件類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const T1\& | 左側值。 |
| rhs | const T2\& | 右側值。 |
| s | long long | 用於作為函式實作選擇器的服務參數；此參數的值將被忽略。 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) 函式


比較非指標類型的等值，使用提供的 Equals 方法。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const T\& | 左側值。 |
| rhs | const T\& | 右側值。 |
| s | long long | 用於作為函式實作選擇器的服務參數；此參數的值將被忽略。 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) 函式


比較非指標類型的等值，使用提供的 Equals 方法。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | T\& | 左側值。 |
| rhs | const T\& | 右側值。 |
| s | long long | 用於作為函式實作選擇器的服務參數；此參數的值將被忽略。 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) 函式


比較非指標類型的等值，使用提供的 operator ==。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const T\& | 左側值。 |
| rhs | const T\& | 右側值。 |
| s | long long | 用於作為函式實作選擇器的服務參數；此參數的值將被忽略。 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) 函式


比較可裝箱與 [SmartPtr](../../system/smartptr/) 值的等值。

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | T | 左側值。 |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | 右側值。 |
| s | long long | 用於作為函式實作選擇器的服務參數；此參數的值將被忽略。 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) 函式


比較可裝箱與 [SmartPtr](../../system/smartptr/) 值的等值。

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | 左側值。 |
| rhs | T | 右側值。 |
| s | long long | 用於作為函式實作選擇器的服務參數；此參數的值將被忽略。 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) 函式


使用解除裝箱，將字串文字與 [SmartPtr](../../system/smartptr/) 值比較。

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const char16_t * | 左側值。 |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | 右側值。 |
| s | long long | 用於作為函式實作選擇器的服務參數；此參數的值將被忽略。 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) 函式


使用解除裝箱，將字串文字與 [SmartPtr](../../system/smartptr/) 值比較。

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | 左側值。 |
| rhs | const char16_t * | 右側值。 |
| s | long long | 用於作為函式實作選擇器的服務參數；此參數的值將被忽略。 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) 函式


比較隨機型別與 nullptr 的等值。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | T | 左側值。 |
| s | std::nullptr_t | 用於作為函式實作選擇器的服務參數；此參數的值將被忽略。 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) 函式


比較隨機型別與 nullptr 的等值。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../system/object/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| rhs | std::nullptr_t | 右側值。 |
| s | T | 用於作為函式實作選擇器的服務參數；此參數的值將被忽略。 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 函式


比較指標類型的等值。

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左側類型。 |
| T2 | 右側類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const T1\& | 左側值。 |
| rhs | const T2\& | 右側值。 |
| s | long long | 用於作為函式實作選擇器的服務參數；此參數的值將被忽略。 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 函式


比較指標類型的等值。

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左側類型。 |
| T2 | 右側類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const T1\& | 左側值。 |
| rhs | const T2\& | 右側值。 |
| s | long long | 用於作為函式實作選擇器的服務參數；此參數的值將被忽略。 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) 函式


比較隨機型別與 [Nullable](../../system/nullable/) 值的等值。

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左側類型。 |
| T2 | 右側類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | T1 | 左側值。 |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | 右側值。 |
| s | long long | 用於作為函式實作選擇器的服務參數；此參數的值將被忽略。 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) 函式


比較 [Nullable](../../system/nullable/) 值與隨機型別的等值。

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左側類型。 |
| T2 | 右側類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | 左側值。 |
| rhs | T2 | 右側值。 |
| s | long long | 用於作為函式實作選擇器的服務參數；此參數的值將被忽略。 |

### 回傳值

gtest 風格的斷言結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) 函式


使用 gtest 演算法比較隨機型別的等值。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左側類型。 |
| T2 | 右側類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | T1 | 左側值。 |
| rhs | T2 | 右側值。 |

### 回傳值

gtest 風格的斷言結果。

## 另見

* 類型別名 [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* 類型別名 [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* 類型別名 [SharedPtr](../../system/sharedptr/)
* 類別 [Object](../../system/object/)
* 類別 [Stream](../../system.io/stream/)
* 類別 [Nullable](../../system/nullable/)
* 結構 [IsSmartPtr](../../system/issmartptr/)
* 結構 [IsBoxable](../../system/isboxable/)
* 結構 [IsStringByteSequence](../../system/isstringbytesequence/)
* 結構 [IsNullable](../../system/isnullable/)
* 命名空間 [System::TestPredicates](../)
* 函式庫 [Aspose.Slides](../../)