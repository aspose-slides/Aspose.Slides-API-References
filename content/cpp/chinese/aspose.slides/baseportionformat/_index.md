---
title: BasePortionFormat
second_title: Aspose.Slides C++ API 参考
description: 通用文本片段格式属性。
type: docs
weight: 144
url: /zh/aspose.slides/baseportionformat/
---
## BasePortionFormat 类

通用文本片段格式属性。

```cpp
class BasePortionFormat : public Aspose::Slides::PVIObject,
                          public virtual Aspose::Slides::IBasePortionFormat
```

## 方法

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 与指定对象比较。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 样式的浮点比较，两个 NaN 被视为相等，即使根据 IEC 60559:1989 NaN 不等于任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 样式的浮点比较，两个 NaN 被视为相等，即使根据 IEC 60559:1989 NaN 不等于任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() override | 返回替代语言的 Id。读取 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() override | 返回复杂脚本字体信息。Null 表示字体未定义，应该从母版继承。读取 [IFontData](../ifontdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() override | 返回东亚字体信息。Null 表示字体未定义，应该从母版继承。读取 [IFontData](../ifontdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | 返回文本 [EffectFormat](../effectformat/) 属性。未应用继承。只读 [IEffectFormat](../ieffectformat/)。 |
| **float** [get_Escapement](./get_escapement/)() override | 返回上标或下标文本。取值范围 -100%（下标）到 100%（上标）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应该从母版继承。读取 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | 返回文本 [FillFormat](../fillformat/) 属性。未应用继承。只读 [IFillFormat](../ifillformat/)。 |
| [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() override | 判断字体是否加粗。未应用继承。读取 [NullableBool](../nullablebool/)。 |
| **float** [get_FontHeight](./get_fontheight/)() override | 返回部分的字体高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定义，应该从母版继承。读取 **float**。 |
| [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() override | 判断字体是否斜体。未应用继承。读取 [NullableBool](../nullablebool/)。 |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() override | 返回文本下划线类型。未应用继承。读取 [TextUnderlineType](../textunderlinetype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() override | 返回用于突出显示文本的颜色。未应用继承。只读 [IColorFormat](../icolorformat/)。 |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() override | 判断下划线样式是否拥有自己的 [FillFormat](../fillformat/) 属性或从文本的 [FillFormat](../fillformat/) 属性继承。读取 [NullableBool](../nullablebool/)。 |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() override | 判断下划线样式是否拥有自己的 [LineFormat](../lineformat/) 属性或从文本的 [LineFormat](../lineformat/) 属性继承。读取 [NullableBool](../nullablebool/)。 |
| **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() override | 返回应打开字距调整的最小字体大小。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应该从母版继承。读取 **float**。 |
| [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() override | 判断数字是否应忽略文本东亚语言特定的垂直布局。未应用继承。读取 [NullableBool](../nullablebool/)。 |
| [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() override | 返回校对语言的 Id。用于拼写和语法检查。读取 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() override | 返回拉丁字体信息。Null 表示字体未定义，应该从母版继承。读取 [IFontData](../ifontdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | 返回文本描边的 [LineFormat](../lineformat/) 属性。未应用继承。只读 [ILineFormat](../ilineformat/)。 |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() override | 判断文本高度是否应标准化。未应用继承。读取 [NullableBool](../nullablebool/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | 返回 Parent_Immediate 对象。只读 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 返回父级 [IPresentationComponent](../ipresentationcomponent/)。只读 [IPresentationComponent](../ipresentationcomponent/)。 |
| [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() override | 判断文本是否不应进行校对。未应用继承。读取 [NullableBool](../nullablebool/)。 |
| **float** [get_Spacing](./get_spacing/)() override | 返回字符间距增量。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应该从母版继承。读取 **float**。 |
| **bool** [get_SpellCheck](./get_spellcheck/)() override | 获取指示文本部分是否启用拼写检查的值。当此属性设为 false 时，抑制对文本元素的拼写检查。设为 true 时，允许拼写检查。默认值为 **false**。 |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() override | 返回文本的删除线类型。未应用继承。读取 [TextStrikethroughType](../textstrikethroughtype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() override | 返回符号字体信息。Null 表示字体未定义，应该从母版继承。读取 [IFontData](../ifontdata/)。 |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() override | 返回文本大小写类型。未应用继承。读取 [Slides::TextCapType](../textcaptype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() override | 返回下划线线 [FillFormat](../fillformat/) 属性。未应用继承。只读 [IFillFormat](../ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() override | 返回用于描边下划线线的 [LineFormat](../lineformat/) 属性。未应用继承。只读 [ILineFormat](../ilineformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 返回哈希码。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是目标类型的实例。相当于 C# 'is' 运算符。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不拷贝任何内容，只是初始化新对象并启用子类的拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不拷贝任何内容，只是初始化新对象并启用子类的拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 对字符串和 nullptr 情形的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 对字符串情形的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值递减共享引用计数。 |
| void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) override | 设置替代语言的 Id。写入 [System::String](../../system/string/)。 |
| void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 设置复杂脚本字体信息。Null 表示字体未定义，应该从母版继承。写入 [IFontData](../ifontdata/)。 |
| void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 设置东亚字体信息。Null 表示字体未定义，应该从母版继承。写入 [IFontData](../ifontdata/)。 |
| void [set_Escapement](./set_escapement/)(**float**) override | 设置上标或下标文本。取值范围 -100%（下标）到 100%（上标）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应该从母版继承。写入 **float**。 |
| void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) override | 判断字体是否加粗。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| void [set_FontHeight](./set_fontheight/)(**float**) override | 设置部分的字体高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定义，应该从母版继承。写入 **float**。 |
| void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) override | 判断字体是否斜体。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | 设置文本下划线类型。未应用继承。写入 [TextUnderlineType](../textunderlinetype/)。 |
| void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | 判断下划线样式是否拥有自己的 [FillFormat](../fillformat/) 属性或从文本的 [FillFormat](../fillformat/) 属性继承。写入 [NullableBool](../nullablebool/)。 |
| void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | 判断下划线样式是否拥有自己的 [LineFormat](../lineformat/) 属性或从文本的 [LineFormat](../lineformat/) 属性继承。写入 [NullableBool](../nullablebool/)。 |
| void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) override | 设置应打开字距调整的最小字体大小。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应该从母版继承。写入 **float**。 |
| void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) override | 判断数字是否应忽略文本东亚语言特定的垂直布局。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) override | 设置校对语言的 Id。用于拼写和语法检查。写入 [System::String](../../system/string/)。 |
| void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 设置拉丁字体信息。Null 表示字体未定义，应该从母版继承。写入 [IFontData](../ifontdata/)。 |
| void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) override | 判断文本高度是否应标准化。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) override | 判断文本是否不应进行校对。未应用继承。写入 [NullableBool](../nullablebool/)。 |
| void [set_Spacing](./set_spacing/)(**float**) override | 设置字符间距增量。**std::numeric_limits<float>::quiet_NaN()** 表示值未定义，应该从母版继承。写入 **float**。 |
| void [set_SpellCheck](./set_spellcheck/)(**bool**) override | 设置指示文本部分是否启用拼写检查的值。当此属性设为 false 时，抑制对文本元素的拼写检查。设为 true 时，允许拼写检查。默认值为 **false**。 |
| void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | 设置文本的删除线类型。未应用继承。写入 [TextStrikethroughType](../textstrikethroughtype/)。 |
| void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 设置符号字体信息。Null 表示字体未定义，应该从母版继承。写入 [IFontData](../ifontdata/)。 |
| void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | 设置文本大小写类型。未应用继承。写入 [Slides::TextCapType](../textcaptype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 减少并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 减少弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 参见

* 类 [PVIObject](../pviobject/)
* 类 [IBasePortionFormat](../ibaseportionformat/)
* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)