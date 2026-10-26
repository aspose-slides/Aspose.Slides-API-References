---
title: GetLeapMonth()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得指定年份的閏月。
type: docs
weight: 274
url: /zh-hant/system.globalization/calendar/getleapmonth/
---
## Calendar::GetLeapMonth(int) const 方法

取得指定年份的閏月。

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year) const
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| year | int | 要取得閏月的年份。 |

### 傳回值

指定年份的閏月，若該年份沒有閏月則返回 0。

## Calendar::GetLeapMonth(int, int) const 方法

取得指定年份的閏月。

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year, int era) const =0
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| year | int | 要取得閏月的年份。 |
| era | int | 時代。 |

### 傳回值

指定時代中指定年份的閏月，若該年份沒有閏月則返回 0。

## 另見

* 類別 [Calendar](../)
* 命名空間 [System::Globalization](../../)
* 函式庫 [Aspose.Slides](../../../)