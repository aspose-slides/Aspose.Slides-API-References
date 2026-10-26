---
title: CharacterRange
second_title: Aspose.Slides for C++ API 参考
description: "表示字符串中字符位置的范围。此类型应在栈上分配，并通过值或引用传递给函数。永不使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 40
url: /zh/system.drawing/characterrange/
---
## CharacterRange 类

表示字符串中字符位置的范围。此类型应在栈上分配，并通过值或引用传递给函数。永不使用 [System::SmartPtr](../../system/smartptr/) 类来管理此类型的对象。

```cpp
class CharacterRange
```

## 方法

| Method | 描述 |
| --- | --- |
|  [CharacterRange](./characterrange/)(**int32_t**, **int32_t**) | 构造一个表示指定范围的 [CharacterRange](./) 类的新实例。 |
|  [CharacterRange](./characterrange/)() | 构造一个表示空范围的 [CharacterRange](./) 类的新实例。 |
| **int32_t** [get_First](./get_first/)() const | 返回当前对象所代表的范围中第一个字符的位置。 |
| **int32_t** [get_Length](./get_length/)() const | 返回当前对象所代表的范围中的字符数。 |
| **bool** [operator!=](./operator_not_equal/)(const [CharacterRange](./)\&) const | 确定当前对象和指定对象是否表示不同的范围。 |
| **bool** [operator==](./operator_equal_equal/)(const [CharacterRange](./)\&) const | 确定当前对象和指定对象是否表示相同的范围。 |
| void [set_First](./set_first/)(**int32_t**) | 设置当前对象所代表的范围中第一个字符的位置。 |
| void [set_Length](./set_length/)(**int32_t**) | 返回当前对象所代表的范围中的字符数。 |
## 另请参见

* 命名空间 [System::Drawing](../)
* 库 [Aspose.Slides](../../)