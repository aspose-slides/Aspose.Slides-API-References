---
title: NotNullAreEqualImpl()
second_title: Aspose.Slides for C++ API 參考
description: 等值比較 陣列或清單.
type: docs
weight: 40
url: /zh-hant/system.testpredicates.details.sharedptrasserts/notnullareequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 函式

等值比較 陣列或清單。

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左側容器型別。 |
| T2 | 右側容器型別。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const T1\& | 左側值。 |
| rhs | const T2\& | 右側值。 |
| s | long long | 服務參數，用作函式實作的選擇子；此參數的值會被忽略 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 函式

等值比較 IEnumerable 實例。

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左側元素型別。 |
| T2 | 右側元素型別。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const T1\& | 左側值。 |
| rhs | const T2\& | 右側值。 |
| s | long long | 服務參數，用作函式實作的選擇子；此參數的值會被忽略 |

### 返回值

gtest 風格的斷言結果。

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) 函式

等值比較 未知類型，使用 Equals 方法。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左側物件型別。 |
| T2 | 右側物件型別。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const T1\& | 左側值。 |
| rhs | const T2\& | 右側值。 |

### 返回值

gtest 風格的斷言結果。

## 另請參閱

* 型別定義 [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* 型別定義 [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* 結構 [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* 命名空間 [System::TestPredicates::Details::SharedPtrAsserts](../)
* 函式庫 [Aspose.Slides](../../)