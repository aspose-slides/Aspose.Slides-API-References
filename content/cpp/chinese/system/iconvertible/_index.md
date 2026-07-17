---
title: IConvertible
second_title: Aspose.Slides for C++ API 参考
description: "定义将实现的引用或值类型的值转换为具有等价值的公共语言运行时类型的方法。此类的对象应仅使用 System::MakeObject() 函数进行分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装在 System::SmartPtr 指针中，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 937
url: /zh/system/iconvertible/
---
## IConvertible 类

定义将实现的引用或值类型的值转换为具有等价值的公共语言运行时类型的方法。此类的对象应仅通过 [System::MakeObject()](../makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装在 [System::SmartPtr](../smartptr/) 指针中，并使用该指针将其作为参数传递给函数。

```cpp
class IConvertible : public virtual System::Object
```

## 方法

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | 使用 C# [Object.Equals](../object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 在 C# 样式中比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 在 C# 样式中比较值类型对象。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../object/gethashcode/) 方法。启用自定义对象的散列。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../object/gettype/) 调用。 |
| virtual [System::TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() | 返回此实例的类型代码。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 检查对象是否表示由 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../object/lock/)() | 实现 C# lock() 语句的加锁。可直接调用或使用 [LockContext](../lockcontext/) 哨兵对象。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../object/object/)([Object](../object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 的 [Object::ReferenceEquals](../object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | 针对字符串的 [Object::ReferenceEquals](../object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 将共享引用计数降低指定的值。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual **bool** [ToBoolean](./toboolean/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的区域特定格式信息，将此实例的值转换为等效的 [Boolean](../boolean/) 值。 |
| virtual **uint8_t** [ToByte](./tobyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的区域特定格式信息，将此实例的值转换为等效的 8 位 uint32_teger。 |
| virtual char_t [ToChar](./tochar/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的区域特定格式信息，将此实例的值转换为等效的 Unicode 字符。 |
| virtual [System::DateTime](../datetime/) [ToDateTime](./todatetime/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的区域特定格式信息，将此实例的值转换为等效的 [System::DateTime](../datetime/)。 |
| virtual [System::Decimal](../decimal/) [ToDecimal](./todecimal/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的区域特定格式信息，将此实例的值转换为等效的 [System::Decimal](../decimal/) 数字。 |
| virtual **double** [ToDouble](./todouble/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的区域特定格式信息，将此实例的值转换为等效的双精度浮点数。 |
| virtual **int16_t** [ToInt16](./toint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的区域特定格式信息，将此实例的值转换为等效的 16 位有符号整数。 |
| virtual **int32_t** [ToInt32](./toint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的区域特定格式信息，将此实例的值转换为等效的 32 位有符号整数。 |
| virtual **int64_t** [ToInt64](./toint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的区域特定格式信息，将此实例的值转换为等效的 64 位有符号整数。 |
| virtual **int8_t** [ToSByte](./tosbyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的区域特定格式信息，将此实例的值转换为等效的 8 位有符号整数。 |
| virtual **float** [ToSingle](./tosingle/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的区域特定格式信息，将此实例的值转换为等效的单精度浮点数。 |
| virtual [System::String](../string/) [ToString](./tostring/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的区域特定格式信息，将此实例的值转换为等效的 [System::String](../string/)。 |
| virtual [String](../string/) [ToString](./tostring/)() const | 相当于 C# [Object.ToString()](../object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| virtual [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\> [ToType](./totype/)(const [TypeInfo](../typeinfo/)\&, [System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的区域特定格式信息，将此实例的值转换为指定 System::Type 的等效 [System::Object](../object/)。 |
| virtual **uint16_t** [ToUInt16](./touint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的区域特定格式信息，将此实例的值转换为等效的 16 位 uint32_teger。 |
| virtual **uint32_t** [ToUInt32](./touint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的区域特定格式信息，将此实例的值转换为等效的 32 位 uint32_teger。 |
| virtual **uint64_t** [ToUInt64](./touint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | 使用指定的区域特定格式信息，将此实例的值转换为等效的 64 位 uint32_teger。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | 实现 C# typeof([System.Object](../object/)) 构造。 |
| void [Unlock](../object/unlock/)() | 实现 C# lock() 语句的解锁。可直接调用或使用 [LockContext](../lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [Object](../object/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)