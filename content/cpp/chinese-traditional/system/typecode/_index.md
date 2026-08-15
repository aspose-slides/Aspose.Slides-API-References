---
title: TypeCode
second_title: Aspose.Slides for C++ API 參考
description: 表示物件的類型。
type: docs
weight: 3225
url: /zh-hant/system/typecode/
---
## TypeCode enum

表示物件的類型。

```cpp
enum class TypeCode
```

### 值

| Name | Value | Description |
| --- | --- | --- |
| Empty | 0 | 空參考。 |
| Object | 1 | 一種通用類型，表示任何未被其他 TypeCode 明確表示的參考型別或值型別。 |
| DBNull | 2 | 資料庫的 null (欄位) 值。 |
| Boolean | 3 | 一種簡單型別，表示 true 或 false 的 [Boolean](../boolean/) 值。 |
| Char | 4 | 一種整數型別，表示介於 0 與 65535 之間的 unsigned 16 位元整數。 |
| SByte | 5 | 一種整數型別，表示介於 -128 與 127 之間的 signed 8 位元整數。 |
| Byte | 6 | 一種整數型別，表示介於 0 與 255 之間的 unsigned 8 位元整數。 |
| Int16 | 7 | 一種整數型別，表示介於 -32768 與 32767 之間的 signed 16 位元整數。 |
| UInt16 | 8 | 一種整數型別，表示介於 0 與 65535 之間的 unsigned 16 位元整數。 |
| Int32 | 9 | 一種整數型別，表示介於 -2147483648 與 2147483647 之間的 signed 32 位元整數。 |
| UInt32 | 10 | 一種整數型別，表示介於 0 與 4294967295 之間的 unsigned 32 位元整數。 |
| Int64 | 11 | 一種整數型別，表示介於 -9223372036854775808 與 9223372036854775807 之間的 signed 64 位元整數。 |
| UInt64 | 12 | 一種整數型別，表示介於 0 與 18446744073709551615 之間的 unsigned 64 位元整數。 |
| Single | 13 | 一種浮點型別，表示值的範圍約為 1.5 x 10 -45 至 3.4 x 10 38，精度為 7 位數。 |
| Double | 14 | 一種浮點型別，表示值的範圍約為 5.0 x 10 -324 至 1.7 x 10 308，精度為 15-16 位數。 |
| Decimal | 15 | 一種簡單型別，表示值的範圍從 1.0 x 10 -28 到約 7.9 x 10 28，具備 28-29 位有效數字。 |
| DateTime | 16 | 表示日期和時間值的型別。 |
| String | 18 | 一種密封類別型別，表示 Unicode 字元字串。 |

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)