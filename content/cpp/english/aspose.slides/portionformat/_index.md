---
title: PortionFormat
second_title: Aspose.Slides for C++ API Reference
description: This class contains the text portion formatting properties. Unlike IPortionFormatEffectiveData, all properties of this class are writeable.
type: docs
weight: 4733
url: /aspose.slides/portionformat/
---
## PortionFormat class


This class contains the text portion formatting properties. Unlike [IPortionFormatEffectiveData](../iportionformateffectivedata/), all properties of this class are writeable.

```cpp
class PortionFormat : public Aspose::Slides::BasePortionFormat,
                      public Aspose::Slides::IPortionFormat
```

## Methods

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compares with specified object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../baseportionformat/get_alternativelanguageid/)() override | Returns the Id of an alternative language. Read [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() override | Returns bookmark identifier. Read [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../baseportionformat/get_complexscriptfont/)() override | Returns the complex script font info. Null means font is undefined and should be inherited from the Master. Read [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../baseportionformat/get_eastasianfont/)() override | Returns the East Asian font info. Null means font is undefined and should be inherited from the Master. Read [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../baseportionformat/get_effectformat/)() override | Returns the text [EffectFormat](../effectformat/) properties. No inheritance applied. Read-only [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](../baseportionformat/get_escapement/)() override | Returns the superscript or subscript text. Value from -100% (subscript) to 100% (superscript). **std::numeric_limits<float>::quiet_NaN()** means value is undefined and should be inherited from the Master. Read **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../baseportionformat/get_fillformat/)() override | Returns the text [FillFormat](../fillformat/) properties. No inheritance applied. Read-only [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](../baseportionformat/get_fontbold/)() override | Determines whether the font is bold. No inheritance applied. Read [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](../baseportionformat/get_fontheight/)() override | Returns the font height of a portion. **std::numeric_limits<float>::quiet_NaN()** means height is undefined and should be inherited from the Master. Read **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](../baseportionformat/get_fontitalic/)() override | Determines whether the font is itallic. No inheritance applied. Read [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../baseportionformat/get_fontunderline/)() override | Returns the text underline type. No inheritance applied. Read [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../baseportionformat/get_highlightcolor/)() override | Returns the color used to highlight a text. No inheritance applied. Read-only [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | Returns the hyperlink defined for mouse click. Read [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | Hyperlinks manager. Read-only [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | Returns the hyperlink defined for mouse over. Read [IHyperlink](../ihyperlink/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../baseportionformat/get_ishardunderlinefill/)() override | Determines whether the underline style has own [FillFormat](../fillformat/) properties or inherits it from the [FillFormat](../fillformat/) properties of the text. Read [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../baseportionformat/get_ishardunderlineline/)() override | Determines whether the underline style has own [LineFormat](../lineformat/) properties or inherits it from the [LineFormat](../lineformat/) properties of the text. Read [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](../baseportionformat/get_kerningminimalsize/)() override | Returns the minimal font size, for which kerning should be switched on. **std::numeric_limits<float>::quiet_NaN()** means value is undefined and should be inherited from the Master. Read **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](../baseportionformat/get_kumimoji/)() override | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied. Read [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](../baseportionformat/get_languageid/)() override | Returns the Id of a proofing language. Used for checking spelling and grammar. Read [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../baseportionformat/get_latinfont/)() override | Returns the Latin font info. Null means font is undefined and should be inherited from the Master. Read [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../baseportionformat/get_lineformat/)() override | Returns the [LineFormat](../lineformat/) properties for text outlining. No inheritance applied. Read-only [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](../baseportionformat/get_normaliseheight/)() override | Determines whether the height of a text should be normalized. No inheritance applied. Read [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Returns Parent_Immediate object. Read-only [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Returns parent [IPresentationComponent](../ipresentationcomponent/). Read-only [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](../baseportionformat/get_proofdisabled/)() override | Determines whether the text shouldn't be proofed. No inheritance applied. Read [NullableBool](../nullablebool/). |
| **bool** [get_SmartTagClean](./get_smarttagclean/)() override | Determines whether the smart tag should be cleaned. No inheritance applied. Read **bool**. |
| **float** [get_Spacing](../baseportionformat/get_spacing/)() override | Returns the intercharacter spacing increment. **std::numeric_limits<float>::quiet_NaN()** means value is undefined and should be inherited from the Master. Read **float**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../baseportionformat/get_strikethroughtype/)() override | Returns the strikethrough type of a text. No inheritance applied. Read [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../baseportionformat/get_symbolfont/)() override | Returns the symbolic font info. Null means font is undefined and should be inherited from the Master. Read [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../baseportionformat/get_textcaptype/)() override | Returns the type of text capitalization. No inheritance applied. Read [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../baseportionformat/get_underlinefillformat/)() override | Returns the underline line [FillFormat](../fillformat/) properties. No inheritance applied. Read-only [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../baseportionformat/get_underlinelineformat/)() override | Returns the [LineFormat](../lineformat/) properties used to outline underline line. No inheritance applied. Read-only [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() override | Gets effective portion formatting data with the inheritance applied. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Returns hash code. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
|  [PortionFormat](./portionformat/)() | Initializes a new instance of [PortionFormat](./) class. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [set_AlternativeLanguageId](../baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | Sets the Id of an alternative language. Write [System::String](../../system/string/). |
| void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) override | Sets bookmark identifier. Write [System::String](../../system/string/). |
| void [set_ComplexScriptFont](../baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Sets the complex script font info. Null means font is undefined and should be inherited from the Master. Write [IFontData](../ifontdata/). |
| void [set_EastAsianFont](../baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Sets the East Asian font info. Null means font is undefined and should be inherited from the Master. Write [IFontData](../ifontdata/). |
| void [set_Escapement](../baseportionformat/set_escapement/)(**float**) override | Sets the superscript or subscript text. Value from -100% (subscript) to 100% (superscript). **std::numeric_limits<float>::quiet_NaN()** means value is undefined and should be inherited from the Master. Write **float**. |
| void [set_FontBold](../baseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) override | Determines whether the font is bold. No inheritance applied. Write [NullableBool](../nullablebool/). |
| void [set_FontHeight](../baseportionformat/set_fontheight/)(**float**) override | Sets the font height of a portion. **std::numeric_limits<float>::quiet_NaN()** means height is undefined and should be inherited from the Master. Write **float**. |
| void [set_FontItalic](../baseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) override | Determines whether the font is itallic. No inheritance applied. Write [NullableBool](../nullablebool/). |
| void [set_FontUnderline](../baseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Sets the text underline type. No inheritance applied. Write [TextUnderlineType](../textunderlinetype/). |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Sets the hyperlink defined for mouse click. Write [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Sets the hyperlink defined for mouse over. Write [IHyperlink](../ihyperlink/). |
| void [set_IsHardUnderlineFill](../baseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Determines whether the underline style has own [FillFormat](../fillformat/) properties or inherits it from the [FillFormat](../fillformat/) properties of the text. Write [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](../baseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Determines whether the underline style has own [LineFormat](../lineformat/) properties or inherits it from the [LineFormat](../lineformat/) properties of the text. Write [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](../baseportionformat/set_kerningminimalsize/)(**float**) override | Sets the minimal font size, for which kerning should be switched on. **std::numeric_limits<float>::quiet_NaN()** means value is undefined and should be inherited from the Master. Write **float**. |
| void [set_Kumimoji](../baseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) override | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied. Write [NullableBool](../nullablebool/). |
| void [set_LanguageId](../baseportionformat/set_languageid/)([System::String](../../system/string/)) override | Sets the Id of a proofing language. Used for checking spelling and grammar. Write [System::String](../../system/string/). |
| void [set_LatinFont](../baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Sets the Latin font info. Null means font is undefined and should be inherited from the Master. Write [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](../baseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) override | Determines whether the height of a text should be normalized. No inheritance applied. Write [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](../baseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) override | Determines whether the text shouldn't be proofed. No inheritance applied. Write [NullableBool](../nullablebool/). |
| void [set_SmartTagClean](./set_smarttagclean/)(**bool**) override | Determines whether the smart tag should be cleaned. No inheritance applied. Write **bool**. |
| void [set_Spacing](../baseportionformat/set_spacing/)(**float**) override | Sets the intercharacter spacing increment. **std::numeric_limits<float>::quiet_NaN()** means value is undefined and should be inherited from the Master. Write **float**. |
| void [set_StrikethroughType](../baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Sets the strikethrough type of a text. No inheritance applied. Write [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](../baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Sets the symbolic font info. Null means font is undefined and should be inherited from the Master. Write [IFontData](../ifontdata/). |
| void [set_TextCapType](../baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Sets the type of text capitalization. No inheritance applied. Write [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## Remarks


This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that no inheritance is applied when getting values so for the majority of cases you will get values meaning \"undefined\".

In order to get the effective formatting parameter values including inherited you need to use [PortionFormat::GetEffective](./geteffective/) method which returns a [IPortionFormatEffectiveData](../iportionformateffectivedata/) instance.

The following examples shows you how to assign the Latin font to a [Paragraph](../paragraph/)'s portion of PowerPoint [Presentation](../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

System::SharedPtr<Paragraph> paragraph = System::MakeObject<Paragraph>();
System::SharedPtr<Portion> portion = System::MakeObject<Portion>(u"Theme text format");
paragraph->get_Portions()->Add(portion);
shape->get_TextFrame()->get_Paragraphs()->Add(paragraph);
// Aspose.Slides uses these special identifiers (similar to those used in PowerPoint):
// +mn-lt - Body Font Latin (Minor Latin Font)
// +mj-lt -Heading Font Latin (Major Latin Font)
// +mn-ea - Body Font East Asian (Minor East Asian Font)
// +mj-ea - Body Font East Asian (Minor East Asian Font)
portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"+mn-lt"));
```

## See Also

* Class [BasePortionFormat](../baseportionformat/)
* Class [IPortionFormat](../iportionformat/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)