---
title: operator<()
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 2094
url: /zh-hant/system/operator_less/
---
## System::operator<(std::nullptr_t, DateTime) 函式




```cpp
constexpr bool System::operator<(std::nullptr_t, DateTime)
```

## System::operator<(std::nullptr_t, const DateTimeOffset\&) 函式




```cpp
constexpr bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<(std::nullptr_t, const Nullable\<T\>\&) 函式


永遠傳回 false。

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## System::operator<(const T1\&, const Nullable\<T2\>\&) 函式


判斷指定的值是否小於由指定 [Nullable](../nullable/) 物件所代表的值，方法是對這些值套用 [operator<()](./)。

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
```


### 範本參數

| 參數 | 描述 |
| --- | --- |
| T1 | 第一個比較值的型別 |
| T2 | 代表第二個比較值之 [Nullable](../nullable/) 物件的基礎型別 |

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| some | const T1\& | 用作第一個比較值的常量參考 |
| other | const [Nullable](../nullable/)\<T2\>\& | 用作第二個比較值之 [Nullable](../nullable/) 物件的常量參考 |

### 傳回值

如果第一個比較值小於第二個比較值則傳回 true，否則傳回 false

## System::operator<(std::nullptr_t, TimeSpan) 函式




```cpp
constexpr bool System::operator<(std::nullptr_t, TimeSpan)
```

## 另請參閱

* 類別 [DateTime](../datetime/)
* 類別 [DateTimeOffset](../datetimeoffset/)
* 類別 [Nullable](../nullable/)
* 類別 [TimeSpan](../timespan/)
* 結構 [IsNullable](../isnullable/)
* 命名空間 [System](../)
* 程式庫 [Aspose.Slides](../../)