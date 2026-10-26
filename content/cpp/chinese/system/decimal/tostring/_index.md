---
title: ToString()
second_title: Aspose.Slides for C++ API 参考
description: 返回由对象表示的值的字符串表示形式。
type: docs
weight: 352
url: /zh/system/decimal/tostring/
---
## Decimal::ToString() const 方法

返回由对象表示的值的字符串表示形式。

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const 方法

使用特定于文化的格式信息将当前对象转换为字符串。

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供文化特定格式信息的[IFormatProvider](../../iformatprovider/)对象。 |

### 返回值

当前对象的字符串表示形式。

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const 方法

```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const 方法

```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const 方法

```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const 方法

使用指定的字符串格式和由指定的[IFormatProvider](../../iformatprovider/)对象提供的文化特定格式信息，将当前对象转换为其字符串表示形式。

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 字符串格式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供文化特定格式信息的[IFormatProvider](../../iformatprovider/)对象。 |

### 返回值

当前对象的字符串表示形式。

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const 方法

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const 方法

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const 方法

```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## 参见

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [Decimal](../)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)