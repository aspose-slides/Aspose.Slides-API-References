---
title: AreSameImpl()
second_title: Aspose.Slides for C++ API 參考
description: Are-same 比較智慧指標。
type: docs
weight: 79
url: /zh-hant/system.testpredicates/aresameimpl/
---
## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) 函式

Are-same 比較智慧指標。

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | 左側物件類型。 |
| T2 | 右側物件類型。 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const T1\& | 左側值。 |
| rhs | const T2\& | 右側值。 |
| s | long long | 作為函式實作選擇器的服務參數；此參數的值會被忽略。 |

### Return Value

gtest 風格的斷言結果。

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) 函式

Are-same 比較例外。

```cpp
template<typename T1,typename T2> std::enable_if<IsExceptionWrapper<T1>::value &&IsExceptionWrapper<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | 左側物件類型。 |
| T2 | 右側物件類型。 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const T1\& | 左側值。 |
| rhs | const T2\& | 右側值。 |
| s | long long | 作為函式實作選擇器的服務參數；此參數的值會被忽略。 |

### Return Value

gtest 風格的斷言結果。

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, int) 函式

Are-same 比較非指標值。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | 左側物件類型。 |
| T2 | 右側物件類型。 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const T1\& | 左側值。 |
| rhs | const T2\& | 右側值。 |

### Return Value

gtest 風格的斷言結果。

## See Also

* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsExceptionWrapper](../../system/isexceptionwrapper/)
* 命名空間 [System::TestPredicates](../)
* Library [Aspose.Slides](../../)