---
title: IChartPortionFormat
second_title: Aspose.Slides C++ API 参考
description: 表示图表中使用的图表部分格式属性。
type: docs
weight: 807
url: /zh/aspose.slides.charts/ichartportionformat/
---
## IChartPortionFormat 类

表示图表中使用的图表部分格式属性。

```cpp
class IChartPortionFormat : public virtual Aspose::Slides::IBasePortionFormat
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等，两个 NaN 仍被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等，两个 NaN 仍被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../../aspose.slides/ibaseportionformat/get_alternativelanguageid/)() | 返回备用语言的 Id。读取 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_ComplexScriptFont](../../aspose.slides/ibaseportionformat/get_complexscriptfont/)() | 返回复杂脚本字体信息。Null 表示字体未定义，应从母版继承。读取 [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_EastAsianFont](../../aspose.slides/ibaseportionformat/get_eastasianfont/)() | 返回东亚字体信息。Null 表示字体未定义，应从母版继承。读取 [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ibaseportionformat/get_effectformat/)() | 返回文本 [EffectFormat](../../aspose.slides/effectformat/) 属性。未应用继承。只读 [IEffectFormat](../../aspose.slides/ieffectformat/)。 |
| virtual **float** [get_Escapement](../../aspose.slides/ibaseportionformat/get_escapement/)() | 返回上标或下标文本。取值范围为 -100%（下标）至 100%（上标）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。读取 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ibaseportionformat/get_fillformat/)() | 返回文本 [FillFormat](../../aspose.slides/fillformat/) 属性。未应用继承。只读 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_FontBold](../../aspose.slides/ibaseportionformat/get_fontbold/)() | 确定字体是否加粗。未应用继承。读取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual **float** [get_FontHeight](../../aspose.slides/ibaseportionformat/get_fontheight/)() | 返回部分的字体高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定义，应从母版继承。读取 **float**。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_FontItalic](../../aspose.slides/ibaseportionformat/get_fontitalic/)() | 确定字体是否斜体。未应用继承。读取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual [TextUnderlineType](../../aspose.slides/textunderlinetype/) [get_FontUnderline](../../aspose.slides/ibaseportionformat/get_fontunderline/)() | 返回文本下划线类型。未应用继承。读取 [TextUnderlineType](../../aspose.slides/textunderlinetype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_HighlightColor](../../aspose.slides/ibaseportionformat/get_highlightcolor/)() | 返回用于突出显示文本的颜色。未应用继承。只读 [IColorFormat](../../aspose.slides/icolorformat/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/get_ishardunderlinefill/)() | 确定下划线样式是否拥有自己的 [FillFormat](../../aspose.slides/fillformat/) 属性或从文本的 [FillFormat](../../aspose.slides/fillformat/) 属性继承。读取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/get_ishardunderlineline/)() | 确定下划线样式是否拥有自己的 [LineFormat](../../aspose.slides/lineformat/) 属性或从文本的 [LineFormat](../../aspose.slides/lineformat/) 属性继承。读取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual **float** [get_KerningMinimalSize](../../aspose.slides/ibaseportionformat/get_kerningminimalsize/)() | 返回应开启字距调整的最小字体大小。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。读取 **float**。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_Kumimoji](../../aspose.slides/ibaseportionformat/get_kumimoji/)() | 确定数字是否应忽略文本东部语言特定的垂直布局。未应用继承。读取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual [System::String](../../system/string/) [get_LanguageId](../../aspose.slides/ibaseportionformat/get_languageid/)() | 返回校对语言的 Id。用于拼写和语法检查。读取 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_LatinFont](../../aspose.slides/ibaseportionformat/get_latinfont/)() | 返回拉丁字体信息。Null 表示字体未定义，应从母版继承。读取 [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ibaseportionformat/get_lineformat/)() | 返回用于文本轮廓的 [LineFormat](../../aspose.slides/lineformat/) 属性。未应用继承。只读 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_NormaliseHeight](../../aspose.slides/ibaseportionformat/get_normaliseheight/)() | 确定文本的高度是否应标准化。未应用继承。读取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_ProofDisabled](../../aspose.slides/ibaseportionformat/get_proofdisabled/)() | 确定文本是否不应进行校对。未应用继承。读取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual **float** [get_Spacing](../../aspose.slides/ibaseportionformat/get_spacing/)() | 返回字符间距增量。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。读取 **float**。 |
| virtual **bool** [get_SpellCheck](../../aspose.slides/ibaseportionformat/get_spellcheck/)() | 获取一个值，指示文本部分是否启用拼写检查。当此属性设置为 false 时，文本元素的拼写检查被抑制。设置为 true 时，允许进行拼写检查。默认值为 **false**。 |
| virtual [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/) [get_StrikethroughType](../../aspose.slides/ibaseportionformat/get_strikethroughtype/)() | 返回文本的删除线类型。未应用继承。读取 [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_SymbolFont](../../aspose.slides/ibaseportionformat/get_symbolfont/)() | 返回符号字体信息。Null 表示字体未定义，应从母版继承。读取 [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual [Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/) [get_TextCapType](../../aspose.slides/ibaseportionformat/get_textcaptype/)() | 返回文本大小写类型。未应用继承。读取 [Slides::TextCapType](../../aspose.slides/textcaptype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_UnderlineFillFormat](../../aspose.slides/ibaseportionformat/get_underlinefillformat/)() | 返回下划线线条 [FillFormat](../../aspose.slides/fillformat/) 属性。未应用继承。只读 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_UnderlineLineFormat](../../aspose.slides/ibaseportionformat/get_underlinelineformat/)() | 返回用于轮廓下划线线条的 [LineFormat](../../aspose.slides/lineformat/) 属性。未应用继承。只读 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
| [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并启用对子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并启用对子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_AlternativeLanguageId](../../aspose.slides/ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | 设置备用语言的 Id。写入 [System::String](../../system/string/)。 |
| virtual void [set_ComplexScriptFont](../../aspose.slides/ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | 设置复杂脚本字体信息。Null 表示字体未定义，应从母版继承。写入 [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual void [set_EastAsianFont](../../aspose.slides/ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | 设置东亚字体信息。Null 表示字体未定义，应从母版继承。写入 [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual void [set_Escapement](../../aspose.slides/ibaseportionformat/set_escapement/)(**float**) | 设置上标或下标文本。取值范围为 -100%（下标）至 100%（上标）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。写入 **float**。 |
| virtual void [set_FontBold](../../aspose.slides/ibaseportionformat/set_fontbold/)([NullableBool](../../aspose.slides/nullablebool/)) | 确定字体是否加粗。未应用继承。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_FontHeight](../../aspose.slides/ibaseportionformat/set_fontheight/)(**float**) | 设置部分的字体高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定义，应从母版继承。写入 **float**。 |
| virtual void [set_FontItalic](../../aspose.slides/ibaseportionformat/set_fontitalic/)([NullableBool](../../aspose.slides/nullablebool/)) | 确定字体是否斜体。未应用继承。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_FontUnderline](../../aspose.slides/ibaseportionformat/set_fontunderline/)([TextUnderlineType](../../aspose.slides/textunderlinetype/)) | 设置文本下划线类型。未应用继承。写入 [TextUnderlineType](../../aspose.slides/textunderlinetype/)。 |
| virtual void [set_IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../../aspose.slides/nullablebool/)) | 确定下划线样式是否拥有自己的 [FillFormat](../../aspose.slides/fillformat/) 属性或从文本的 [FillFormat](../../aspose.slides/fillformat/) 属性继承。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/set_ishardunderlineline/)([NullableBool](../../aspose.slides/nullablebool/)) | 确定下划线样式是否拥有自己的 [LineFormat](../../aspose.slides/lineformat/) 属性或从文本的 [LineFormat](../../aspose.slides/lineformat/) 属性继承。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_KerningMinimalSize](../../aspose.slides/ibaseportionformat/set_kerningminimalsize/)(**float**) | 设置应开启字距调整的最小字体大小。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。写入 **float**。 |
| virtual void [set_Kumimoji](../../aspose.slides/ibaseportionformat/set_kumimoji/)([NullableBool](../../aspose.slides/nullablebool/)) | 确定数字是否应忽略文本东部语言特定的垂直布局。未应用继承。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_LanguageId](../../aspose.slides/ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | 设置校对语言的 Id。用于拼写和语法检查。写入 [System::String](../../system/string/)。 |
| virtual void [set_LatinFont](../../aspose.slides/ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | 设置拉丁字体信息。Null 表示字体未定义，应从母版继承。写入 [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual void [set_NormaliseHeight](../../aspose.slides/ibaseportionformat/set_normaliseheight/)([NullableBool](../../aspose.slides/nullablebool/)) | 确定文本的高度是否应标准化。未应用继承。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_ProofDisabled](../../aspose.slides/ibaseportionformat/set_proofdisabled/)([NullableBool](../../aspose.slides/nullablebool/)) | 确定文本是否不应进行校对。未应用继承。写入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_Spacing](../../aspose.slides/ibaseportionformat/set_spacing/)(**float**) | 设置字符间距增量。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应从母版继承。写入 **float**。 |
| virtual void [set_SpellCheck](../../aspose.slides/ibaseportionformat/set_spellcheck/)(**bool**) | 设置一个值，指示文本部分是否启用拼写检查。当此属性设置为 false 时，文本元素的拼写检查被抑制。设置为 true 时，允许进行拼写检查。默认值为 **false**。 |
| virtual void [set_StrikethroughType](../../aspose.slides/ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)) | 设置文本的删除线类型。未应用继承。写入 [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)。 |
| virtual void [set_SymbolFont](../../aspose.slides/ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | 设置符号字体信息。Null 表示字体未定义，应从母版继承。写入 [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual void [set_TextCapType](../../aspose.slides/ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/)) | 设置文本大小写类型。未应用继承。写入 [Slides::TextCapType](../../aspose.slides/textcaptype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 另请参见

* 类 [IBasePortionFormat](../../aspose.slides/ibaseportionformat/)
* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)