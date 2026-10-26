---
title: "System::Collections::Specialized"
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 391
url: /zh/system.collections.specialized/
---
## 类

| 类 | 描述 |
| --- | --- |
| [BitVector32](./bitvector32/) | 提供一个简单轻量的位向量，可轻松进行整数或 [Boolean](../system/boolean/) 访问，针对 32 位存储。 |
| [NameValueCollection](./namevaluecollection/) | 关联的 [String](../system/string/) 键和 [String](../system/string/) 值的集合，可通过键或索引进行访问。 |
| [StringCollection](./stringcollection/) | 字符串的索引列表。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [StringCollectionPtr](./stringcollectionptr/) | 带访问运算符的字符串集合指针。 |
| [StringDictionary](./stringdictionary/) | [String](../system/string/) 到字符串字典。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |

## 函数

| 函数 | 描述 |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)(**BitVector32::Section**, **BitVector32::Section**) | 检查两个指定对象是否相等。 |
| **bool** [operator!=](./operator_not_equal/)(**BitVector32::Section**, **BitVector32::Section**) | 检查两个指定对象是否不相等。 |