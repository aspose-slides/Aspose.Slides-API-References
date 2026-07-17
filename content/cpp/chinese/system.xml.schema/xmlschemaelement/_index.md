---
title: XmlSchemaElement
second_title: Aspose.Slides for C++ API 参考
description: 表示由万维网联盟 (W3C) 指定的 XML Schema 中的 element 元素。此类是所有粒子类型的基类，用于描述 XML 文档中的元素。
type: docs
weight: 365
url: /zh/system.xml.schema/xmlschemaelement/
---
## XmlSchemaElement 类


表示来自 XML [Schema](../) 的 **元素**，其规格由万维 [Web](../../system.web/) 联盟（W3C）指定。此类是所有粒子类型的基类，用于描述 XML 文档中的元素。

```cpp
class XmlSchemaElement : public System::Xml::Schema::XmlSchemaParticle
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | 返回 **annotation** 属性。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | 返回 **Block** 派生。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | 返回 **Block** 值的后期编译解释。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Constraints](./get_constraints/)() | 返回元素的约束集合。 |
| [String](../../system/string/) [get_DefaultValue](./get_defaultvalue/)() | 如果元素的内容是简单类型或元素内容为 **textOnly**，则返回元素的默认值。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_ElementSchemaType](./get_elementschematype/)() | 返回表示元素类型的 [XmlSchemaType](../xmlschematype/) 对象，基于元素的 [XmlSchemaElement::get_SchemaType](./get_schematype/) 或 [XmlSchemaElement::get_SchemaTypeName](./get_schematypename/) 值。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ElementType](./get_elementtype/)() | 返回基于元素的 [XmlSchemaElement](./) 或 [XmlSchemaElement](./) 的对象，保存 **ElementType** 值的后期编译解释。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | 返回 **Final** 值以指示不再允许进一步派生。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | 返回 **Final** 值的后期编译解释。 |
| [String](../../system/string/) [get_FixedValue](./get_fixedvalue/)() | 返回固定值。 |
| [XmlSchemaForm](../xmlschemaform/) [get_Form](./get_form/)() | 返回元素的形式。 |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | 返回字符串 id。 |
| **bool** [get_IsAbstract](./get_isabstract/)() | 返回信息以指示元素是否可以在实例文档中使用。 |
| **bool** [get_IsNillable](./get_isnillable/)() | 返回信息以指示 **xsi:nil** 是否可以出现在实例数据中。指示是否可以为元素分配显式的 nil 值。 |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | 返回 **schema** 元素所在文件的行号。 |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | 返回 **schema** 元素所在文件的列号。 |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | 返回粒子可以出现的最大次数。 |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | 返回以字符串形式表示的次数。粒子可以出现的最大次数。 |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | 返回粒子可以出现的最小次数。 |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | 返回以字符串形式表示的次数。粒子可以出现的最小次数。 |
| [String](../../system/string/) [get_Name](./get_name/)() | 返回元素的名称。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | 返回用于此模式对象的 XmlSerializerNamespaces。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | 返回此 [XmlSchemaObject](../xmlschemaobject/) 的父对象。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | 返回给定元素的实际限定名称。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | 返回在此模式（或指定命名空间指示的其他模式）中声明的元素的引用名称。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_SchemaType](./get_schematype/)() | 返回元素的类型。可以是复合类型或简单类型。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SchemaTypeName](./get_schematypename/)() | 返回此模式或指定命名空间指示的其他模式中定义的内置数据类型的名称。 |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | 返回加载模式的文件的源位置。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SubstitutionGroup](./get_substitutiongroup/)() | 返回被此元素替代的元素的名称。 |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | 返回不属于当前模式目标命名空间的限定属性。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的等价实现。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是由 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的等价实现。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际不拷贝任何内容，仅初始化新对象并启用子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际不拷贝任何内容，仅初始化新对象并启用子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串与 nullptr 情形下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情形下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定的值。 |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | 设置 **annotation** 属性。 |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | 设置 **Block** 派生。 |
| void [set_DefaultValue](./set_defaultvalue/)(const [String](../../system/string/)\&) | 设置元素的默认值（当其内容为简单类型或 **textOnly** 时）。 |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | 设置 **Final** 值以指示不再允许进一步派生。 |
| void [set_FixedValue](./set_fixedvalue/)(const [String](../../system/string/)\&) | 设置固定值。 |
| void [set_Form](./set_form/)([XmlSchemaForm](../xmlschemaform/)) | 设置元素的形式。 |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | 设置字符串 id。 |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | 设置信息以指示元素是否可以在实例文档中使用。 |
| void [set_IsNillable](./set_isnillable/)(**bool**) | 设置信息以指示 **xsi:nil** 是否可以出现在实例数据中。指示是否可以为元素分配显式的 nil 值。 |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | 设置 **schema** 元素所在文件的行号。 |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | 设置 **schema** 元素所在文件的列号。 |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | 设置粒子可以出现的最大次数。 |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | 设置以字符串形式表示的次数。粒子可以出现的最大次数。 |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | 设置粒子可以出现的最小次数。 |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | 设置以字符串形式表示的次数。粒子可以出现的最小次数。 |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | 设置元素的名称。 |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | 设置用于此模式对象的 XmlSerializerNamespaces。 |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | 设置此 [XmlSchemaObject](../xmlschemaobject/) 的父对象。 |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | 设置在此模式（或指定命名空间指示的其他模式）中声明的元素的引用名称。 |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&) | 设置元素的类型。可以是复合类型或简单类型。 |
| void [set_SchemaTypeName](./set_schematypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | 设置此模式或指定命名空间指示的其他模式中定义的内置数据类型的名称。 |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | 设置加载模式的文件的源位置。 |
| void [set_SubstitutionGroup](./set_substitutiongroup/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | 设置被此元素替代的元素的名称。 |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | 设置不属于当前模式目标命名空间的限定属性。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前共享引用计数的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 减少共享引用计数并返回其值。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的等价实现。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 减少弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
|  [XmlSchemaElement](./xmlschemaelement/)() | 初始化 [XmlSchemaElement](./) 类的新实例。 |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | 初始化 [XmlSchemaObject](../xmlschemaobject/) 类的新实例。 |
|  [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | 初始化 [XmlSchemaParticle](../xmlschemaparticle/) 类的新实例。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 类型定义

| 类型定义 | 描述 |
| --- | --- |
| [Ptr](./ptr/) | 此类实例的共享指针别名。 |

## 备注

此类的对象应仅使用 [System::MakeObject()](../../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为会导致运行时错误和/或断言故障。始终将此类包装在 [System::SmartPtr](../../system/smartptr/) 指针中，并使用该指针将其作为参数传递给函数。 

## 另请参阅

* 类 [XmlSchemaParticle](../xmlschemaparticle/)
* 命名空间 [System::Xml::Schema](../)
* 库 [Aspose.Slides](../../)