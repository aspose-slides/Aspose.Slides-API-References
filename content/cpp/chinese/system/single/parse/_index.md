---
title: Parse()
second_title: Aspose.Slides C++ API 参考
description: 将包含数字字符串表示的指定字符串转换为等价的单精度浮点值。
type: docs
weight: 1
url: /zh/system/single/parse/
---
## Single::Parse(const String\&) 方法

将包含数字字符串表示的指定字符串转换为等价的单精度浮点值。

```cpp
static float System::Single::Parse(const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串。 |

### 返回值

等于由指定字符串表示的数字的单精度浮点值。

## Single::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式信息将包含数字字符串表示的指定字符串转换为等价的单精度浮点值。

```cpp
static float System::Single::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字符串格式信息的对象指针。 |

### 返回值

等于由指定字符串表示的数字的单精度浮点值。

## Single::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, std::nullptr_t) 方法




```cpp
static float System::Single::Parse(const String &value, std::nullptr_t)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式信息和数字样式将包含数字字符串表示的指定字符串转换为等价的单精度浮点值。

```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 指定数字字符串表示的允许样式的 NumberStyles 枚举值的位掩码组合。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字符串格式信息的对象指针。 |

### 返回值

等于由指定字符串表示的数字的单精度浮点值。

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## 另请参阅

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Single](../)
* 命名空间 [System](../../)
* Library [Aspose.Slides](../../../)