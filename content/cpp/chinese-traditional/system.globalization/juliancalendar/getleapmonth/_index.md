---
title: GetLeapMonth()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得指定年份的閏月。
type: docs
weight: 118
url: /zh-hant/system.globalization/juliancalendar/getleapmonth/
---
## JulianCalendar::GetLeapMonth(int, int) const 方法

取得指定年份的閏月。

```cpp
int System::Globalization::JulianCalendar::GetLeapMonth(int year, int era) const override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| year | int | 取得閏月的年份。 |
| era | int | 時代。 |

### 返回值

指定時代中指定年份的閏月，若該年份沒有閏月則為零。

## JulianCalendar::GetLeapMonth(int) const 方法

取得指定年份的閏月。

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| year | int | 取得閏月的年份。 |

### 返回值

指定年份的閏月，若該年份沒有閏月則為零。

## JulianCalendar::GetLeapMonth(int, int) const 方法

取得指定年份的閏月。

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year, int era) const=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| year | int | 取得閏月的年份。 |
| era | int | 時代。 |

### 返回值

指定時代中指定年份的閏月，若該年份沒有閏月則為零。

## 參見

* Class [JulianCalendar](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)