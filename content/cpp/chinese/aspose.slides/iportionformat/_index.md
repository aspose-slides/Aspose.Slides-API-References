---
title: IPortionFormat
second_title: Aspose.Slides for C++ API 参考
description: 此类包含文本部分的格式属性。与 IPortionFormatEffectiveData 不同，此类的所有属性都是可写的。
type: docs
weight: 3329
url: /zh/aspose.slides/iportionformat/
---
## IPortionFormat class


此类包含文本部分的格式属性。与 [IPortionFormatEffectiveData](../iportionformateffectivedata/) 不同，此类的所有属性都是可写的。

```cpp
class IPortionFormat : public virtual Aspose::Slides::IBasePortionFormat,
                       public Aspose::Slides::IHyperlinkContainer
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformat/get_alternativelanguageid/)() | 返回替代语言的 Id。阅读 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | 返回书签标识符。阅读 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformat/get_complexscriptfont/)() | 返回复杂脚本字体信息。Null 表示字体未定义，应从母版继承。阅读 [IFontData](../ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformat/get_eastasianfont/)() | 返回东亚字体信息。Null 表示字体未定义，应从母版继承。阅读 [IFontData](../ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ibaseportionformat/get_effectformat/)() | 返回文本 [EffectFormat](../effectformat/) 属性。未应用继承。只读 [IEffectFormat](../ieffectformat/)。 |
| virtual **float** [get_Escapement](../ibaseportionformat/get_escapement/)() | 返回上标或下标文本。取值范围为 -100%（下标）到 100%（上标）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。读取 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ibaseportionformat/get_fillformat/)() | 返回文本 [FillFormat](../fillformat/) 属性。未应用继承。只读 [IFillFormat](../ifillformat/)。 |
| virtual [NullableBool](../nullablebool/) [get_FontBold](../ibaseportionformat/get_fontbold/)() | 确定字体是否为粗体。未应用继承。读取 [NullableBool](../nullablebool/)。 |
| virtual **float** [get_FontHeight](../ibaseportionformat/get_fontheight/)() | 返回部分的字体高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定义，应从母版继承。读取 **float**。 |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](../ibaseportionformat/get_fontitalic/)() | 确定字体是否为斜体。未应用继承。读取 [NullableBool](../nullablebool/)。 |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformat/get_fontunderline/)() | 返回文本下划线类型。未应用继承。读取 [TextUnderlineType](../textunderlinetype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../ibaseportionformat/get_highlightcolor/)() | 返回用于突出显示文本的颜色。未应用继承。只读 [IColorFormat](../icolorformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | 返回鼠标点击时定义的超链接。阅读 [IHyperlink](../ihyperlink/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | 超链接管理器 只读 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | 返回鼠标悬停时定义的超链接。阅读 [IHyperlink](../ihyperlink/)。 |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../ibaseportionformat/get_ishardunderlinefill/)() | 确定下划线样式是否拥有自己的 [FillFormat](../fillformat/) 属性，或从文本的 [FillFormat](../fillformat/) 属性继承。读取 [NullableBool](../nullablebool/)。 |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../ibaseportionformat/get_ishardunderlineline/)() | 确定下划线样式是否拥有自己的 [LineFormat](../lineformat/) 属性，或从文本的 [LineFormat](../lineformat/) 属性继承。读取 [NullableBool](../nullablebool/)。 |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformat/get_kerningminimalsize/)() | 返回应开启字距调整的最小字体大小。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。读取 **float**。 |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](../ibaseportionformat/get_kumimoji/)() | 确定数字是否应忽略文本特定东部语言的垂直布局。未应用继承。读取 [NullableBool](../nullablebool/)。 |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformat/get_languageid/)() | 返回校对语言的 Id。用于拼写和语法检查。阅读 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformat/get_latinfont/)() | 返回拉丁字体信息。Null 表示字体未定义，应从母版继承。阅读 [IFontData](../ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ibaseportionformat/get_lineformat/)() | 返回文本轮廓的 [LineFormat](../lineformat/) 属性。未应用继承。只读 [ILineFormat](../ilineformat/)。 |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](../ibaseportionformat/get_normaliseheight/)() | 确定文本高度是否应标准化。未应用继承。读取 [NullableBool](../nullablebool/)。 |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](../ibaseportionformat/get_proofdisabled/)() | 确定文本是否不应进行校对。未应用继承。读取 [NullableBool](../nullablebool/)。 |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | 确定智能标签是否应被清除。未应用继承。读取 **bool**。 |
| virtual **float** [get_Spacing](../ibaseportionformat/get_spacing/)() | 返回字符间距增量。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。读取 **float**。 |
| virtual **bool** [get_SpellCheck](../ibaseportionformat/get_spellcheck/)() | 获取一个值，指示是否为文本部分启用拼写检查。当此属性设为 false 时，文本元素的拼写检查被抑制。设为 true 时，允许拼写检查。默认值为 **false**。 |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformat/get_strikethroughtype/)() | 返回文本的删除线类型。未应用继承。读取 [TextStrikethroughType](../textstrikethroughtype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformat/get_symbolfont/)() | 返回符号字体信息。Null 表示字体未定义，应从母版继承。阅读 [IFontData](../ifontdata/)。 |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformat/get_textcaptype/)() | 返回文本大小写类型。未应用继承。读取 [Slides::TextCapType](../textcaptype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../ibaseportionformat/get_underlinefillformat/)() | 返回下划线线条 [FillFormat](../fillformat/) 属性。未应用继承。只读 [IFillFormat](../ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../ibaseportionformat/get_underlinelineformat/)() | 返回用于描绘下划线线条的 [LineFormat](../lineformat/) 属性。未应用继承。只读 [ILineFormat](../ilineformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() | 获取应用继承后的有效部分格式化数据。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示由 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许拷贝构造子类。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许拷贝构造子类。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 专化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 专化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_AlternativeLanguageId](../ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | 设置替代语言的 Id。写入 [System::String](../../system/string/)。 |
| virtual void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) | 设置书签标识符。写入 [System::String](../../system/string/)。 |
| virtual void [set_ComplexScriptFont](../ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 设置复杂脚本字体信息。Null 表示字体未定义，应从母版继承。写入 [IFontData](../ifontdata/)。 |
| virtual void [set_EastAsianFont](../ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 设置东亚字体信息。Null 表示字体未定义，应从母版继承。写入 [IFontData](../ifontdata/)。 |
| virtual void [set_Escapement](../ibaseportionformat/set_escapement/)(**float**) | 设置上标或下标文本。取值范围为 -100%（下标）到 100%（上标）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。写入 **float**。 |
| virtual void [set_FontBold](../ibaseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) | 确定字体是否为粗体。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| virtual void [set_FontHeight](../ibaseportionformat/set_fontheight/)(**float**) | 设置部分的字体高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定义，应从母版继承。写入 **float**。 |
| virtual void [set_FontItalic](../ibaseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) | 确定字体是否为斜体。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| virtual void [set_FontUnderline](../ibaseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | 设置文本下划线类型。未应用继承。写入 [TextUnderlineType](../textunderlinetype/)。 |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | 设置鼠标点击时定义的超链接。写入 [IHyperlink](../ihyperlink/)。 |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | 设置鼠标悬停时定义的超链接。写入 [IHyperlink](../ihyperlink/)。 |
| virtual void [set_IsHardUnderlineFill](../ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | 确定下划线样式是否拥有自己的 [FillFormat](../fillformat/) 属性，或从文本的 [FillFormat](../fillformat/) 属性继承。写入 [NullableBool](../nullablebool/)。 |
| virtual void [set_IsHardUnderlineLine](../ibaseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) | 确定下划线样式是否拥有自己的 [LineFormat](../lineformat/) 属性，或从文本的 [LineFormat](../lineformat/) 属性继承。写入 [NullableBool](../nullablebool/)。 |
| virtual void [set_KerningMinimalSize](../ibaseportionformat/set_kerningminimalsize/)(**float**) | 设置应开启字距调整的最小字体大小。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。写入 **float**。 |
| virtual void [set_Kumimoji](../ibaseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) | 确定数字是否应忽略文本特定东部语言的垂直布局。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| virtual void [set_LanguageId](../ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | 设置校对语言的 Id。用于拼写和语法检查。写入 [System::String](../../system/string/)。 |
| virtual void [set_LatinFont](../ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 设置拉丁字体信息。Null 表示字体未定义，应从母版继承。写入 [IFontData](../ifontdata/)。 |
| virtual void [set_NormaliseHeight](../ibaseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) | 确定文本高度是否应标准化。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| virtual void [set_ProofDisabled](../ibaseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) | 确定文本是否不应进行校对。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| virtual void [set_SmartTagClean](./set_smarttagclean/)(**bool**) | 确定智能标签是否应被清除。未应用继承。写入 **bool**。 |
| virtual void [set_Spacing](../ibaseportionformat/set_spacing/)(**float**) | 设置字符间距增量。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。写入 **float**。 |
| virtual void [set_SpellCheck](../ibaseportionformat/set_spellcheck/)(**bool**) | 设置一个值，指示是否为文本部分启用拼写检查。当此属性设为 false 时，文本元素的拼写检查被抑制。设为 true 时，允许拼写检查。默认值为 **false**。 |
| virtual void [set_StrikethroughType](../ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | 设置文本的删除线类型。未应用继承。写入 [TextStrikethroughType](../textstrikethroughtype/)。 |
| virtual void [set_SymbolFont](../ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 设置符号字体信息。Null 表示字体未定义，应从母版继承。写入 [IFontData](../ifontdata/)。 |
| virtual void [set_TextCapType](../ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | 设置文本大小写类型。未应用继承。写入 [Slides::TextCapType](../textcaptype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 备注


此类用于返回和操作针对特定部分定义的文本部分格式属性。这意味着在获取值时不应用继承，因此在大多数情况下您会得到表示“未定义”的值。

为了获取包括继承在内的有效格式参数值，需要使用 [IPortionFormat::GetEffective](./geteffective/) 方法，该方法返回一个 [IPortionFormatEffectiveData](../iportionformateffectivedata/) 实例。

## 另见

* 类 [IBasePortionFormat](../ibaseportionformat/)
* 类 [IHyperlinkContainer](../ihyperlinkcontainer/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)