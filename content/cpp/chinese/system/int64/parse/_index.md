---
title: Parse()
second_title: Aspose.Slides for C++ API 参考
description: 将包含数字字符串表示的指定字符串转换为等效的 64 位有符号整数。
type: docs
weight: 1
url: /zh/system/int64/parse/
---
## Int64::Parse(const String\&) 方法

将包含数字字符串表示的指定字符串转换为等效的 64 位有符号整数。

```cpp
static int64_t System::Int64::Parse(const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串。 |

### 返回值

等于指定字符串所表示数字的 64 位有符号整数。

## Int64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式信息将包含数字字符串表示的指定字符串转换为等效的 64 位有符号整数。

```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字符串格式信息的对象的指针。 |

### 返回值

等于指定字符串所表示数字的 64 位有符号整数。

## Int64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法

```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, std::nullptr_t) 方法

```cpp
static int64_t System::Int64::Parse(const String &value, std::nullptr_t)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 方法

使用提供的格式信息和数字样式将包含数字字符串表示的指定字符串转换为等效的 64 位有符号整数。

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 枚举值的按位组合，指定数字字符串表示的允许样式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字符串格式信息的对象的指针。 |

### 返回值

等于指定字符串所表示数字的 64 位有符号整数。

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 方法

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) 方法

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## 另请参见

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int64](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)