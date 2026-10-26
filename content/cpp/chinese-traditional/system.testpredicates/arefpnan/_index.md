---
title: AreFPNaN()
second_title: Aspose.Slides C++ API 參考
description: 命名空間 詳細資訊
type: docs
weight: 1
url: /zh-hant/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) 函式

命名空間 [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```

### 模板參數

| Parameter | Description |
| --- | --- |
| T1 | First floating point type. |
| T2 | Second floating point type. |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | T1 | First floating point value. |
| rhs | T2 | Second floating point value. |

### 返回值

如果 **lhs** 與 **rhs** 皆為浮點數值則回傳 true，否則回傳 false。

## 備註

檢查兩個浮點數值是否皆為 NaN。處理支援非信號 NaN 的情況。

## System::TestPredicates::AreFPNaN(T1, T2) 函式

檢查兩個浮點數值是否皆為 NaN。處理不支援非信號 NaN 的情況。

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```

### 模板參數

| Parameter | Description |
| --- | --- |
| T1 | First floating point type. |
| T2 | Second floating point type. |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | T1 | First floating point value. |
| rhs | T2 | Second floating point value. |

### 返回值

永遠回傳 false，因為不支援 NaN 值。

## 另請參閱

* 命名空間 [System::TestPredicates](../)
* 程式庫 [Aspose.Slides](../../)