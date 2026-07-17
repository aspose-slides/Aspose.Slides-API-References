---
title: Guid
second_title: Aspose.Slides for C++ API 参考
description: "表示全局唯一标识符。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 885
url: /zh/system/guid/
---
## Guid 类


表示全局唯一标识符。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../smartptr/) 类来管理此类型的对象。

```cpp
class Guid
```

## 方法

| Method | Description |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | 对当前对象和指定对象所表示的 GUID 执行算术比较。 |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | 确定当前对象和指定对象所表示的 GUID 是否相等。 |
| int [GetHashCode](./gethashcode/)() const | 返回当前对象的哈希码。 |
|  [Guid](./guid/)() | 构造一个表示全零 GUID 的对象。 |
|  [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | 构造一个将 GUID 指定为无符号 8 位整数数组的对象。 |
|  [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | 构造一个将 GUID 指定为无符号 8 位整数数组视图的对象。 |
|  [Guid](./guid/)(const [String](../string/)\&) | 构造一个将 GUID 指定为字符串的对象。 |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | 根据指定的 GUID 组件构造 [Guid](./) 类的实例。 |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | 根据指定的 GUID 组件构造 [Guid](./) 类的实例。 |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | 根据指定的无符号整数和字节构造 [Guid](./) 类的实例。 |
|  [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | 根据指定的无符号整数和字节构造 [Guid](./) 类的实例。 |
|  [Guid](./guid/)(const [Guid](./)\&) | 构造一个表示与指定对象相同 GUID 的对象。 |
| static [Guid](./) [NewGuid](./newguid/)() | 生成一个新 GUID 并返回表示该 GUID 的 [Guid](./) 对象。 |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | 确定当前对象和指定对象所表示的 GUID 是否不相等。 |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | 将指定 [Guid](./) 对象所表示的 GUID 值赋给当前对象。 |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | 确定当前对象和指定对象所表示的 GUID 是否相等。 |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | 将指定的 GUID 字符串表示转换为等价的 [Guid](./) 对象。 |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | 将当前对象表示的 GUID 转换为字节数组。 |
| [String](../string/) [ToString](./tostring/)() const | 将当前对象表示的 GUID 转换为其字符串表示。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | 使用指定的字符串格式将当前对象表示的 GUID 转换为其字符串表示。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | 使用指定的字符串格式和区域性将当前对象表示的 GUID 转换为其字符串表示。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | 尝试将指定的字符串转换为 [Guid](./) 对象。 |
|  [~Guid](./~guid/)() | 析构函数。 |
## 字段

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | 表示值为 0 的 GUID。 |
## 另请参阅

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)