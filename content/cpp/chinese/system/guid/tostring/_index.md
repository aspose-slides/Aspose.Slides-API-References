---
title: ToString()
second_title: Aspose.Slides for C++ API 参考
description: 将当前对象表示的 GUID 转换为其字符串表示形式。
type: docs
weight: 79
url: /zh/system/guid/tostring/
---
## Guid::ToString() const 方法

将当前对象表示的 GUID 转换为其字符串表示形式。

```cpp
String System::Guid::ToString() const
```
## Guid::ToString(const String\&) const 方法

使用指定的字符串格式，将当前对象表示的 GUID 转换为其字符串表示形式。

```cpp
String System::Guid::ToString(const String &format) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 要使用的格式 |

### 返回值

当前对象表示的 GUID 值的字符串表示形式

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const 方法

使用指定的字符串格式和文化信息，将当前对象表示的 GUID 转换为其字符串表示形式。

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 要使用的格式 |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 要使用的文化 |

### 返回值

当前对象表示的 GUID 值的字符串表示形式

## 另请参见

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [Guid](../)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)