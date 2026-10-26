---
title: operator-()
second_title: Aspose.Slides for C++ API 參考
description: 計算兩個星期幾之間的天數。
type: docs
weight: 2172
url: /zh-hant/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) 函式

計算兩個星期天之間的天數。

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | 被減數 |
| b | [DayOfWeek](../dayofweek/) | 減數 |

### 返回值

星期 **a** 與 **b** 之間的天數；如果 *goes* 在 **** 之後，返回值為負數。

## System::operator-(const T\&, const Decimal\&) 函式

傳回一個新的 [Decimal](../decimal/) 類別實例，該實例代表從指定值中減去指定的 [Decimal](../decimal/) 物件所代表的值的結果。

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | const T\& | 要被減去的值 |
| d | const [Decimal](../decimal/)\& | 代表被減值之 [Decimal](../decimal/) 物件 |

### 返回值

一個新的 [Decimal](../decimal/) 類別實例，該實例代表從 **x** 中減去 **d** 所代表的值的結果。

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) 函式

從左側委派的回呼清單結尾斷開右側委派的所有回呼。

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | 將從其中移除回呼的委派。 |
| rhv | MulticastDelegate\<T\> | 其回呼將被移除的委派。 |

### 返回值

傳回一個委派，其中包含左側值的回呼，但不包含右側值的回呼。

## System::operator-(const T1\&, const Nullable\<T2\>\&) 函式

對非可為 null 與可為 null 的值執行減法。

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左運算元類型。 |
| T2 | 右運算元類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| some | const T1\& | 左運算元。 |
| other | const [Nullable](../nullable/)\<T2\>\& | 右運算元。 |

### 返回值

減法結果。

## 另見

* 列舉 [DayOfWeek](../dayofweek/)
* 類別 [Decimal](../decimal/)
* 類別 [Nullable](../nullable/)
* 命名空間 [System](../)
* 程式庫 [Aspose.Slides](../../)