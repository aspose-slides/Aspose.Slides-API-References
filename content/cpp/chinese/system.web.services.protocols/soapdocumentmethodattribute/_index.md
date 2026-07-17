---
title: SoapDocumentMethodAttribute
second_title: Aspose.Slides C++ API 参考
description: "指定所有从方法传递或返回的 SOAP 消息使用 Document 格式。此类的对象只能使用 System::MakeObject() 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类包装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 53
url: /zh/system.web.services.protocols/soapdocumentmethodattribute/
---
## SoapDocumentMethodAttribute 类

指定所有从方法传递或返回的 SOAP 消息使用 Document 格式。此类的对象只能使用 [System::MakeObject()](../../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class SoapDocumentMethodAttribute : public System::Attribute
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 比较引用类型对象，采用 C# 风格。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 比较值类型对象，采用 C# 风格。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 与任何值都不相等，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 与任何值都不相等，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | 仅供内部使用。 |
| [String](../../system/string/) [get_Action](./get_action/)() | 获取 'SOAPAction' 属性的值。 |
| [String](../../system/string/) [get_Binding](./get_binding/)() | 获取 XML Web 服务方法实现的操作所对应的绑定。 |
| **bool** [get_OneWay](./get_oneway/)() | 获取指示客户端是否不等待服务器完成方法处理的值。 |
| [SoapParameterStyle](../soapparameterstyle/) [get_ParameterStyle](./get_parameterstyle/)() | 获取指示参数是否在 'Body' 元素下封装在单个 XML 元素中的值。 |
| [String](../../system/string/) [get_RequestElementName](./get_requestelementname/)() | 获取与 SOAP 请求关联的 XML 元素的名称，该元素在服务描述中定义为操作。 |
| [String](../../system/string/) [get_RequestNamespace](./get_requestnamespace/)() | 获取与 SOAP 请求关联的命名空间。 |
| [String](../../system/string/) [get_ResponseElementName](./get_responseelementname/)() | 获取与 SOAP 响应关联的 XML 元素的名称。 |
| [String](../../system/string/) [get_ResponseNamespace](./get_responsenamespace/)() | 获取与 SOAP 响应关联的命名空间。 |
| [Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/) [get_Use](./get_use/)() | 获取决定消息编码方式的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| static [Object::ptr](../../system/object/ptr/) [GetCustomAttribute](../../system/attribute/getcustomattribute/)(const [TypeInfo](../../system/typeinfo/)&, const [TypeInfo](../../system/typeinfo/)&) | 返回指定类型上应用的指定类型的自定义属性。 |
| static [ArrayPtr](../../system/arrayptr/)\<[Object::ptr](../../system/object/ptr/)\> [GetCustomAttributes](../../system/attribute/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)&) | 返回指定类型上应用的所有自定义属性。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的散列。 |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | 检查对象是否是 targetType 描述的类型的实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
| [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | 复制构造函数。实际上不复制任何内容，仅初始化新对象并允许子类的复制构造。 |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类的复制构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | 将值类型对象与 nullptr 按引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | 针对字符串和 nullptr 情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | 针对字符串情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| void [set_Action](./set_action/)([String](../../system/string/)) | 设置 'SOAPAction' 属性的值。 |
| void [set_Binding](./set_binding/)([String](../../system/string/)) | 设置 XML Web 服务方法实现的操作所对应的绑定。 |
| void [set_OneWay](./set_oneway/)(**bool**) | 设置指示客户端是否不等待服务器完成方法处理的值。 |
| void [set_ParameterStyle](./set_parameterstyle/)([SoapParameterStyle](../soapparameterstyle/)) | 设置指示参数是否在 'Body' 元素下封装在单个 XML 元素中的值。 |
| void [set_RequestElementName](./set_requestelementname/)([String](../../system/string/)) | 设置与 SOAP 请求关联的 XML 元素的名称，该元素在服务描述中定义为操作。 |
| void [set_RequestNamespace](./set_requestnamespace/)([String](../../system/string/)) | 设置与 SOAP 请求关联的命名空间。 |
| void [set_ResponseElementName](./set_responseelementname/)([String](../../system/string/)) | 设置与 SOAP 响应关联的 XML 元素的名称。 |
| void [set_ResponseNamespace](./set_responsenamespace/)([String](../../system/string/)) | 设置与 SOAP 响应关联的命名空间。 |
| void [set_Use](./set_use/)([Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/)) | 设置决定消息编码方式的值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前的共享引用计数值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)() | 构造一个新实例。 |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)([String](../../system/string/)) | 构造一个新实例。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 参见

* 类 [Attribute](../../system/attribute/)
* 命名空间 [System::Web::Services::Protocols](../)
* 库 [Aspose.Slides](../../)