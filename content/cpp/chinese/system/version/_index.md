---
title: Version
second_title: Aspose.Slides for C++ API 参考
description: "表示一个版本号。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 1444
url: /zh/system/version/
---
## Version 类


表示一个版本号。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../smartptr/) 类来管理此类型的对象。

```cpp
class Version
```

## 方法

| 方法 | 描述 |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | 比较当前对象和指定对象所表示的版本。 |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | 确定当前对象和指定对象所表示的版本号是否相等。 |
| int [get_Build](./get_build/)() const | 返回构建号。 |
| int [get_Major](./get_major/)() const | 返回主版本。 |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | 返回修订号的高 16 位值。 |
| int [get_Minor](./get_minor/)() const | 返回次版本。 |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | 返回修订号的低 16 位值。 |
| int [get_Revision](./get_revision/)() const | 返回修订号。 |
| int [GetHashCode](./gethashcode/)() const | 返回当前对象的哈希码。 |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | 将版本号的字符串表示转换为等价的 [Version](./) 类实例。 |
| [String](../string/) [ToString](./tostring/)() const | 返回当前对象所表示的版本号的字符串表示。 |
| [String](../string/) [ToString](./tostring/)(int) const | 返回当前对象所表示的版本号的指定段数的字符串表示。 |
|  [Version](./version/)(int, int, int, int) | 构造一个表示指定主版本、次版本、构建和修订值的实例。 |
|  [Version](./version/)(int, int, int) | 构造一个表示指定主版本、次版本和构建值的实例。 |
|  [Version](./version/)(int, int) | 构造一个表示指定主版本和值的实例。 |
|  [Version](./version/)(const [String](../string/)\&) | 构造一个表示为字符串的版本号的实例。 |
|  [Version](./version/)() | 构造一个表示版本号 0.0.-1.-1 的实例。 |
## 另请参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)