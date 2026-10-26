---
title: StringWriter
second_title: Aspose.Slides C++ API 参考
description: "实现一个将信息写入字符串的 TextWriter。此类的对象应仅使用 System::MakeObject() 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 417
url: /zh/system.io/stringwriter/
---
## StringWriter 类


实现一个 [TextWriter](../textwriter/)，用于将信息写入字符串。该类的对象应仅使用 [System::MakeObject()](../../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class StringWriter : public System::IO::TextWriter
```

## 方法

| Method | Description |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | 关闭流并释放已获取的资源。 |
| void [Dispose](../textwriter/dispose/)() override | 释放当前对象使用的所有资源并关闭底层流。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 式的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 式的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual void [Flush](../textwriter/flush/)() | 将缓冲区内容刷新到底层流。 |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | 返回当前使用的编码。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | 返回当前使用的 [IFormatProvider](../../system/iformatprovider/) 对象。 |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | 返回当前使用的 [IFormatProvider](../../system/iformatprovider/) 对象。 |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | 返回行终止符字符串。 |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | 返回行终止符字符串。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。实现自定义对象的哈希。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | 返回当前使用的 StringBuilder。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型的实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。实现自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化版本。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化版本。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | 设置行终止符字符串。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | 使用指定的 StringBuilder 和 [IFormatProvider](../../system/iformatprovider/) 构造 [StringWriter](./) 的新实例。 |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | 使用指定的 StringBuilder 和当前区域设置中的 [IFormatProvider](../../system/iformatprovider/) 构造 [StringWriter](./) 的新实例。 |
|  [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | 使用指定的 [IFormatProvider](../../system/iformatprovider/) 构造 [StringWriter](./) 的新实例。 |
|  [StringWriter](./stringwriter/)() | 使用当前区域设置中的 [IFormatProvider](../../system/iformatprovider/) 构造 [StringWriter](./) 的新实例。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 返回底层字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| void [Write](./write/)(char_t) override | 将指定字符写入流。 |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | 将指定字符数组的指定子范围写入流。 |
| void [Write](./write/)(const [String](../../system/string/)\&) override | 将指定字符串写入流。 |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 将指定对象的字符串表示写入流。 |
| virtual void [Write](../textwriter/write/)(**bool**) | 将指定布尔值的字符串表示写入流。 |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | 将指定 [Decimal](../../system/decimal/) 对象的字符串表示写入流。 |
| virtual void [Write](../textwriter/write/)(**double**) | 将指定双精度浮点值的字符串表示写入流。 |
| virtual void [Write](../textwriter/write/)(int) | 将指定 32 位整数值的字符串表示写入流。 |
| virtual void [Write](../textwriter/write/)(**int64_t**) | 将指定 64 位整数值的字符串表示写入流。 |
| virtual void [Write](../textwriter/write/)(**float**) | 将指定单精度浮点值的字符串表示写入流。 |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | 将指定无符号 32 位整数值的字符串表示写入流。 |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | 将指定无符号 64 位整数值的字符串表示写入流。 |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | 将指定数组中的所有字符写入流。 |
| virtual void [Write](../textwriter/write/)(const char_t *) | 将指定的 C 字符串写入流。 |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | 将指定 [TypeInfo](../../system/typeinfo/) 对象的字符串表示写入流。 |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | 按照指定格式将指定值写入流。 |
| virtual void [WriteLine](../textwriter/writeline/)() | 将行终止符写入流。 |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 将指定对象的字符串表示及随后行终止符写入流。 |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | 将指定布尔值的字符串表示及随后行终止符写入流。 |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | 将指定字符及随后行终止符写入流。 |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | 将指定 [Decimal](../../system/decimal/) 对象的字符串表示及随后行终止符写入流。 |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | 将指定双精度浮点值的字符串表示及随后行终止符写入流。 |
| virtual void [WriteLine](../textwriter/writeline/)(int) | 将指定 32 位整数值的字符串表示及随后行终止符写入流。 |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | 将指定 64 位整数值的字符串表示及随后行终止符写入流。 |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | 将指定单精度浮点值的字符串表示及随后行终止符写入流。 |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | 将指定字符串及随后行终止符写入流。 |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | 将指定无符号 32 位整数值的字符串表示及随后行终止符写入流。 |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | 将指定无符号 64 位整数值的字符串表示及随后行终止符写入流。 |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | 将指定数组中的所有字符及随后行终止符写入流。 |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | 将指定字符数组的指定子范围及随后行终止符写入流。 |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | 将指定的 C 字符串及随后行终止符写入流。 |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | 将指定 [TypeInfo](../../system/typeinfo/) 对象的字符串表示及随后行终止符写入流。 |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | 按照指定格式将指定值写入流并附加行终止符。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | 析构函数。 |
## 另请参见

* 类 [TextWriter](../textwriter/)
* 命名空间 [System::IO](../)
* 库 [Aspose.Slides](../../)