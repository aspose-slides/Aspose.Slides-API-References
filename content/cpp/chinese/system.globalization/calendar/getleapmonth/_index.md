---
title: GetLeapMonth()
second_title: Aspose.Slides C++ API 参考
description: 获取指定年份的闰月。
type: docs
weight: 274
url: /zh/system.globalization/calendar/getleapmonth/
---
## Calendar::GetLeapMonth(int) const 方法

获取指定年份的闰月。

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| year | int | 要获取闰月的年份。 |

### 返回值

指定年份的闰月，如果该年份没有闰月则返回 0。

## Calendar::GetLeapMonth(int, int) const 方法

获取指定年份的闰月。

```cpp
virtual int System::Globalization::Calendar::GetLeapMonth(int year, int era) const =0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| year | int | 要获取闰月的年份。 |
| era | int | 纪元。 |

### 返回值

指定纪元中指定年份的闰月，如果该年份没有闰月则返回 0。

## 另见

* 类 [Calendar](../)
* 命名空间 [System::Globalization](../../)
* 库 [Aspose.Slides](../../../)