---
title: BinaryReader
second_title: Aspose.Slides for C++ API 参考
description: "表示一个读取器，以特定编码将原始数据类型作为二进制数据读取。该类的对象只能通过 System::MakeObject() 函数分配。不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言错误。始终将此类包装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 92
url: /zh/system.io/binaryreader/
---
## BinaryReader 类


表示一个读取器，以特定编码将原始数据类型作为二进制数据读取。该类的对象只能通过 [System::MakeObject()](../../system/makeobject/) 函数分配。不要在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言错误。始终将此类包装为 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class BinaryReader : public System::IDisposable
```

## 方法

| 方法 | 描述 |
| --- | --- |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | 构造一个 [BinaryReader](./) 类的实例，该实例使用 UTF-8 编码从指定的流读取数据。 |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | 构造一个 [BinaryReader](./) 类的实例，该实例使用指定的编码从指定的流读取数据。 |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&, **bool**) | 构造一个 [BinaryReader](./) 类的实例，该实例使用指定的编码从指定的流读取数据。 |
| virtual void [Close](./close/)() | 关闭当前 [BinaryReader](./) 对象及其底层输入流。 |
| void [Dispose](./dispose/)() override | 释放当前对象使用的所有资源并关闭底层流。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准 NaN 与任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准 NaN 与任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() | 返回输入流。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。用于对自定义对象进行哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 所描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。用于克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类进行拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类进行拷贝构造。 |
| virtual int [PeekChar](./peekchar/)() | 从输入流读取单个字符而不改变流的读取光标。 |
| virtual int [Read](./read/)() | 从输入流读取单个字符。 |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | 从输入流读取指定数量的字节并写入指定的字节数组。 |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | 从输入流读取指定数量的字符，将其转换为 UTF-16 编码，并将结果 UTF-16 字符写入指定字符数组的指定位置开始处。 |
| virtual **bool** [ReadBoolean](./readboolean/)() | 从输入流读取单字节并返回其布尔表示。 |
| virtual **uint8_t** [ReadByte](./readbyte/)() | 从输入流读取单个字节。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadBytes](./readbytes/)(int) | 从输入流读取指定数量的字节。 |
| virtual char_t [ReadChar](./readchar/)() | 从输入流读取单个字符。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [ReadChars](./readchars/)(int) | 从输入流读取指定数量的字符并以 UTF-16 编码返回。 |
| virtual [Decimal](../../system/decimal/) [ReadDecimal](./readdecimal/)() | 未实现。 |
| virtual **double** [ReadDouble](./readdouble/)() | 从输入流读取 8 字节并返回双精度浮点值。 |
| virtual **int16_t** [ReadInt16](./readint16/)() | 从输入流读取 2 字节并返回 16 位整数值。 |
| virtual int [ReadInt32](./readint32/)() | 从输入流读取 4 字节并返回 32 位整数值。 |
| virtual **int64_t** [ReadInt64](./readint64/)() | 从输入流读取 8 字节并返回 64 位整数值。 |
| virtual **int8_t** [ReadSByte](./readsbyte/)() | 从输入流读取单个字节并作为有符号 8 位整数返回。 |
| virtual **float** [ReadSingle](./readsingle/)() | 从输入流读取 4 字节并返回单精度浮点值。 |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | 从当前流读取字符串。字符串前缀为长度，以每次 7 位的整数编码。 |
| virtual **uint16_t** [ReadUInt16](./readuint16/)() | 从输入流读取 2 字节并返回无符号 16 位整数值。 |
| virtual **uint32_t** [ReadUInt32](./readuint32/)() | 从输入流读取 4 字节并返回无符号 32 位整数值。 |
| virtual **uint64_t** [ReadUInt64](./readuint64/)() | 从输入流读取 8 字节并返回无符号 64 位整数值。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。用于将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~BinaryReader](./~binaryreader/)() | 析构函数。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [IDisposable](../../system/idisposable/)
* 命名空间 [System::IO](../)
* 库 [Aspose.Slides](../../)