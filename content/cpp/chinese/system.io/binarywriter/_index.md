---
title: BinaryWriter
second_title: Aspose.Slides C++ API 参考
description: "表示一个将原始类型的值写入字节流的写入器。此类的对象只能使用 System::MakeObject() 函数分配。绝不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装到 System::SmartPtr 指针中，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 105
url: /zh/system.io/binarywriter/
---
## BinaryWriter 类

表示一个将原始类型的值写入字节流的写入器。此类的对象只能使用 [System::MakeObject()](../../system/makeobject/) 函数分配。绝不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言失败。始终将此类包装到 [System::SmartPtr](../../system/smartptr/) 指针中，并使用该指针将其作为参数传递给函数。

```cpp
class BinaryWriter : public System::IDisposable
```

## 方法

| 方法 | 描述 |
| --- | --- |
|  [BinaryWriter](./binarywriter/)(const [StreamPtr](../../system/streamptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | 构造一个 [BinaryWriter](./) 类的实例，该实例使用指定的编码将数据写入指定的流。 |
| void [Close](./close/)() | 关闭当前的 [BinaryWriter](./) 对象以及底层输出流。 |
| void [Dispose](./dispose/)() override | 释放当前对象使用的所有资源并关闭底层流。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 样式的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 样式的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| void [Flush](./flush/)() | 刷新输出流。 |
| [StreamPtr](../../system/streamptr/) [get_BaseStream](./get_basestream/)() | 返回输出流。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 对字符串和 nullptr 情形的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 对字符串情形的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| **int64_t** [Seek](./seek/)(int, [System::IO::SeekOrigin](../seekorigin/)) | 设置当前对象所代表的流的位置。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual void [Write](./write/)(**uint8_t**) | 将指定的无符号 8 位整数值写入输出流。 |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | 将指定字节数组中的指定子范围字节写入输出流。 |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | 将指定字符数组中的指定子范围 UTF-16 字符写入输出流。 |
| virtual void [Write](./write/)(**bool**) | 如果 **value** 为 true，则写入值为 0 的单字节；如果为 false，则写入值为 1 的单字节到输出流。 |
| virtual void [Write](./write/)(char16_t) | 将指定的 16 位宽字符值写入输出流。 |
| virtual void [Write](./write/)(**int16_t**) | 将指定的 16 位整数值写入输出流。 |
| virtual void [Write](./write/)(int) | 将指定的 32 位整数值写入输出流。 |
| virtual void [Write](./write/)(**int64_t**) | 将指定的 64 位整数值写入输出流。 |
| virtual void [Write](./write/)(**uint16_t**) | 将指定的无符号 16 位整数值写入输出流。 |
| virtual void [Write](./write/)(**uint32_t**) | 将指定的无符号 32 位整数值写入输出流。 |
| virtual void [Write](./write/)(**uint64_t**) | 将指定的无符号 64 位整数值写入输出流。 |
| virtual void [Write](./write/)(**float**) | 将指定的单精度浮点值写入输出流。 |
| virtual void [Write](./write/)(**double**) | 将指定的双精度浮点值写入输出流。 |
| virtual void [Write](./write/)(const [Decimal](../../system/decimal/)\&) | 将指定 [Decimal](../../system/decimal/) 值的字节表示写入输出流。 |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | 以当前编码将长度前缀字符串写入输出流。 |
| virtual void [Write](./write/)(const char_t *) | 以当前编码将长度前缀字符串写入输出流。 |
|  [~BinaryWriter](./~binarywriter/)() | 析构函数。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
## 另见

* 类 [IDisposable](../../system/idisposable/)
* 命名空间 [System::IO](../)
* 库 [Aspose.Slides](../../)