---
title: StringWriter()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的 StringBuilder 和 IFormatProvider 构造 StringWriter 的新实例。
type: docs
weight: 1
url: /zh/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) constructor

使用指定的 StringBuilder 和 [IFormatProvider](../../../system/iformatprovider/) 构造 [StringWriter](../) 的新实例。

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | 用于正在构造的 [StringWriter](../) 的 StringBuilder 对象 |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | 用于正在构造的对象的 [IFormatProvider](../../../system/iformatprovider/) 对象 |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) constructor

使用指定的 StringBuilder 和来自当前文化的 [IFormatProvider](../../../system/iformatprovider/) 构造 [StringWriter](../) 的新实例。

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | 用于正在构造的 [StringWriter](../) 的 StringBuilder 对象 |

## StringWriter::StringWriter(const IFormatProviderPtr\&) constructor

使用指定的 [IFormatProvider](../../../system/iformatprovider/) 构造 [StringWriter](../) 的新实例。

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | 用于正在构造的对象的 [IFormatProvider](../../../system/iformatprovider/) 对象 |

## StringWriter::StringWriter() constructor

使用来自当前文化的 [IFormatProvider](../../../system/iformatprovider/) 构造 [StringWriter](../) 的新实例。

```cpp
System::IO::StringWriter::StringWriter()
```

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [IFormatProviderPtr](../../../system/iformatproviderptr/)
* 类 [StringBuilder](../../../system.text/stringbuilder/)
* 类 [StringWriter](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)