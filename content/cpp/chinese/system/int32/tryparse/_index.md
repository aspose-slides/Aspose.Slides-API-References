---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 将包含数字字符串表示的指定字符串转换为等效的 32 位有符号整数。
type: docs
weight: 14
url: /zh/system/int32/tryparse/
---
## Int32::TryParse(const String\&, int32_t\&) method


将包含数字字符串表示的指定字符串转换为等效的 32 位有符号整数。

```cpp
static bool System::Int32::TryParse(const String &value, int32_t &result)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串。 |
| result | **int32_t**\& | 指向存放转换结果的 32 位有符号整数变量的引用。 |

### 返回值

如果转换成功则返回 True，否则返回 false。

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int32_t\&) method


使用提供的格式信息和数字样式，将包含数字字符串表示的指定字符串转换为等效的 32 位有符号整数。

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int32_t &result)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 枚举值的按位组合，用于指定数字字符串表示的允许样式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字符串格式信息的对象的指针。 |
| result | **int32_t**\& | 指向存放转换结果的 32 位有符号整数变量的引用。 |

### 返回值

如果转换成功则返回 True，否则返回 false。

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int32_t &result)
```

## 参见

* 枚举 [NumberStyles](../../../system.globalization/numberstyles/)
* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [Int32](../)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)