---
title: PortionFormat
second_title: Aspose.Slides C++ API 参考
description: 此类包含文本段落的格式属性。与 IPortionFormatEffectiveData 不同，此类的所有属性均可写。
type: docs
weight: 4811
url: /zh/aspose.slides/portionformat/
---
## PortionFormat 类

此类包含文本段落格式属性。与 [IPortionFormatEffectiveData](../iportionformateffectivedata/) 不同，此类的所有属性均可写。

```cpp
class PortionFormat : public Aspose::Slides::BasePortionFormat,
                      public Aspose::Slides::IPortionFormat
```

## 方法

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 与指定对象比较。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 样式比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 仿 C# 样式的浮点比较，两个 NaN 被视为相等，即使 IEC 60559:1989 规定 NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 仿 C# 样式的浮点比较，两个 NaN 被视为相等，即使 IEC 60559:1989 规定 NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../baseportionformat/get_alternativelanguageid/)() override | 返回备选语言的 Id。读取 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() override | 返回书签标识符。读取 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../baseportionformat/get_complexscriptfont/)() override | 返回复合脚本字体信息。Null 表示字体未定义，应从母版继承。读取 [IFontData](../ifontdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../baseportionformat/get_eastasianfont/)() override | 返回东亚字体信息。Null 表示字体未定义，应从母版继承。读取 [IFontData](../ifontdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../baseportionformat/get_effectformat/)() override | 返回文本 [EffectFormat](../effectformat/) 属性。未应用继承。只读 [IEffectFormat](../ieffectformat/)。 |
| **float** [get_Escapement](../baseportionformat/get_escapement/)() override | 返回上标或下标文本。值范围为 -100%（下标）到 100%（上标）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。读取 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../baseportionformat/get_fillformat/)() override | 返回文本 [FillFormat](../fillformat/) 属性。未应用继承。只读 [IFillFormat](../ifillformat/)。 |
| [NullableBool](../nullablebool/) [get_FontBold](../baseportionformat/get_fontbold/)() override | 判断字体是否加粗。未应用继承。读取 [NullableBool](../nullablebool/)。 |
| **float** [get_FontHeight](../baseportionformat/get_fontheight/)() override | 返回段落的字体高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定义，应从母版继承。读取 **float**。 |
| [NullableBool](../nullablebool/) [get_FontItalic](../baseportionformat/get_fontitalic/)() override | 判断字体是否斜体。未应用继承。读取 [NullableBool](../nullablebool/)。 |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../baseportionformat/get_fontunderline/)() override | 返回文本下划线类型。未应用继承。读取 [TextUnderlineType](../textunderlinetype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../baseportionformat/get_highlightcolor/)() override | 返回用于高亮文本的颜色。未应用继承。只读 [IColorFormat](../icolorformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | 返回鼠标点击时定义的超链接。读取 [IHyperlink](../ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | 超链接管理器。只读 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | 返回鼠标悬停时定义的超链接。读取 [IHyperlink](../ihyperlink/)。 |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../baseportionformat/get_ishardunderlinefill/)() override | 判断下划线样式是否拥有自己的 [FillFormat](../fillformat/) 属性或从文本的 [FillFormat](../fillformat/) 属性继承。读取 [NullableBool](../nullablebool/)。 |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../baseportionformat/get_ishardunderlineline/)() override | 判断下划线样式是否拥有自己的 [LineFormat](../lineformat/) 属性或从文本的 [LineFormat](../lineformat/) 属性继承。读取 [NullableBool](../nullablebool/)。 |
| **float** [get_KerningMinimalSize](../baseportionformat/get_kerningminimalsize/)() override | 返回应开启字距调整的最小字体大小。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。读取 **float**。 |
| [NullableBool](../nullablebool/) [get_Kumimoji](../baseportionformat/get_kumimoji/)() override | 判断数字是否应忽略文本特定于东部语言的垂直布局。未应用继承。读取 [NullableBool](../nullablebool/)。 |
| [System::String](../../system/string/) [get_LanguageId](../baseportionformat/get_languageid/)() override | 返回校对语言的 Id。用于拼写和语法检查。读取 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../baseportionformat/get_latinfont/)() override | 返回拉丁字体信息。Null 表示字体未定义，应从母版继承。读取 [IFontData](../ifontdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../baseportionformat/get_lineformat/)() override | 返回文本轮廓的 [LineFormat](../lineformat/) 属性。未应用继承。只读 [ILineFormat](../ilineformat/)。 |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](../baseportionformat/get_normaliseheight/)() override | 判断文本高度是否应归一化。未应用继承。读取 [NullableBool](../nullablebool/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | 返回 Parent_Immediate 对象。只读 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 返回父 [IPresentationComponent](../ipresentationcomponent/)。只读 [IPresentationComponent](../ipresentationcomponent/)。 |
| [NullableBool](../nullablebool/) [get_ProofDisabled](../baseportionformat/get_proofdisabled/)() override | 判断文本是否不应进行校对。未应用继承。读取 [NullableBool](../nullablebool/)。 |
| **bool** [get_SmartTagClean](./get_smarttagclean/)() override | 判断是否应清除智能标签。未应用继承。读取 **bool**。 |
| **float** [get_Spacing](../baseportionformat/get_spacing/)() override | 返回字符间距增量。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。读取 **float**。 |
| **bool** [get_SpellCheck](../baseportionformat/get_spellcheck/)() override | 获取指示是否为文本段落启用拼写检查的值。将此属性设为 false 时，文本元素的拼写检查将被抑制。设为 true 时，允许拼写检查。默认值为 **false**。 |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../baseportionformat/get_strikethroughtype/)() override | 返回文本的删除线类型。未应用继承。读取 [TextStrikethroughType](../textstrikethroughtype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../baseportionformat/get_symbolfont/)() override | 返回符号字体信息。Null 表示字体未定义，应从母版继承。读取 [IFontData](../ifontdata/)。 |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../baseportionformat/get_textcaptype/)() override | 返回文本大小写类型。未应用继承。读取 [Slides::TextCapType](../textcaptype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../baseportionformat/get_underlinefillformat/)() override | 返回下划线线 [FillFormat](../fillformat/) 属性。未应用继承。只读 [IFillFormat](../ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../baseportionformat/get_underlinelineformat/)() override | 返回用于轮廓下划线线的 [LineFormat](../lineformat/) 属性。未应用继承。只读 [ILineFormat](../ilineformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() override | 获取应用继承后的有效段落格式数据。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 返回哈希码。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否为目标类型的实例。相当于 C# `is` 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际并不复制任何内容，仅初始化新对象并启用子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际并不复制任何内容，仅初始化新对象并启用子类的拷贝构造。 |
|  [PortionFormat](./portionformat/)() | 初始化 [PortionFormat](./) 类的新实例。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串与 nullptr 情况下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情况下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数减少指定值。 |
| void [set_AlternativeLanguageId](../baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | 设置备选语言的 Id。写入 [System::String](../../system/string/)。 |
| void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) override | 设置书签标识符。写入 [System::String](../../system/string/)。 |
| void [set_ComplexScriptFont](../baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 设置复合脚本字体信息。Null 表示字体未定义，应从母版继承。写入 [IFontData](../ifontdata/)。 |
| void [set_EastAsianFont](../baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 设置东亚字体信息。Null 表示字体未定义，应从母版继承。写入 [IFontData](../ifontdata/)。 |
| void [set_Escapement](../baseportionformat/set_escapement/)(**float**) override | 设置上标或下标文本。值范围为 -100%（下标）到 100%（上标）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。写入 **float**。 |
| void [set_FontBold](../baseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) override | 判断字体是否加粗。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| void [set_FontHeight](../baseportionformat/set_fontheight/)(**float**) override | 设置段落的字体高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定义，应从母版继承。写入 **float**。 |
| void [set_FontItalic](../baseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) override | 判断字体是否斜体。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| void [set_FontUnderline](../baseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | 设置文本下划线类型。未应用继承。写入 [TextUnderlineType](../textunderlinetype/)。 |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 设置鼠标点击时定义的超链接。写入 [IHyperlink](../ihyperlink/)。 |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 设置鼠标悬停时定义的超链接。写入 [IHyperlink](../ihyperlink/)。 |
| void [set_IsHardUnderlineFill](../baseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | 判断下划线样式是否拥有自己的 [FillFormat](../fillformat/) 属性或从文本的 [FillFormat](../fillformat/) 属性继承。写入 [NullableBool](../nullablebool/)。 |
| void [set_IsHardUnderlineLine](../baseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | 判断下划线样式是否拥有自己的 [LineFormat](../lineformat/) 属性或从文本的 [LineFormat](../lineformat/) 属性继承。写入 [NullableBool](../nullablebool/)。 |
| void [set_KerningMinimalSize](../baseportionformat/set_kerningminimalsize/)(**float**) override | 设置应开启字距调整的最小字体大小。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。写入 **float**。 |
| void [set_Kumimoji](../baseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) override | 判断数字是否应忽略文本特定于东部语言的垂直布局。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| void [set_LanguageId](../baseportionformat/set_languageid/)([System::String](../../system/string/)) override | 设置校对语言的 Id。用于拼写和语法检查。写入 [System::String](../../system/string/)。 |
| void [set_LatinFont](../baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 设置拉丁字体信息。Null 表示字体未定义，应从母版继承。写入 [IFontData](../ifontdata/)。 |
| void [set_NormaliseHeight](../baseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) override | 判断文本高度是否应归一化。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| void [set_ProofDisabled](../baseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) override | 判断文本是否不应进行校对。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| void [set_SmartTagClean](./set_smarttagclean/)(**bool**) override | 判断是否应清除智能标签。未应用继承。写入 **bool**。 |
| void [set_Spacing](../baseportionformat/set_spacing/)(**float**) override | 设置字符间距增量。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。写入 **float**。 |
| void [set_SpellCheck](../baseportionformat/set_spellcheck/)(**bool**) override | 设置指示是否为文本段落启用拼写检查的值。将此属性设为 false 时，文本元素的拼写检查将被抑制。设为 true 时，允许拼写检查。默认值为 **false**。 |
| void [set_StrikethroughType](../baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | 设置文本的删除线类型。未应用继承。写入 [TextStrikethroughType](../textstrikethroughtype/)。 |
| void [set_SymbolFont](../baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 设置符号字体信息。Null 表示字体未定义，应从母版继承。写入 [IFontData](../ifontdata/)。 |
| void [set_TextCapType](../baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | 设置文本大小写类型。未应用继承。写入 [Slides::TextCapType](../textcaptype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
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

此类用于返回和操作为特定段落定义的文本段落格式属性。这意味着在获取值时不应用继承，因此在大多数情况下您会得到表示 “未定义” 的值。

若要获取包括继承在内的有效格式参数值，需要使用 [PortionFormat::GetEffective](./geteffective/) 方法，该方法返回一个 [IPortionFormatEffectiveData](../iportionformateffectivedata/) 实例。

以下示例展示了如何为 PowerPoint [Presentation](../presentation/) 中的 [Paragraph](../paragraph/) 段落分配拉丁字体。 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

System::SharedPtr<Paragraph> paragraph = System::MakeObject<Paragraph>();
System::SharedPtr<Portion> portion = System::MakeObject<Portion>(u"Theme text format");
paragraph->get_Portions()->Add(portion);
shape->get_TextFrame()->get_Paragraphs()->Add(paragraph);
// Aspose.Slides 使用这些特殊标识符（类似于 PowerPoint 中使用的）:
// +mn-lt - 正文字体拉丁文（次要拉丁字体）
// +mj-lt - 标题字体拉丁文（主要拉丁字体）
// +mn-ea - 正文字体东亚文字（次要东亚字体）
// +mj-ea - 正文字体东亚文字（次要东亚字体）
portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"+mn-lt"));
```

## 另见

* 类 [BasePortionFormat](../baseportionformat/)
* 类 [IPortionFormat](../iportionformat/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)