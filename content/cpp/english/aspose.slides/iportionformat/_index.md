---
title: IPortionFormat
second_title: Aspose.Slides for C++ API Reference
description: This class contains the text portion formatting properties. Unlike IPortionFormatEffectiveData, all properties of this class are writeable.
type: docs
weight: 3277
url: /aspose.slides/iportionformat/
---
## IPortionFormat class


This class contains the text portion formatting properties. Unlike [IPortionFormatEffectiveData](../iportionformateffectivedata/), all properties of this class are writeable.

```cpp
class IPortionFormat : public virtual Aspose::Slides::IBasePortionFormat,
                       public Aspose::Slides::IHyperlinkContainer
```

## Methods

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformat/get_alternativelanguageid/)() | Returns the Id of an alternative language. Read [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | Returns bookmark identifier. Read [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformat/get_complexscriptfont/)() | Returns the complex script font info. Null means font is undefined and should be inherited from the Master. Read [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformat/get_eastasianfont/)() | Returns the East Asian font info. Null means font is undefined and should be inherited from the Master. Read [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ibaseportionformat/get_effectformat/)() | Returns the text [EffectFormat](../effectformat/) properties. No inheritance applied. Read-only [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](../ibaseportionformat/get_escapement/)() | Returns the superscript or subscript text. Value from -100% (subscript) to 100% (superscript). **std::numeric_limits<float>::quiet_NaN()** means value is undefined and should be inherited from the Master. Read **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ibaseportionformat/get_fillformat/)() | Returns the text [FillFormat](../fillformat/) properties. No inheritance applied. Read-only [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](../ibaseportionformat/get_fontbold/)() | Determines whether the font is bold. No inheritance applied. Read [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](../ibaseportionformat/get_fontheight/)() | Returns the font height of a portion. **std::numeric_limits<float>::quiet_NaN()** means height is undefined and should be inherited from the Master. Read **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](../ibaseportionformat/get_fontitalic/)() | Determines whether the font is itallic. No inheritance applied. Read [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformat/get_fontunderline/)() | Returns the text underline type. No inheritance applied. Read [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../ibaseportionformat/get_highlightcolor/)() | Returns the color used to highlight a text. No inheritance applied. Read-only [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Returns the hyperlink defined for mouse click. Read [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlinks manager Read-only [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Returns the hyperlink defined for mouse over. Read [IHyperlink](../ihyperlink/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../ibaseportionformat/get_ishardunderlinefill/)() | Determines whether the underline style has own [FillFormat](../fillformat/) properties or inherits it from the [FillFormat](../fillformat/) properties of the text. Read [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../ibaseportionformat/get_ishardunderlineline/)() | Determines whether the underline style has own [LineFormat](../lineformat/) properties or inherits it from the [LineFormat](../lineformat/) properties of the text. Read [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformat/get_kerningminimalsize/)() | Returns the minimal font size, for which kerning should be switched on. **std::numeric_limits<float>::quiet_NaN()** means value is undefined and should be inherited from the Master. Read **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](../ibaseportionformat/get_kumimoji/)() | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied. Read [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformat/get_languageid/)() | Returns the Id of a proofing language. Used for checking spelling and grammar. Read [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformat/get_latinfont/)() | Returns the Latin font info. Null means font is undefined and should be inherited from the Master. Read [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ibaseportionformat/get_lineformat/)() | Returns the [LineFormat](../lineformat/) properties for text outlining. No inheritance applied. Read-only [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](../ibaseportionformat/get_normaliseheight/)() | Determines whether the height of a text should be normalized. No inheritance applied. Read [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](../ibaseportionformat/get_proofdisabled/)() | Determines whether the text shouldn't be proofed. No inheritance applied. Read [NullableBool](../nullablebool/). |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | Determines whether the smart tag should be cleaned. No inheritance applied. Read **bool**. |
| virtual **float** [get_Spacing](../ibaseportionformat/get_spacing/)() | Returns the intercharacter spacing increment. **std::numeric_limits<float>::quiet_NaN()** means value is undefined and should be inherited from the Master. Read **float**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformat/get_strikethroughtype/)() | Returns the strikethrough type of a text. No inheritance applied. Read [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformat/get_symbolfont/)() | Returns the symbolic font info. Null means font is undefined and should be inherited from the Master. Read [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformat/get_textcaptype/)() | Returns the type of text capitalization. No inheritance applied. Read [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../ibaseportionformat/get_underlinefillformat/)() | Returns the underline line [FillFormat](../fillformat/) properties. No inheritance applied. Read-only [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../ibaseportionformat/get_underlinelineformat/)() | Returns the [LineFormat](../lineformat/) properties used to outline underline line. No inheritance applied. Read-only [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() | Gets effective portion formatting data with the inheritance applied. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| virtual void [set_AlternativeLanguageId](../ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | Sets the Id of an alternative language. Write [System::String](../../system/string/). |
| virtual void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) | Sets bookmark identifier. Write [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](../ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Sets the complex script font info. Null means font is undefined and should be inherited from the Master. Write [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](../ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Sets the East Asian font info. Null means font is undefined and should be inherited from the Master. Write [IFontData](../ifontdata/). |
| virtual void [set_Escapement](../ibaseportionformat/set_escapement/)(**float**) | Sets the superscript or subscript text. Value from -100% (subscript) to 100% (superscript). **std::numeric_limits<float>::quiet_NaN()** means value is undefined and should be inherited from the Master. Write **float**. |
| virtual void [set_FontBold](../ibaseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) | Determines whether the font is bold. No inheritance applied. Write [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](../ibaseportionformat/set_fontheight/)(**float**) | Sets the font height of a portion. **std::numeric_limits<float>::quiet_NaN()** means height is undefined and should be inherited from the Master. Write **float**. |
| virtual void [set_FontItalic](../ibaseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) | Determines whether the font is itallic. No inheritance applied. Write [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](../ibaseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Sets the text underline type. No inheritance applied. Write [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Sets the hyperlink defined for mouse click. Write [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Sets the hyperlink defined for mouse over. Write [IHyperlink](../ihyperlink/). |
| virtual void [set_IsHardUnderlineFill](../ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Determines whether the underline style has own [FillFormat](../fillformat/) properties or inherits it from the [FillFormat](../fillformat/) properties of the text. Write [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](../ibaseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Determines whether the underline style has own [LineFormat](../lineformat/) properties or inherits it from the [LineFormat](../lineformat/) properties of the text. Write [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](../ibaseportionformat/set_kerningminimalsize/)(**float**) | Sets the minimal font size, for which kerning should be switched on. **std::numeric_limits<float>::quiet_NaN()** means value is undefined and should be inherited from the Master. Write **float**. |
| virtual void [set_Kumimoji](../ibaseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied. Write [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](../ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | Sets the Id of a proofing language. Used for checking spelling and grammar. Write [System::String](../../system/string/). |
| virtual void [set_LatinFont](../ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Sets the Latin font info. Null means font is undefined and should be inherited from the Master. Write [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](../ibaseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) | Determines whether the height of a text should be normalized. No inheritance applied. Write [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](../ibaseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) | Determines whether the text shouldn't be proofed. No inheritance applied. Write [NullableBool](../nullablebool/). |
| virtual void [set_SmartTagClean](./set_smarttagclean/)(**bool**) | Determines whether the smart tag should be cleaned. No inheritance applied. Write **bool**. |
| virtual void [set_Spacing](../ibaseportionformat/set_spacing/)(**float**) | Sets the intercharacter spacing increment. **std::numeric_limits<float>::quiet_NaN()** means value is undefined and should be inherited from the Master. Write **float**. |
| virtual void [set_StrikethroughType](../ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Sets the strikethrough type of a text. No inheritance applied. Write [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](../ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Sets the symbolic font info. Null means font is undefined and should be inherited from the Master. Write [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](../ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Sets the type of text capitalization. No inheritance applied. Write [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## Remarks


This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that no inheritance is applied when getting values so for the majority of cases you will get values meaning \"undefined\".

In order to get the effective formatting parameter values including inherited you need to use [IPortionFormat::GetEffective](./geteffective/) method which returns a [IPortionFormatEffectiveData](../iportionformateffectivedata/) instance.
## See Also

* Class [IBasePortionFormat](../ibaseportionformat/)
* Class [IHyperlinkContainer](../ihyperlinkcontainer/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)