---
title: "System::StringExtra"
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 911
url: /zh/system.stringextra/
---
## 函数

| 函数 | 描述 |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | 连接字符串数组。 |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | 连接字符串。 |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | 连接字符串。 |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | 连接字符串。 |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | 将多个对象转换为字符串并连接得到的字符串。针对 [SmartPtr](../system/smartptr/) 类型的特化。 |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | 将多个对象转换为字符串并连接得到的字符串。针对算术类型的特化。 |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | 将多个对象转换为字符串并连接得到的字符串。针对结构体和其他值类型的特化。 |