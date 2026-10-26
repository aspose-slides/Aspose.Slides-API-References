---
title: ToString()
second_title: Aspose.Slides C++ API 参考
description: 使用指定的格式和格式提供程序将当前对象转换为字符串。
type: docs
weight: 443
url: /zh/system/datetimeoffset/tostring/
---
## DateTimeOffset::ToString(const String&, const SharedPtr<IFormatProvider>&) const 方法

使用指定的格式和格式提供程序将当前对象转换为字符串。

```cpp
String System::DateTimeOffset::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | const [String](../../string/)& | 格式字符串。 |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>& | 格式提供程序。 |

### 返回值

[String](../../string/) 表示当前 [DateTimeOffset](../) 对象。

## DateTimeOffset::ToString(const SharedPtr<IFormatProvider>&) const 方法

使用指定的格式提供程序将当前对象转换为字符串。

```cpp
String System::DateTimeOffset::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>& | 格式提供程序。 |

### 返回值

[String](../../string/) 表示当前 [DateTimeOffset](../) 对象。

## DateTimeOffset::ToString(const String&) const 方法

使用指定的格式将当前对象转换为字符串。

```cpp
String System::DateTimeOffset::ToString(const String &format) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | const [String](../../string/)& | 格式字符串。 |

### 返回值

[String](../../string/) 表示当前 [DateTimeOffset](../) 对象。

## DateTimeOffset::ToString() const 方法

将当前对象转换为字符串。

```cpp
String System::DateTimeOffset::ToString() const
```

### 返回值

[String](../../string/) 表示当前 [DateTimeOffset](../) 对象。

## 另请参见

* Typedef [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [IFormatProvider](../../iformatprovider/)
* 类 [DateTimeOffset](../)
* 命名空间 [System](../../)
* Library [Aspose.Slides](../../../)