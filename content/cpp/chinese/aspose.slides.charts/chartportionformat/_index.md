---
title: ChartPortionFormat
second_title: Aspose.Slides C++ API 参考
description: 此类包含图表中使用的图表部分格式属性。不同于 IPortionFormatEffectiveData，该类的所有属性均可写。
type: docs
weight: 261
url: /zh/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat 类

此类包含用于图表的图表部分格式属性。 与 [IPortionFormatEffectiveData](../../aspose.slides/iportionformateffectivedata/) 不同，此类的所有属性都是可写的。

```cpp
class ChartPortionFormat : public Aspose::Slides::BasePortionFormat,
                           public Aspose::Slides::Charts::IChartPortionFormat
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 与指定对象进行比较。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中即使根据 IEC 60559:1989 标准 NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中即使根据 IEC 60559:1989 标准 NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../../aspose.slides/baseportionformat/get_alternativelanguageid/)() override | 返回备用语言的 Id。阅读 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_ComplexScriptFont](../../aspose.slides/baseportionformat/get_complexscriptfont/)() override | 返回复杂脚本字体信息。Null 表示字体未定义，应从母版继承。阅读 [IFontData](../../aspose.slides/ifontdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_EastAsianFont](../../aspose.slides/baseportionformat/get_eastasianfont/)() override | 返回东亚字体信息。Null 表示字体未定义，应从母版继承。阅读 [IFontData](../../aspose.slides/ifontdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/baseportionformat/get_effectformat/)() override | 返回文本 [EffectFormat](../../aspose.slides/effectformat/) 属性。未应用继承。只读 [IEffectFormat](../../aspose.slides/ieffectformat/)。 |
| **float** [get_Escapement](../../aspose.slides/baseportionformat/get_escapement/)() override | 返回上标或下标文本。值范围为 -100%（下标）到 100%（上标）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。读取 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/baseportionformat/get_fillformat/)() override | 返回文本 [FillFormat](../../aspose.slides/fillformat/) 属性。未应用继承。只读 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_FontBold](../../aspose.slides/baseportionformat/get_fontbold/)() override | 确定字体是否加粗。未应用继承。读取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| **float** [get_FontHeight](../../aspose.slides/baseportionformat/get_fontheight/)() override | 返回部分的字体高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定义，应从母版继承。读取 **float**。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_FontItalic](../../aspose.slides/baseportionformat/get_fontitalic/)() override | 确定字体是否斜体。未应用继承。读取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| [TextUnderlineType](../../aspose.slides/textunderlinetype/) [get_FontUnderline](../../aspose.slides/baseportionformat/get_fontunderline/)() override | 返回文本下划线类型。未应用继承。读取 [TextUnderlineType](../../aspose.slides/textunderlinetype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_HighlightColor](../../aspose.slides/baseportionformat/get_highlightcolor/)() override | 返回用于突出显示文本的颜色。未应用继承。只读 [IColorFormat](../../aspose.slides/icolorformat/)。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineFill](../../aspose.slides/baseportionformat/get_ishardunderlinefill/)() override | 确定下划线样式是否拥有自己的 [FillFormat](../../aspose.slides/fillformat/) 属性，或从文本的 [FillFormat](../../aspose.slides/fillformat/) 属性继承。读取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineLine](../../aspose.slides/baseportionformat/get_ishardunderlineline/)() override | 确定下划线样式是否拥有自己的 [LineFormat](../../aspose.slides/lineformat/) 属性，或从文本的 [LineFormat](../../aspose.slides/lineformat/) 属性继承。读取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| **float** [get_KerningMinimalSize](../../aspose.slides/baseportionformat/get_kerningminimalsize/)() override | 返回应开启字距调整的最小字体大小。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。读取 **float**。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Kumimoji](../../aspose.slides/baseportionformat/get_kumimoji/)() override | 确定数字是否应忽略文本东亚语言特定的垂直布局。未应用继承。读取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| [System::String](../../system/string/) [get_LanguageId](../../aspose.slides/baseportionformat/get_languageid/)() override | 返回校对语言的 Id。用于拼写和语法检查。读取 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_LatinFont](../../aspose.slides/baseportionformat/get_latinfont/)() override | 返回拉丁字体信息。Null 表示字体未定义，应从母版继承。读取 [IFontData](../../aspose.slides/ifontdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/baseportionformat/get_lineformat/)() override | 返回文本描边的 [LineFormat](../../aspose.slides/lineformat/) 属性。未应用继承。只读 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_NormaliseHeight](../../aspose.slides/baseportionformat/get_normaliseheight/)() override | 确定文本的高度是否应归一化。未应用继承。读取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | 返回 Parent_Immediate 对象。只读 [IDOMObject](../../aspose.slides/idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | 返回父级 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)。只读 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_ProofDisabled](../../aspose.slides/baseportionformat/get_proofdisabled/)() override | 确定文本是否不应进行校对。未应用继承。读取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| **float** [get_Spacing](../../aspose.slides/baseportionformat/get_spacing/)() override | 返回字符间距增量。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。读取 **float**。 |
| **bool** [get_SpellCheck](../../aspose.slides/baseportionformat/get_spellcheck/)() override | 获取一个值，指示文本部分是否启用拼写检查。当此属性设置为 false 时，文本元素的拼写检查被抑制。设置为 true 时，允许拼写检查。默认值为 **false**。 |
| [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/) [get_StrikethroughType](../../aspose.slides/baseportionformat/get_strikethroughtype/)() override | 返回文本的删除线类型。未应用继承。读取 [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_SymbolFont](../../aspose.slides/baseportionformat/get_symbolfont/)() override | 返回符号字体信息。Null 表示字体未定义，应从母版继承。读取 [IFontData](../../aspose.slides/ifontdata/)。 |
| [Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/) [get_TextCapType](../../aspose.slides/baseportionformat/get_textcaptype/)() override | 返回文本大写类型。未应用继承。读取 [Slides::TextCapType](../../aspose.slides/textcaptype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_UnderlineFillFormat](../../aspose.slides/baseportionformat/get_underlinefillformat/)() override | 返回下划线线条 [FillFormat](../../aspose.slides/fillformat/) 属性。未应用继承。只读 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_UnderlineLineFormat](../../aspose.slides/baseportionformat/get_underlinelineformat/)() override | 返回用于描边下划线线条的 [LineFormat](../../aspose.slides/lineformat/) 属性。未应用继承。只读 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | 返回哈希码。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
| [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并启用子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并启用子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 情形。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串情形。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
| void [set_AlternativeLanguageId](../../aspose.slides/baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | 设置备用语言的 Id。写入 [System::String](../../system/string/)。 |
| void [set_ComplexScriptFont](../../aspose.slides/baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | 设置复杂脚本字体信息。Null 表示字体未定义，应从母版继承。写入 [IFontData](../../aspose.slides/ifontdata/)。 |
| void [set_EastAsianFont](../../aspose.slides/baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | 设置东亚字体信息。Null 表示字体未定义，应从母版继承。写入 [IFontData](../../aspose.slides/ifontdata/)。 |
| void [set_Escapement](../../aspose.slides/baseportionformat/set_escapement/)(**float**) override | 设置上标或下标文本。值范围为 -100%（下标）到 100%（上标）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。写入 **float**。 |
| void [set_FontBold](../../aspose.slides/baseportionformat/set_fontbold/)([NullableBool](../../aspose.slides/nullablebool/)) override | 确定字体是否加粗。未应用继承。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| void [set_FontHeight](../../aspose.slides/baseportionformat/set_fontheight/)(**float**) override | 设置部分的字体高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定义，应从母版继承。写入 **float**。 |
| void [set_FontItalic](../../aspose.slides/baseportionformat/set_fontitalic/)([NullableBool](../../aspose.slides/nullablebool/)) override | 确定字体是否斜体。未应用继承。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| void [set_FontUnderline](../../aspose.slides/baseportionformat/set_fontunderline/)([TextUnderlineType](../../aspose.slides/textunderlinetype/)) override | 设置文本下划线类型。未应用继承。写入 [TextUnderlineType](../../aspose.slides/textunderlinetype/)。 |
| void [set_IsHardUnderlineFill](../../aspose.slides/baseportionformat/set_ishardunderlinefill/)([NullableBool](../../aspose.slides/nullablebool/)) override | 确定下划线样式是否拥有自己的 [FillFormat](../../aspose.slides/fillformat/) 属性，或从文本的 [FillFormat](../../aspose.slides/fillformat/) 属性继承。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| void [set_IsHardUnderlineLine](../../aspose.slides/baseportionformat/set_ishardunderlineline/)([NullableBool](../../aspose.slides/nullablebool/)) override | 确定下划线样式是否拥有自己的 [LineFormat](../../aspose.slides/lineformat/) 属性，或从文本的 [LineFormat](../../aspose.slides/lineformat/) 属性继承。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| void [set_KerningMinimalSize](../../aspose.slides/baseportionformat/set_kerningminimalsize/)(**float**) override | 设置应开启字距调整的最小字体大小。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。写入 **float**。 |
| void [set_Kumimoji](../../aspose.slides/baseportionformat/set_kumimoji/)([NullableBool](../../aspose.slides/nullablebool/)) override | 确定数字是否应忽略文本东亚语言特定的垂直布局。未应用继承。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| void [set_LanguageId](../../aspose.slides/baseportionformat/set_languageid/)([System::String](../../system/string/)) override | 设置校对语言的 Id。用于拼写和语法检查。写入 [System::String](../../system/string/)。 |
| void [set_LatinFont](../../aspose.slides/baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | 设置拉丁字体信息。Null 表示字体未定义，应从母版继承。写入 [IFontData](../../aspose.slides/ifontdata/)。 |
| void [set_NormaliseHeight](../../aspose.slides/baseportionformat/set_normaliseheight/)([NullableBool](../../aspose.slides/nullablebool/)) override | 确定文本的高度是否应归一化。未应用继承。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| void [set_ProofDisabled](../../aspose.slides/baseportionformat/set_proofdisabled/)([NullableBool](../../aspose.slides/nullablebool/)) override | 确定文本是否不应进行校对。未应用继承。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| void [set_Spacing](../../aspose.slides/baseportionformat/set_spacing/)(**float**) override | 设置字符间距增量。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。写入 **float**。 |
| void [set_SpellCheck](../../aspose.slides/baseportionformat/set_spellcheck/)(**bool**) override | 设置一个值，指示文本部分是否启用拼写检查。当此属性设置为 false 时，文本元素的拼写检查被抑制。设置为 true 时，允许拼写检查。默认值为 **false**。 |
| void [set_StrikethroughType](../../aspose.slides/baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)) override | 设置文本的删除线类型。未应用继承。写入 [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)。 |
| void [set_SymbolFont](../../aspose.slides/baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | 设置符号字体信息。Null 表示字体未定义，应从母版继承。写入 [IFontData](../../aspose.slides/ifontdata/)。 |
| void [set_TextCapType](../../aspose.slides/baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/)) override | 设置文本的大写类型。未应用继承。写入 [Slides::TextCapType](../../aspose.slides/textcaptype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 备注

此类用于返回和操作为特定部分定义的文本部分格式属性。这意味着在获取值时不应用继承，因此在大多数情况下您会得到表示“未定义”的值。

为了获取包括继承在内的有效格式参数值，您需要使用 [PortionFormat::GetEffective](../../aspose.slides/portionformat/geteffective/) 方法，该方法返回一个 [IPortionFormatEffectiveData](../../aspose.slides/iportionformateffectivedata/) 实例。

## 另见

* 类 [BasePortionFormat](../../aspose.slides/baseportionformat/)
* 类 [IChartPortionFormat](../ichartportionformat/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)