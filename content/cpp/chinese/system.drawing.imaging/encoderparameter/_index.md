---
title: EncoderParameter
second_title: Aspose.Slides for C++ API 参考
description: "用作容器，将值传递给图像编码器。该类的对象应仅使用 System::MakeObject() 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装成 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 66
url: /zh/system.drawing.imaging/encoderparameter/
---
## EncoderParameter 类

作为一个容器，用于将值传递给图像编码器。此类的对象应仅使用 [System::MakeObject()](../../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class EncoderParameter : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
|  [EncoderParameter](./encoderparameter/)() | 构造 [EncoderParameter](./) 类的新实例。 |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **uint8_t**, **bool**) | 构造 [EncoderParameter](./) 类的新实例。 |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int16_t**) | 构造 [EncoderParameter](./) 类的新实例。 |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int64_t**) | 构造 [EncoderParameter](./) 类的新实例。 |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int32_t**) | 构造 [EncoderParameter](./) 类的新实例。 |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int32_t**, **int32_t**) | 构造一个表示分数的 [EncoderParameter](./) 类实例。 |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int64_t**, **int64_t**) | 构造一个表示整数值范围的 [EncoderParameter](./) 类实例。 |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int32_t**, **int32_t**, **int32_t**, **int32_t**) | 构造一个表示分数范围的 [EncoderParameter](./) 类实例。 |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [String](../../system/string/)\&) | 构造 [EncoderParameter](./) 类的新实例。 |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **bool**) | 构造一个表示值数组的 [EncoderParameter](./) 类实例。 |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int16_t**\>\&) | 构造一个表示值数组的 [EncoderParameter](./) 类实例。 |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int64_t**\>\&) | 构造一个表示值数组的 [EncoderParameter](./) 类实例。 |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&) | 构造一个表示分数数组的 [EncoderParameter](./) 类实例。 |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int64_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int64_t**\>\&) | 构造一个表示整数范围数组的 [EncoderParameter](./) 类实例。 |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&) | 构造一个表示分数范围数组的 [EncoderParameter](./) 类实例。 |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, int, [EncoderParameterValueType](../encoderparametervaluetype/), void *) | 构造一个表示从指定缓冲区读取的、指定类型的指定数量值的 [EncoderParameter](./) 类实例。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），仍将两个 NaN 视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），仍将两个 NaN 视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [EncoderPtr](../encoderptr/) [get_Encoder](./get_encoder/)() const | 返回与当前 [EncoderParameter](./) 对象关联的 [Encoder](../encoder/) 对象。 |
| int [get_NumberOfValues](./get_numberofvalues/)() const | 返回当前对象表示的值的数量。 |
| [EncoderParameterValueType](../encoderparametervaluetype/) [get_Type](./get_type/)() const | 返回当前对象表示的值的类型。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并启用子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并启用子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于 string 与 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| void [set_Encoder](./set_encoder/)(const [EncoderPtr](../encoderptr/)\&) | 将指定的 [Encoder](../encoder/) 对象与当前 [EncoderParameter](./) 对象关联。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
|  [~EncoderParameter](./~encoderparameter/)() | 析构函数。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [Object](../../system/object/)
* 命名空间 [System::Drawing::Imaging](../)
* 库 [Aspose.Slides](../../)