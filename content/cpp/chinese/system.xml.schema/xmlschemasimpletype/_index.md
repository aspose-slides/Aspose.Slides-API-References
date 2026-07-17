---
title: XmlSchemaSimpleType
second_title: Aspose.Slides for C++ API 参考
description: 表示由万维网联盟 (W3C) 指定的 XML Schema 中用于简单内容的 simpleType 元素。此类定义了一个简单类型。简单类型可以为仅包含文本的属性或元素的值指定信息和约束。
type: docs
weight: 833
url: /zh/system.xml.schema/xmlschemasimpletype/
---
## XmlSchemaSimpleType 类

Represents the **simpleType** element for simple content from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class defines a simple type. Simple types can specify information and constraints for the value of attributes or elements with text-only content.

```cpp
class XmlSchemaSimpleType : public System::Xml::Schema::XmlSchemaType
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，在该比较中即使根据 IEC 60559:1989 标准 NaN 与任何值（包括 NaN）都不相等，两个 NaN 仍被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，在该比较中即使根据 IEC 60559:1989 标准 NaN 与任何值（包括 NaN）都不相等，两个 NaN 仍被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅用于内部目的。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | 返回 **annotation** 属性。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](../xmlschematype/get_baseschematype/)() | 返回后编译的对象类型或内置 XML [Schema](../) 定义语言 (XSD) 数据类型、simpleType 元素或 complexType 元素。这是后模式编译的 信息集 值。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_BaseXmlSchemaType](../xmlschematype/get_basexmlschematype/)() | 返回此模式类型的基类型的后编译值。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleTypeContent](../xmlschemasimpletypecontent/)\> [get_Content](./get_content/)() | 返回 [XmlSchemaSimpleTypeUnion](../xmlschemasimpletypeunion/)、[XmlSchemaSimpleTypeList](../xmlschemasimpletypelist/) 或 [XmlSchemaSimpleTypeRestriction](../xmlschemasimpletyperestriction/) 中的一个。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](../xmlschematype/get_datatype/)() | 返回复合类型的数据类型的后编译值。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](../xmlschematype/get_derivedby/)() | 返回此元素从其基类型派生的后编译信息。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](../xmlschematype/get_final/)() | 返回类型派生的最终属性，该属性指示是否允许进一步派生。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](../xmlschematype/get_finalresolved/)() | 返回 [XmlSchemaType::get_Final](../xmlschematype/get_final/) 值的后编译解释。 |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | 返回字符串 id。 |
| virtual **bool** [get_IsMixed](../xmlschematype/get_ismixed/)() | 返回一个指示此类型是否具有混合内容模型的值。此调用仅在复合类型中有效。 |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | 返回 **schema** 元素所引用文件中的行号。 |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | 返回 **schema** 元素所引用文件中的行位置。 |
| [String](../../system/string/) [get_Name](../xmlschematype/get_name/)() | 返回类型的名称。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | 返回用于此 schema 对象的 XmlSerializerNamespaces。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | 返回此 [XmlSchemaObject](../xmlschemaobject/) 的父对象。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](../xmlschematype/get_qualifiedname/)() | 返回从此类型的 **Name** 属性构建的类型的限定名称。这是后模式编译的值。 |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | 返回加载该 schema 的文件的源位置。 |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](../xmlschematype/get_typecode/)() | 返回类型的 XmlTypeCode。 |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | 返回不属于当前 schema 目标命名空间的限定属性。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | 返回表示指定的内置复合类型的 [XmlSchemaComplexType](../xmlschemacomplextype/)。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | 返回表示通过限定名称指定的内置复合类型的 [XmlSchemaComplexType](../xmlschemacomplextype/)。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](./)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | 返回表示通过限定名称指定的内置 simple 类型的 [XmlSchemaSimpleType](./)。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](./)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | 返回表示指定 simple 类型的内置 simple 类型的 [XmlSchemaSimpleType](./)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。支持自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| static **bool** [IsDerivedFrom](../xmlschematype/isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | 返回一个指示指定的派生 schema 类型是否来自指定的基 schema 类型的值。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支持自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并支持子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并支持子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 使用引用比较值类型对象与 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对 string 和 nullptr 情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | 设置 **annotation** 属性。 |
| void [set_Content](./set_content/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleTypeContent](../xmlschemasimpletypecontent/)\>\&) | 设置 [XmlSchemaSimpleTypeUnion](../xmlschemasimpletypeunion/)、[XmlSchemaSimpleTypeList](../xmlschemasimpletypelist/) 或 [XmlSchemaSimpleTypeRestriction](../xmlschemasimpletyperestriction/) 中的一个。 |
| void [set_Final](../xmlschematype/set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | 设置类型派生的最终属性，该属性指示是否允许进一步派生。 |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | 设置字符串 id。 |
| virtual void [set_IsMixed](../xmlschematype/set_ismixed/)(**bool**) | 设置一个指示此类型是否具有混合内容模型的值。此调用仅在复合类型中有效。 |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | 设置 **schema** 元素所引用文件中的行号。 |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | 设置 **schema** 元素所引用文件中的行位置。 |
| void [set_Name](../xmlschematype/set_name/)(const [String](../../system/string/)\&) | 设置类型的名称。 |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | 设置用于此 schema 对象的 XmlSerializerNamespaces。 |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | 设置此 [XmlSchemaObject](../xmlschemaobject/) 的父对象。 |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | 设置加载该 schema 的文件的源位置。 |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | 设置不属于当前 schema 目标命名空间的限定属性。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。支持将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | 初始化 [XmlSchemaObject](../xmlschemaobject/) 类的新实例。 |
|  [XmlSchemaSimpleType](./xmlschemasimpletype/)() | 初始化 [XmlSchemaSimpleType](./) 类的新实例。 |
|  [XmlSchemaType](../xmlschematype/xmlschematype/)() | 初始化 [XmlSchemaType](../xmlschematype/) 类的新实例。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 类型定义

| 类型别名 | 描述 |
| --- | --- |
| [Ptr](./ptr/) | 此类实例的共享指针的别名。 |

## 备注

此类的对象只能使用 [System::MakeObject()](../../system/makeobject/) 函数分配。绝不能在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

## 另见

* 类 [XmlSchemaType](../xmlschematype/)
* 命名空间 [System::Xml::Schema](../)
* 库 [Aspose.Slides](../../)