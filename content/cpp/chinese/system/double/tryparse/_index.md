---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 将包含数字字符串表示的指定字符串转换为等效的双精度浮点值。
type: docs
weight: 14
url: /zh/system/double/tryparse/
---
## Double::TryParse(const String\&, double\&) 方法


将包含数字字符串表示的指定字符串转换为等效的双精度浮点值。

```cpp
static bool System::Double::TryParse(const String &value, double &result)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串。 |
| result | **double**\& | 指向 double 精度浮点变量的引用，用于接收转换结果。 |

### 返回值

如果转换成功则返回 true，否则返回 false。

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, double\&) 方法


将包含数字字符串表示的指定字符串转换为等效的双精度浮点值，使用提供的格式信息和数字样式。

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, double &result)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 枚举值的按位组合，指定数字字符串表示的允许样式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字符串格式信息的对象的指针。 |
| result | **double**\& | 指向 double 精度浮点变量的引用，用于接收转换结果。 |

### 返回值

如果转换成功则返回 true，否则返回 false。

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, double\&) 方法




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, double\&) 方法




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, double\&) 方法




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## 另请参阅

* 枚举 [NumberStyles](../../../system.globalization/numberstyles/)
* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 结构体 [Double](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)