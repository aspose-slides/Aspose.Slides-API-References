---
title: FormatterConverter
second_title: Aspose.Slides for C++ API 参考
description: "表示 System::Runtime::Serialization::IFormatterConverter 接口的基础实现。"
type: docs
weight: 14
url: /zh/system.runtime.serialization/formatterconverter/
---
## FormatterConverter 类

表示 [System::Runtime::Serialization::IFormatterConverter](../iformatterconverter/) 接口的基本实现。

```cpp
class FormatterConverter : public System::Runtime::Serialization::IFormatterConverter
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Convert](./convert/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, const [TypeInfo](../../system/typeinfo/)\&) override | 将值转换为给定的 [System::TypeInfo](../../system/typeinfo/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Convert](./convert/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [TypeCode](../../system/typecode/)) override | 将值转换为给定的 [System::TypeCode](../../system/typecode/)。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 所描述类型的实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于 string 和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于 strings 的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| **bool** [ToBoolean](./toboolean/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 将值转换为 bool。 |
| **uint8_t** [ToByte](./tobyte/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 将值转换为 **uint8_t**。 |
| char16_t [ToChar](./tochar/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 将值转换为 char16_t。 |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 将值转换为 [DateTime](../../system/datetime/)。 |
| [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 将值转换为 [Decimal](../../system/decimal/)。 |
| **double** [ToDouble](./todouble/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 将值转换为 double。 |
| **int16_t** [ToInt16](./toint16/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 将值转换为 **int16_t**。 |
| **int32_t** [ToInt32](./toint32/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 将值转换为 **int32_t**。 |
| **int64_t** [ToInt64](./toint64/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 将值转换为 **int64_t**。 |
| **int8_t** [ToSByte](./tosbyte/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 将值转换为 **int8_t**。 |
| **float** [ToSingle](./tosingle/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 将值转换为 float。 |
| [String](../../system/string/) [ToString](./tostring/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 将值转换为 [String](../../system/string/)。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| **uint16_t** [ToUInt16](./touint16/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 将值转换为 **uint16_t**。 |
| **uint32_t** [ToUInt32](./touint32/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 将值转换为 **uint32_t**。 |
| **uint64_t** [ToUInt64](./touint64/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 将值转换为 **uint64_t**。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [IFormatterConverter](../iformatterconverter/)
* 命名空间 [System::Runtime::Serialization](../)
* 库 [Aspose.Slides](../../)