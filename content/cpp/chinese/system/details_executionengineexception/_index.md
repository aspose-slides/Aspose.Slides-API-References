---
title: Details_ExecutionEngineException
second_title: Aspose.Slides for C++ API 参考
description: ExecutionEngineException 仅出于兼容性原因而存在。
type: docs
weight: 456
url: /zh/system/details_executionengineexception/
---
## Details_ExecutionEngineException 类


ExecutionEngineException is present for compatibility reasons only.

```cpp
class Details_ExecutionEngineException : public System::Details_SystemException
```

## 方法

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | 使用 C# [Object.Equals](../object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 在 C# 风格中比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 在 C# 风格中比较值类型对象。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 样式的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准，NaN 与任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 样式的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989 标准，NaN 与任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | 返回包含自定义异常数据的字典。 |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | 返回一个 32 位整数值，该值是与当前对象表示的异常相关联的 HRESULT 代码。 |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | 返回表示内部异常的对象的引用。 |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | 返回包含错误描述的字符串。 |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | 返回包含堆栈追踪的字符串。 |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | 返回表示最内层异常的 Exception 对象的副本。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../object/gethashcode/) 方法。启用自定义对象的哈希。 |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../object/gettype/) 调用。 |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../lockcontext/) 哨兵对象。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../object/object/)([Object](../object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并支持子类的拷贝构造。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并支持子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情形的 [Object::ReferenceEquals](../object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | 针对字符串情形的 [Object::ReferenceEquals](../object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | 设置 HRESULT，这是分配给特定异常的编码数值。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | 返回当前对象的字符串表示。 |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual const char * [what](../details_exception/what/)() const | 实现 [what()](../details_exception/what/) 方法，该方法由 [ExceptionWrapper](../exceptionwrapper/) 类调用。尽管此类未从 std::exception 继承，派生类仍可使用受保护/私有成员来实现其逻辑。将此方法实现移动到 [ExceptionWrapper](../exceptionwrapper/) 可能会破坏该逻辑。 |
| virtual  [~Object](../object/~object/)() | 销毁对象。释放所有内部数据结构。 |
## 另请参阅

* 类 [Details_SystemException](../details_systemexception/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)