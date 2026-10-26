---
title: "System::Runtime::Serialization"
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 794
url: /zh/system.runtime.serialization/
---
## 类

| 类 | 描述 |
| --- | --- |
| [Details_SerializationException](./details_serializationexception/) |  |
| [FormatterConverter](./formatterconverter/) | 表示 [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/) 接口的基础实现。 |
| [IFormatterConverter](./iformatterconverter/) | 提供 [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) 实例与 formatter 提供的最适合解析 [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) 内部数据的类之间的连接。 |
| [ISerializable](./iserializable/) | 可序列化对象的接口。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [SerializationInfo](./serializationinfo/) | 保存表示序列化对象的命名字段集合。未实现。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言失败。始终将此类包装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [StreamingContext](./streamingcontext/) | 虚拟类，用于使使用 StreamingContext 的翻译类能够编译。不要通过 [SmartPtr](../system/smartptr/) 管理此类的实例，它们只能在栈上分配。 |
## 类型定义

| 类型定义 | 描述 |
| --- | --- |
| [SerializationException](./serializationexception/) |  |