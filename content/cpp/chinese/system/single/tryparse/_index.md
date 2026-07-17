---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 将包含数字字符串表示形式的指定字符串转换为等效的单精度浮点值。
type: docs
weight: 14
url: /zh/system/single/tryparse/
---
## Single::TryParse(const String&, float&) 方法

将包含数字字符串表示形式的指定字符串转换为等效的单精度浮点值。

```cpp
static bool System::Single::TryParse(const String &value, float &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串。 |
| result | **float**\& | 指向单精度浮点变量的引用，用于存放转换结果。 |

### 返回值

如果转换成功则返回 True，否则返回 false。

## Single::TryParse(const String&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, float&) 方法

使用提供的格式信息和数字样式，将包含数字字符串表示形式的指定字符串转换为等效的单精度浮点值。

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, float &result)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 枚举值的按位组合，指定数字字符串表示形式所允许的样式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字符串格式信息的对象的指针。 |
| result | **float**\& | 指向单精度浮点变量的引用，用于存放转换结果。 |

### 返回值

如果转换成功则返回 True，否则返回 false。

## Single::TryParse(const String&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, float&) 方法




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, float &result)
```

## Single::TryParse(const String&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, float&) 方法




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, float &result)
```

## Single::TryParse(const String&, Globalization::NumberStyles, std::nullptr_t, float&) 方法




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, float &result)
```

## 另请参见

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Single](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)