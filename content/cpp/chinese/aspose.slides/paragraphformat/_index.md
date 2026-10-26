---
title: ParagraphFormat
second_title: Aspose.Slides C++ API 参考
description: 此类包含段落格式属性。不同于 IParagraphFormatEffectiveData，此类的所有属性都是可写的。
type: docs
weight: 4668
url: /zh/aspose.slides/paragraphformat/
---
## ParagraphFormat 类


此类包含段落格式属性。不同于 [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)，此类的所有属性都是可写的。

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 与指定对象比较。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 样式比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，即两个 NaN 被视为相等，尽管 IEC 60559:1989 中 NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，即两个 NaN 被视为相等，尽管 IEC 60559:1989 中 NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | 返回段落中无继承的文本对齐方式。读取 [TextAlignment](../textalignment/)。 |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | 返回无继承的默认制表位大小。读取 **float**。 |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | 确定段落中是否使用东亚换行。未应用继承。读取 [NullableBool](../nullablebool/)。 |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | 返回段落中无继承的字体对齐方式。读取 [Slides::FontAlignment](../fontalignment/)。 |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | 确定段落中是否使用悬挂标点。未应用继承。读取 [NullableBool](../nullablebool/)。 |
| **float** [get_Indent](./get_indent/)() override | 返回段落中无继承的首行缩进/悬挂缩进。悬挂缩进可使用负值定义。读取 **float**。 |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | 确定段落中是否使用拉丁换行。未应用继承。读取 [NullableBool](../nullablebool/)。 |
| **float** [get_MarginLeft](./get_marginleft/)() override | 返回段落中无继承的左边距。读取 **float**。 |
| **float** [get_MarginRight](./get_marginright/)() override | 返回段落中无继承的右边距。读取 **float**。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | 返回 Parent_Immediate 对象。只读 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 返回父级 [IPresentationComponent](../ipresentationcomponent/)。只读 [IPresentationComponent](../ipresentationcomponent/)。 |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | 确定段落中是否使用从右到左书写。未应用继承。读取 [NullableBool](../nullablebool/)。 |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | 返回段落中无继承的最后一行之后的间距。正值表示以字体大小的百分比指定空白，负值以点大小指定空白。读取 **float**。 |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | 返回段落中无继承的第一行之前的间距。正值表示以字体大小的百分比指定空白，负值以点大小指定空白。读取 **float**。 |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | 返回段落中基线之间的间距。正值表示百分比，负值表示点大小。未应用继承。读取 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | 返回指定索引处段落的制表位。未应用继承。只读 [Aspose::Slides::ITab](../itab/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | 返回段落的所有制表位。未应用继承。只读 [ITabCollection](../itabcollection/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | 获取应用继承后的有效段落格式数据。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 返回哈希码。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是目标类型的实例。相当于 C# `is` 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不拷贝任何内容，仅初始化新对象并允许子类拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不拷贝任何内容，仅初始化新对象并允许子类拷贝构造。 |
|  [ParagraphFormat](./paragraphformat/)() | 初始化 [ParagraphFormat](./) 类的新实例。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串与 nullptr 情形下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情形下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值降低共享引用计数。 |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | 设置段落中无继承的文本对齐方式。写入 [TextAlignment](../textalignment/)。 |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | 设置无继承的默认制表位大小。写入 **float**。 |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | 确定段落中是否使用东亚换行。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | 设置段落中无继承的字体对齐方式。写入 [Slides::FontAlignment](../fontalignment/)。 |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | 确定段落中是否使用悬挂标点。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| void [set_Indent](./set_indent/)(**float**) override | 设置段落中无继承的首行缩进/悬挂缩进。悬挂缩进可使用负值定义。写入 **float**。 |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | 确定段落中是否使用拉丁换行。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | 设置段落中无继承的左边距。写入 **float**。 |
| void [set_MarginRight](./set_marginright/)(**float**) override | 设置段落中无继承的右边距。写入 **float**。 |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | 确定段落中是否使用从右到左书写。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | 设置段落中无继承的最后一行之后的间距。正值表示以字体大小的百分比指定空白，负值以点大小指定空白。写入 **float**。 |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | 设置段落中无继承的第一行之前的间距。正值表示以字体大小的百分比指定空白，负值以点大小指定空白。写入 **float**。 |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | 设置段落中基线之间的间距。正值表示百分比，负值表示点大小。未应用继承。写入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前的共享引用计数值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 减少并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 减少弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
## 备注


此类用于返回和操作为特定段落定义的段落格式属性。这意味着在获取值时不应用继承，因此在大多数情况下您将获得表示“未定义”的值。

为了获取包括继承在内的有效格式参数值，您需要使用 [ParagraphFormat::GetEffective](./geteffective/) 方法，该方法返回一个 [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) 实例。
## 参见

* 类 [PVIObject](../pviobject/)
* 类 [IParagraphFormat](../iparagraphformat/)
* 类 [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)