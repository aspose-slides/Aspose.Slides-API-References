---
title: Details_SoapException
second_title: Aspose.Slides C++ API 参考
description: "表示在通过 SOAP 调用方法时抛出的异常并且发生错误。不要手动创建此类的实例。请改用 SoapException 类。不要将 SoapException 类的实例包装到 System::SmartPtr 中。"
type: docs
weight: 1
url: /zh/system.web.services.protocols/details_soapexception/
---
## Details_SoapException 类

表示在通过 SOAP 调用方法时抛出的异常并且发生错误。不要手动创建此类的实例。请改用 SoapException 类。不要将 SoapException 类的实例包装到 [System::SmartPtr](../../system/smartptr/) 中。

```cpp
class Details_SoapException : public System::Details_SystemException
```

## 方法

| 方法 | 描述 |
| --- | --- |
|  [Details_SoapException](./details_soapexception/)() | 构造一个新实例。 |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | 构造一个新实例。 |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [Exception](../../system/exception/)) | 构造一个新实例。 |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/)) | 构造一个新实例。 |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [Exception](../../system/exception/)) | 构造一个新实例。 |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>) | 构造一个新实例。 |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [Exception](../../system/exception/)) | 构造一个新实例。 |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>) | 构造一个新实例。 |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>, [Exception](../../system/exception/)) | 构造一个新实例。 |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>, [Exception](../../system/exception/)) | 构造一个新实例。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C#-style 浮点数比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C#-style 浮点数比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [String](../../system/string/) [get_Actor](./get_actor/)() | 返回在使用 SOAP 版本 1.1 时抛出异常的代码片段。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_Code](./get_code/)() | 返回以 'namespace:localname' 格式的命名空间限定本地名称，用于指定 SOAP 错误代码。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | 返回包含自定义异常数据的字典。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\> [get_Detail](./get_detail/)() | 返回关于抛出异常的详细信息。 |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | 返回一个 32 位整数值，即与当前对象表示的异常相关联的 HRESULT 代码。 |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | 返回表示内部异常的对象的引用。 |
| [String](../../system/string/) [get_Lang](./get_lang/)() | 返回用于本地化异常属性的语言。 |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | 返回包含错误描述的字符串。 |
| [String](../../system/string/) [get_Node](./get_node/)() | 返回在使用 SOAP 版本 1.2 时抛出异常的代码片段。 |
| [String](../../system/string/) [get_Role](./get_role/)() | 返回抛出异常的 XML Web 服务的角色。 |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | 返回包含堆栈跟踪的字符串。 |
| [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\> [get_SubCode](./get_subcode/)() | 返回来自 'subcode' XML 元素的可选信息。 |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | 返回表示最内层异常的 Exception 对象的副本。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的散列。 |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_systemexception/gettype/)() const override | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| **bool** [Is](../../system/details_systemexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| static **bool** [IsClientFaultCode](./isclientfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | 检查指定的代码是否等于 'Client' SOAP 错误代码。 |
| static **bool** [IsMustUnderstandFaultCode](./ismustunderstandfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | 检查指定的代码是否等于 'MustUnderstand' SOAP 错误代码。 |
| static **bool** [IsServerFaultCode](./isserverfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | 检查指定的代码是否等于 'Server' SOAP 错误代码。 |
| static **bool** [IsVersionMismatchFaultCode](./isversionmismatchfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | 检查指定的代码是否等于 'VersionMismatch' SOAP 错误代码。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 使用 nullptr 对值类型对象进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | 设置 HRESULT，一个分配给特定异常的编码数值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | 返回当前对象的字符串表示。 |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_systemexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual const char * [what](../../system/details_exception/what/)() const | 实现 [what()](../../system/details_exception/what/) 方法，该方法由 [ExceptionWrapper](../../system/exceptionwrapper/) 类调用。尽管此类未从 std::exception 继承，但派生类仍可以使用受保护/私有成员实现其逻辑。将此方法实现移至 [ExceptionWrapper](../../system/exceptionwrapper/) 可能会破坏该逻辑。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 字段

| 字段 | 描述 |
| --- | --- |
| static [ClientFaultCode](./clientfaultcode/) | 表示客户端调用格式不正确或缺少必需信息的 SOAP 错误代码。 |
| static [DetailElementName](./detailelementname/) | 以 'namespace:localname' 格式的命名空间限定本地名称。 |
| static [MustUnderstandFaultCode](./mustunderstandfaultcode/) | 表示标有 'MustUnderstand' 属性的 SOAP 元素未被处理的 SOAP 错误代码。 |
| static [ServerFaultCode](./serverfaultcode/) | 表示服务器上发生错误的 SOAP 错误代码。 |
| static [VersionMismatchFaultCode](./versionmismatchfaultcode/) | 表示无效命名空间的 SOAP 错误代码。 |

## 另请参见

* 类 [Details_SystemException](../../system/details_systemexception/)
* 命名空间 [System::Web::Services::Protocols](../)
* 库 [Aspose.Slides](../../)