---
title: Details_EncoderFallbackException
second_title: Aspose.Slides for C++ API 参考
description: "在编码失败时，由 EncoderExceptionFallback 抛出异常。切勿手动创建此类的实例。请改用 EncoderFallbackException 类。切勿将 EncoderFallbackException 类的实例包装到 System::SmartPtr 中。"
type: docs
weight: 118
url: /zh/system.text/details_encoderfallbackexception/
---
## Details_EncoderFallbackException 类


当编码失败时，由 [EncoderExceptionFallback](../encoderexceptionfallback/) 抛出异常。切勿手动创建此类的实例。请改用 EncoderFallbackException 类。切勿将 EncoderFallbackException 类的实例包装到 [System::SmartPtr](../../system/smartptr/) 中。

```cpp
class Details_EncoderFallbackException : public System::Details_ArgumentException
```

## 方法

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点数比较，在此比较中，两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点数比较，在此比较中，两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| char_t [get_CharUnknown](./get_charunknown/)() | 获取触发错误的字符。 |
| char_t [get_CharUnknownHigh](./get_charunknownhigh/)() | 获取触发错误的字符对中的高位字符。 |
| char_t [get_CharUnknownLow](./get_charunknownlow/)() | 获取触发错误的字符对中的低位字符。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | 返回包含自定义异常数据的字典。 |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | 返回一个 32 位整数值，该值是与当前对象表示的异常关联的 HRESULT 代码。 |
| int [get_Index](./get_index/)() | 获取触发错误的字符在输入数组中的位置。 |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | 返回表示内部异常的对象的引用。 |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | 返回包含错误描述的字符串。 |
| [String](../../system/string/) [get_ParamName](../../system/details_argumentexception/get_paramname/)() |  |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | 返回包含堆栈跟踪的字符串。 |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | 返回表示最内部异常的 Exception 对象的副本。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。支持对自定义对象进行哈希。 |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_argumentexception/gettype/)() const override | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| **bool** [Is](../../system/details_argumentexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支持克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | 设置 HRESULT，即分配给特定异常的编码数值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | 返回当前对象的字符串表示。 |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_argumentexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。可直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual const char * [what](../../system/details_exception/what/)() const | 实现 [what()](../../system/details_exception/what/) 方法，该方法被 [ExceptionWrapper](../../system/exceptionwrapper/) 类调用。尽管此类未从 std::exception 继承，派生类仍可使用受保护/私有成员实现其逻辑。将此方法实现移至 [ExceptionWrapper](../../system/exceptionwrapper/) 可能会破坏该逻辑。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另见

* 类 [Details_ArgumentException](../../system/details_argumentexception/)
* 命名空间 [System::Text](../)
* 库 [Aspose.Slides](../../)