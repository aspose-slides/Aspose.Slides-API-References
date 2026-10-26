---
title: operator>=()
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 2133
url: /zh-hant/system/operator_greater_equal/
---
## System::operator>=(std::nullptr_t, DateTime) 函式




```cpp
constexpr bool System::operator>=(std::nullptr_t, DateTime)
```

## System::operator>=(std::nullptr_t, const DateTimeOffset\&) 函式




```cpp
constexpr bool System::operator>=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>=(std::nullptr_t, const Nullable\<T\>\&) 函式


永遠返回 false.

```cpp
template<typename T> bool System::operator>=(std::nullptr_t, const Nullable<T> &)
```

## System::operator>=(const T1\&, const Nullable\<T2\>\&) 函式


判斷指定的值是否大於或等於由指定的 [Nullable](../nullable/) 物件所表示的值，藉由將 [operator>=()](./) 套用於這些值。

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>=(const T1 &some, const Nullable<T2> &other)
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| T1 | 第一個比較值的類型 |
| T2 | 代表第二個比較值之 [Nullable](../nullable/) 物件的底層類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| some | const T1\& | 用作第一個比較值的常量參考 |
| other | const [Nullable](../nullable/)\<T2\>\& | 用作第二個比較值的 [Nullable](../nullable/) 物件的常量參考 |

### 返回值

True 如果第一個比較值大於或等於第二個比較值，否則 - false

## System::operator>=(std::nullptr_t, TimeSpan) 函式




```cpp
constexpr bool System::operator>=(std::nullptr_t, TimeSpan)
```

## 另請參閱

* 類別 [DateTime](../datetime/)
* 類別 [DateTimeOffset](../datetimeoffset/)
* 類別 [Nullable](../nullable/)
* 類別 [TimeSpan](../timespan/)
* 結構 [IsNullable](../isnullable/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)