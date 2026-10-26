---
title: Nullable
second_title: Aspose.Slides for C++ API 參考
description: 前向宣告。
type: docs
weight: 1106
url: /zh-hant/system/nullable/
---
## 可空類別

Forward declaration.

```cpp
template<typename T>class Nullable
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 由 [Nullable](./) 類別擴充的底層值型別 |

## 方法

| 方法 | 說明 |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | 判斷目前物件所代表的值是否等於指定的 [Nullable](./) 物件所代表的值。 |
| **bool** [get_HasValue](./get_hasvalue/)() const | 判斷目前物件是否代表任何值。 |
| T [get_Value](./get_value/)() const | 傳回目前物件所代表的值的副本。 |
| int [GetHashCode](./gethashcode/)() const | 傳回目前物件的雜湊碼。 |
| T [GetValueOrDefault](./getvalueordefault/)(T) | 傳回目前物件所代表的值；如果目前物件的值為 null，則傳回指定的值。 |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | 判斷目前物件是否代表 null 值。 |
|  [Nullable](./nullable/)() | 建構一個代表 null 值的實例。 |
|  [Nullable](./nullable/)(std::nullptr_t) | 建構一個代表 null 的實例。 |
|  [Nullable](./nullable/)(const T1\&) | 建構一個 [Nullable](./) 類別的實例，該實例表示指定的值，並在必要時轉換為底層型別 T 的值。 |
|  [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | 建構一個實例，該實例代表由指定的 [Nullable](./) 物件所代表的值。指定的可空物件可能代表與建構實例的底層型別不同的型別，在此情況下，所代表的值會被轉換為 T 型別的值。 |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | 輔助函式，用於檢查此物件與 **other** 是否皆非 null，若是則呼叫 lambda。用於實作中。 |
|  [operator const T &](./operator_const_t__and/)() const | 傳回目前物件所代表的值的常量參考。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 判斷目前物件所代表的值是否非 null。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | 判斷目前物件所代表的值是否不等於指定的值。 |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | 判斷目前物件所代表的值是否不等於指定的 [Nullable](./) 物件所代表的值。 |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | 對目前物件所代表的值套用 [operator&=()](./operator_and_equal/)，使用指定的值作為右側參數。 |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | 傳回一個預設建構的 Nullable<T> 類別實例。 |
| auto [operator+](./operator_plus/)(const T1\&) const | 將可空值與非可空值相加。 |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | 將可空值相加。 |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | 重設目前物件，使其代表 null 值。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | 對目前物件所代表的值套用 [operator+=()](./operator_plus_equal/)，使用指定的值作為右側參數。 |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | 對目前物件所代表的值套用 [operator+=()](./operator_plus_equal/)，使用指定的 [Nullable](./) 物件所代表的值作為右側參數。 |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | 減去可空值與 null 指向的值。 |
| auto [operator-](./operator_minus/)(const T1\&) const | 將可空值與非可空值相減。 |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | 減去可空值。 |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | 傳回一個代表 null 值的 [Nullable](./) 類別實例。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | 對目前物件所代表的值套用 [operator-=()](./operator_minus_equal/)，使用指定的值作為右側參數。 |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | 對目前物件所代表的值套用 [operator-=()](./operator_minus_equal/)，使用指定的 [Nullable](./) 物件所代表的值作為右側參數。 |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | 永遠傳回 false。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | 透過套用 [operator<()](./operator_less/)，判斷目前物件所代表的值是否小於指定的值。 |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | 透過套用 [operator<()](./operator_less/)，判斷目前物件所代表的值是否小於指定的 [Nullable](./) 物件所代表的值。 |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | 永遠傳回 false。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | 透過套用 [operator<=()](./operator_less_equal/)，判斷目前物件所代表的值是否小於或等於指定的值。 |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | 透過套用 [operator<=()](./operator_less_equal/)，判斷目前物件所代表的值是否小於或等於指定的 [Nullable](./) 物件所代表的值。 |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | 將 null 指派給目前物件。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | 以指定的值取代物件目前所代表的值。 |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | 以指定的值取代物件目前所代表的值。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 判斷目前物件所代表的值是否為 null。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | 判斷目前物件所代表的值是否等於指定的值。 |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | 判斷目前物件所代表的值是否等於指定的 [Nullable](./) 物件所代表的值。 |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | 永遠傳回 false。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | 透過套用 [operator>()](./operator_greater/)，判斷目前物件所代表的值是否大於指定的值。 |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | 透過套用 [operator>()](./operator_greater/)，判斷目前物件所代表的值是否大於指定的 [Nullable](./) 物件所代表的值。 |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | 永遠傳回 false。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | 透過套用 [operator>=()](./operator_greater_equal/)，判斷目前物件所代表的值是否大於或等於指定物件所代表的值。 |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | 透過套用 [operator>=()](./operator_greater_equal/)，判斷目前物件所代表的值是否大於或等於指定的 [Nullable](./) 物件所代表的值。 |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | 對目前物件所代表的值套用 [operator|=()](./operator_or_equal/)，使用指定的值作為右側參數。 |
| void [reset](./reset/)() | 將目前所代表的值設為 null。 |
| void [set_Value](./set_value/)(const T\&) | 為可空物件設定新值。 |
| [String](../string/) [ToString](./tostring/)() const | 將目前物件所代表的值轉換為字串。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [ValueType](./valuetype/) | 此類別所代表的值型別的別名。 |

## 備註

表示一個可指派 null 的指定型別的值。此型別應在堆疊上分配，並以值或參考方式傳遞給函式。切勿使用 [System::SmartPtr](../smartptr/) 類別來管理此型別的物件。

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)