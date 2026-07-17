---
title: TextWriter
second_title: Aspose.Slides for C++ API 参考
description: "一个用于表示将字符序列写入不同目标的写入器类的基类。此类的对象只能使用 System::MakeObject() 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 443
url: /zh/system.io/textwriter/
---
## TextWriter 类

A base class for classes that represent writers that writes sequences of characters to different destinations. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TextWriter : public System::IDisposable
```

## 方法

| Method | Description |
| --- | --- |
| virtual void [Close](./close/)() | 关闭流并释放已获取的资源。 |
| void [Dispose](./dispose/)() override | 释放当前对象使用的所有资源并关闭底层流。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅用于内部目的。 |
| virtual void [Flush](./flush/)() | 将缓冲区内容刷新到底层流。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | 返回当前使用的编码。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | 返回当前使用的 [IFormatProvider](../../system/iformatprovider/) 对象。 |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | 返回当前使用的 [IFormatProvider](../../system/iformatprovider/) 对象。 |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | 返回行结束符字符串。 |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | 返回行结束符字符串。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上并不复制任何内容，只是初始化新对象并允许子类复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上并不复制任何内容，只是初始化新对象并允许子类复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 按引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | 设置行结束符字符串。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 结构。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 将指定对象的字符串表示写入流。 |
| virtual void [Write](./write/)(**bool**) | 将指定布尔值的字符串表示写入流。 |
| virtual void [Write](./write/)(char_t) | 将指定字符写入流。 |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | 将指定 [Decimal](../../system/decimal/) 对象的字符串表示写入流。 |
| virtual void [Write](./write/)(**double**) | 将指定双精度浮点值的字符串表示写入流。 |
| virtual void [Write](./write/)(int) | 将指定 32 位整数值的字符串表示写入流。 |
| virtual void [Write](./write/)(**int64_t**) | 将指定 64 位整数值的字符串表示写入流。 |
| virtual void [Write](./write/)(**float**) | 将指定单精度浮点值的字符串表示写入流。 |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | 将指定字符串写入流。 |
| virtual void [Write](./write/)(**uint32_t**) | 将指定无符号 32 位整数值的字符串表示写入流。 |
| virtual void [Write](./write/)(**uint64_t**) | 将指定无符号 64 位整数值的字符串表示写入流。 |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | 将指定数组中的所有字符写入流。 |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | 将指定字符数组中指定的 UTF-16 子范围写入流。 |
| virtual void [Write](./write/)(const char_t *) | 将指定的 C 字符串写入流。 |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | 将指定 [TypeInfo](../../system/typeinfo/) 对象的字符串表示写入流。 |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | 根据指定格式将指定值写入流。 |
| virtual void [WriteLine](./writeline/)() | 向流写入行结束符字符。 |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 将指定对象的字符串表示以及行结束符写入流。 |
| virtual void [WriteLine](./writeline/)(**bool**) | 将指定布尔值的字符串表示以及行结束符写入流。 |
| virtual void [WriteLine](./writeline/)(char_t) | 将指定字符以及行结束符写入流。 |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | 将指定 [Decimal](../../system/decimal/) 对象的字符串表示以及行结束符写入流。 |
| virtual void [WriteLine](./writeline/)(**double**) | 将指定双精度浮点值的字符串表示以及行结束符写入流。 |
| virtual void [WriteLine](./writeline/)(int) | 将指定 32 位整数值的字符串表示以及行结束符写入流。 |
| virtual void [WriteLine](./writeline/)(**int64_t**) | 将指定 64 位整数值的字符串表示以及行结束符写入流。 |
| virtual void [WriteLine](./writeline/)(**float**) | 将指定单精度浮点值的字符串表示以及行结束符写入流。 |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | 将指定字符串以及行结束符写入流。 |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | 将指定无符号 32 位整数值的字符串表示以及行结束符写入流。 |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | 将指定无符号 64 位整数值的字符串表示以及行结束符写入流。 |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | 将指定数组中的所有字符以及行结束符写入流。 |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | 将指定字符数组中指定的 UTF-16 子范围以及行结束符写入流。 |
| virtual void [WriteLine](./writeline/)(const char_t *) | 将指定的 C 字符串以及行结束符写入流。 |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | 将指定 [TypeInfo](../../system/typeinfo/) 对象的字符串表示以及行结束符写入流。 |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | 根据指定格式将指定值以及行结束符写入流。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
| virtual  [~TextWriter](./~textwriter/)() | 析构函数。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [Ptr](./ptr/) | 此类的共享指针别名。 |

## 另见

* 类 [IDisposable](../../system/idisposable/)
* 命名空间 [System::IO](../)
* 库 [Aspose.Slides](../../)