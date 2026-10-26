---
title: GetDateTimeFormats()
second_title: Aspose.Slides C++ API 参考
description: 返回一个字符串数组，每个元素都是使用标准日期和时间格式说明符之一对当前对象进行格式化后的字符串表示。
type: docs
weight: 547
url: /zh/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const 方法

返回一个字符串数组，每个元素都是使用标准日期和时间格式说明符之一对当前对象进行格式化后的字符串表示。

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const 方法

返回一个字符串数组，每个元素都是使用指定的标准日期和时间格式说明符对当前对象进行格式化后的字符串表示。

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | char_t | 标准日期和时间格式说明符。 |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const 方法

返回一个字符串数组，每个元素都是使用标准日期和时间格式说明符之一以及指定的格式提供程序对当前对象进行格式化后的字符串表示。

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 格式提供程序。 |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const 方法

返回一个字符串数组，每个元素都是使用指定的标准日期和时间格式说明符以及格式提供程序对当前对象进行格式化后的字符串表示。

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | char_t | 标准日期和时间格式说明符。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 格式提供程序。 |

## 另见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [DateTime](../)
* 类 [IFormatProvider](../../iformatprovider/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)