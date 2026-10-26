---
title: Parse()
second_title: Aspose.Slides C++ API 参考
description: 将十进制数的字符串表示转换为等价的 Decimal 类实例。
type: docs
weight: 469
url: /zh/system/decimal/parse/
---
## Decimal::Parse(const String\&) 方法

将十进制数的字符串表示转换为等价的 [Decimal](../) 类实例。

```cpp
static Decimal System::Decimal::Parse(const String &s)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 数字的字符串表示 |

### 返回值

一个新的 [Decimal](../) 类实例，表示与指定字符串所表示的值等价的值。

## Decimal::Parse(const String\&, Globalization::NumberStyles) 方法

使用指定的样式，将十进制数的字符串表示转换为等价的 [Decimal](../) 类实例。

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要转换的十进制值的字符串表示 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 一个按位组合的枚举值，提供关于 **s** 的附加信息、关于 **s** 中可能出现的样式元素，或关于从 **s** 转换为 [Decimal](../) 对象的相关信息 |

### 返回值

一个新的 [Decimal](../) 类实例，表示与指定字符串所表示的值等价的值。

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

使用指定的格式提供程序，将十进制数的字符串表示转换为等价的 [Decimal](../) 类实例。

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要转换的十进制值的字符串表示 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 格式提供程序 |

### 返回值

一个新的 [Decimal](../) 类实例，表示与指定字符串所表示的值等价的值。

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

使用指定的样式和格式提供程序，将十进制数的字符串表示转换为等价的 [Decimal](../) 类实例。

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要转换的十进制值的字符串表示 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 一个按位组合的枚举值，提供关于 **s** 的附加信息、关于 **s** 中可能出现的样式元素，或关于从 **s** 转换为 [Decimal](../) 对象的相关信息 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 格式提供程序 |

### 返回值

一个新的 [Decimal](../) 类实例，表示与指定字符串所表示的值等价的值。

## 另见

* 枚举 [NumberStyles](../../../system.globalization/numberstyles/)
* 类型别名 [SharedPtr](../../sharedptr/)
* 类 [Decimal](../)
* 类 [String](../../string/)
* 类 [IFormatProvider](../../iformatprovider/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)