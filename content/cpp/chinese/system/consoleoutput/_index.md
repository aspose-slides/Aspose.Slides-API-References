---
title: ConsoleOutput
second_title: Aspose.Slides C++ API 参考
description: "表示标准输出流。此类的对象只能使用 System::MakeObject() 函数分配。不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 209
url: /zh/system/consoleoutput/
---
## ConsoleOutput 类

表示标准输出流。此类的对象只能使用 [System::MakeObject()](../makeobject/) 函数分配。不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | 关闭流并释放获取的资源。 |
| void [Dispose](../../system.io/textwriter/dispose/)() override | 释放当前对象使用的所有资源并关闭底层流。 |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | 使用 C# [Object.Equals](../object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual void [Flush](../../system.io/textwriter/flush/)() | 将缓冲区内容刷新到底层流。 |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | 始终返回 ASCII 编码。 |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | 返回当前使用的 [IFormatProvider](../iformatprovider/) 对象。 |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | 返回当前使用的 [IFormatProvider](../iformatprovider/) 对象。 |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | 返回行终止符字符串。 |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | 返回行终止符字符串。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../object/gettype/) 调用。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 检查对象是否是 targetType 所描述类型的实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../lockcontext/) 哨兵对象。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../object/object/)([Object](../object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) 的特化，用于字符串和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) 的特化，用于字符串的情况。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | 设置行终止符字符串。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../string/) [ToString](../object/tostring/)() const | 相当于 C# [Object.ToString()](../object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | 实现 C# typeof([System.Object](../object/)) 构造。 |
| void [Unlock](../object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [Write](./write/)(**bool**) override | 将指定 bool 值的字符串表示输出到当前对象表示的输出流。 |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | 将指定对象的字符串表示输出到当前对象表示的输出流。 |
| void [Write](./write/)(char_t) override | 将指定字符值输出到当前对象表示的输出流。 |
| void [Write](./write/)([Decimal](../decimal/)) override | 将 [Decimal](../decimal/) 值的字符串表示输出到当前对象表示的输出流。 |
| void [Write](./write/)(**double**) override | 将双精度浮点值的字符串表示输出到当前对象表示的输出流。 |
| void [Write](./write/)(**int32_t**) override | 将 32 位整数值的字符串表示输出到当前对象表示的输出流。 |
| void [Write](./write/)(**int64_t**) override | 将 64 位整数值的字符串表示输出到当前对象表示的输出流。 |
| void [Write](./write/)(**float**) override | 将单精度浮点值的字符串表示输出到当前对象表示的输出流。 |
| void [Write](./write/)(const [String](../string/)\&) override | 将指定的字符串对象输出到当前对象表示的输出流。 |
| void [Write](./write/)(**uint32_t**) override | 将无符号 32 位整数值的字符串表示输出到当前对象表示的输出流。 |
| void [Write](./write/)(**uint64_t**) override | 将无符号 64 位整数值的字符串表示输出到当前对象表示的输出流。 |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | 将指定字符数组的字符串表示输出到当前对象表示的输出流。 |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | 将指定字符数组中一段值的字符串表示输出到当前对象表示的输出流。 |
| void [Write](./write/)(const char_t *) override | 将指定的 C 字符串输出到当前对象表示的输出流。 |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | 将指定 [TypeInfo](../typeinfo/) 对象的字符串表示输出到当前对象表示的输出流。 |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | 将指定 32 位整数值的字符串表示写入流。 |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | 将指定值按照指定格式写入流。 |
| void [WriteLine](./writeline/)() override | 将当前行终止符输出到当前对象表示的输出流。 |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | 将指定对象的字符串表示以及当前行终止符输出到当前对象表示的输出流。 |
| void [WriteLine](./writeline/)(**bool**) override | 将指定 bool 值的字符串表示以及当前行终止符输出到当前对象表示的输出流。 |
| void [WriteLine](./writeline/)(char_t) override | 将指定字符值以及当前行终止符输出到当前对象表示的输出流。 |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | 将 [Decimal](../decimal/) 值的字符串表示以及当前行终止符输出到当前对象表示的输出流。 |
| void [WriteLine](./writeline/)(**double**) override | 将双精度浮点值的字符串表示以及当前行终止符输出到当前对象表示的输出流。 |
| void [WriteLine](./writeline/)(int) override | 将 32 位整数值的字符串表示以及当前行终止符输出到当前对象表示的输出流。 |
| void [WriteLine](./writeline/)(**int64_t**) override | 将 64 位整数值的字符串表示以及当前行终止符输出到当前对象表示的输出流。 |
| void [WriteLine](./writeline/)(**float**) override | 将单精度浮点值的字符串表示以及当前行终止符输出到当前对象表示的输出流。 |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | 将指定的字符串对象以及当前行终止符输出到当前对象表示的输出流。 |
| void [WriteLine](./writeline/)(**uint32_t**) override | 将无符号 32 位整数值的字符串表示以及当前行终止符输出到当前对象表示的输出流。 |
| void [WriteLine](./writeline/)(**uint64_t**) override | 将无符号 64 位整数值的字符串表示以及当前行终止符输出到当前对象表示的输出流。 |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | 将指定字符数组的字符串表示以及当前行终止符输出到当前对象表示的输出流。 |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | 将指定字符数组中一段值的字符串表示以及当前行终止符输出到当前对象表示的输出流。 |
| void [WriteLine](./writeline/)(const char_t *) override | 将指定的 C 字符串以及当前行终止符输出到当前对象表示的输出流。 |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | 将指定 [TypeInfo](../typeinfo/) 对象的字符串表示以及当前行终止符输出到当前对象表示的输出流。 |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | 将指定值按照指定格式写入流，并在后面添加行终止字符。 |
| virtual  [~Object](../object/~object/)() | 销毁对象。释放所有内部数据结构。 |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | 析构函数。 |

## 另见

* 类 [TextWriter](../../system.io/textwriter/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)