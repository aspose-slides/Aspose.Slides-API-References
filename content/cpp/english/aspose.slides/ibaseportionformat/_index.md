---
title: IBasePortionFormat
second_title: Aspose.Slides for C++ API Reference
description: This class contains the text portion formatting properties. Unlike IPortionFormatEffectiveData, all properties of this class are writeable.
type: docs
weight: 1457
url: /aspose.slides/ibaseportionformat/
---
## IBasePortionFormat class


This class contains the text portion formatting properties. Unlike [IPortionFormatEffectiveData](../iportionformateffectivedata/), all properties of this class are writeable.

```cpp
class IBasePortionFormat : public virtual System::Object
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
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | Returns the Id of an alternative language. Read [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | Returns the complex script font info. Null means font is undefined and should be inherited from the Master. Read [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | Returns the East Asian font info. Null means font is undefined and should be inherited from the Master. Read [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | Returns the text [EffectFormat](../effectformat/) properties. No inheritance applied. Read-only [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](./get_escapement/)() | Returns the superscript or subscript text. Value from -100% (subscript) to 100% (superscript). **std::numeric_limits<float>::quiet_NaN()** means value is undefined and should be inherited from the Master. Read **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | Returns the text [FillFormat](../fillformat/) properties. No inheritance applied. Read-only [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() | Determines whether the font is bold. No inheritance applied. Read [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](./get_fontheight/)() | Returns the font height of a portion. **std::numeric_limits<float>::quiet_NaN()** means height is undefined and should be inherited from the Master. Read **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() | Determines whether the font is itallic. No inheritance applied. Read [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | Returns the text underline type. No inheritance applied. Read [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() | Returns the color used to highlight a text. No inheritance applied. Read-only [IColorFormat](../icolorformat/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | Determines whether the underline style has own [FillFormat](../fillformat/) properties or inherits it from the [FillFormat](../fillformat/) properties of the text. Read [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | Determines whether the underline style has own [LineFormat](../lineformat/) properties or inherits it from the [LineFormat](../lineformat/) properties of the text. Read [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | Returns the minimal font size, for which kerning should be switched on. **std::numeric_limits<float>::quiet_NaN()** means value is undefined and should be inherited from the Master. Read **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied. Read [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | Returns the Id of a proofing language. Used for checking spelling and grammar. Read [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | Returns the Latin font info. Null means font is undefined and should be inherited from the Master. Read [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | Returns the [LineFormat](../lineformat/) properties for text outlining. No inheritance applied. Read-only [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() | Determines whether the height of a text should be normalized. No inheritance applied. Read [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() | Determines whether the text shouldn't be proofed. No inheritance applied. Read [NullableBool](../nullablebool/). |
| virtual **float** [get_Spacing](./get_spacing/)() | Returns the intercharacter spacing increment. **std::numeric_limits<float>::quiet_NaN()** means value is undefined and should be inherited from the Master. Read **float**. |
| virtual **bool** [get_SpellCheck](./get_spellcheck/)() | Gets a value indicating whether spell checking is enabled for the text portion. When this property is set to false, spelling checks for text elements are suppressed. When set to true, spell checking is allowed. Default value is **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | Returns the strikethrough type of a text. No inheritance applied. Read [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | Returns the symbolic font info. Null means font is undefined and should be inherited from the Master. Read [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | Returns the type of text capitalization. No inheritance applied. Read [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | Returns the underline line [FillFormat](../fillformat/) properties. No inheritance applied. Read-only [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | Returns the [LineFormat](../lineformat/) properties used to outline underline line. No inheritance applied. Read-only [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
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
| virtual void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) | Sets the Id of an alternative language. Write [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Sets the complex script font info. Null means font is undefined and should be inherited from the Master. Write [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Sets the East Asian font info. Null means font is undefined and should be inherited from the Master. Write [IFontData](../ifontdata/). |
| virtual void [set_Escapement](./set_escapement/)(**float**) | Sets the superscript or subscript text. Value from -100% (subscript) to 100% (superscript). **std::numeric_limits<float>::quiet_NaN()** means value is undefined and should be inherited from the Master. Write **float**. |
| virtual void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) | Determines whether the font is bold. No inheritance applied. Write [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](./set_fontheight/)(**float**) | Sets the font height of a portion. **std::numeric_limits<float>::quiet_NaN()** means height is undefined and should be inherited from the Master. Write **float**. |
| virtual void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) | Determines whether the font is itallic. No inheritance applied. Write [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Sets the text underline type. No inheritance applied. Write [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Determines whether the underline style has own [FillFormat](../fillformat/) properties or inherits it from the [FillFormat](../fillformat/) properties of the text. Write [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Determines whether the underline style has own [LineFormat](../lineformat/) properties or inherits it from the [LineFormat](../lineformat/) properties of the text. Write [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) | Sets the minimal font size, for which kerning should be switched on. **std::numeric_limits<float>::quiet_NaN()** means value is undefined and should be inherited from the Master. Write **float**. |
| virtual void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied. Write [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) | Sets the Id of a proofing language. Used for checking spelling and grammar. Write [System::String](../../system/string/). |
| virtual void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Sets the Latin font info. Null means font is undefined and should be inherited from the Master. Write [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) | Determines whether the height of a text should be normalized. No inheritance applied. Write [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) | Determines whether the text shouldn't be proofed. No inheritance applied. Write [NullableBool](../nullablebool/). |
| virtual void [set_Spacing](./set_spacing/)(**float**) | Sets the intercharacter spacing increment. **std::numeric_limits<float>::quiet_NaN()** means value is undefined and should be inherited from the Master. Write **float**. |
| virtual void [set_SpellCheck](./set_spellcheck/)(**bool**) | Sets a value indicating whether spell checking is enabled for the text portion. When this property is set to false, spelling checks for text elements are suppressed. When set to true, spell checking is allowed. Default value is **false**. |
| virtual void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Sets the strikethrough type of a text. No inheritance applied. Write [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Sets the symbolic font info. Null means font is undefined and should be inherited from the Master. Write [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Sets the type of text capitalization. No inheritance applied. Write [Slides::TextCapType](../textcaptype/). |
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

In order to get the effective formatting parameter values including inherited you need to use [IPortionFormat::GetEffective](../iportionformat/geteffective/) method which returns a [IPortionFormatEffectiveData](../iportionformateffectivedata/) instance.
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)