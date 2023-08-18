---
title: OverrideTheme
second_title: Aspose.Slides for C++ API Reference
description: Represents a overriding theme.
type: docs
weight: 547
url: /aspose.slides.theme/overridetheme/
---
## OverrideTheme class


Represents a overriding theme.

```cpp
class OverrideTheme : public Aspose::Slides::Theme::Theme,
                      public Aspose::Slides::Theme::IOverrideTheme
```

## Methods

| Method | Description |
| --- | --- |
| void [Clear](./clear/)() override | Set [ColorScheme](../colorscheme/), [FontScheme](../fontscheme/), [FormatScheme](../formatscheme/) to null to disable any overriding with this theme object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ColorFormat](./get_colorformat/)([ColorSchemeIndex](../../aspose.slides/colorschemeindex/)) override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\> [get_ColorScheme](./get_colorscheme/)() override | Returns the color scheme. Read-only [IColorScheme](../icolorscheme/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\> [get_FontScheme](./get_fontscheme/)() override | Returns the font scheme. Read-only [IFontScheme](../ifontscheme/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\> [get_FormatScheme](./get_formatscheme/)() override | Returns the shape format scheme. Read-only [IFormatScheme](../iformatscheme/). |
| **bool** [get_IsEmpty](./get_isempty/)() override | True value means that [ColorScheme](../colorscheme/), [FontScheme](../fontscheme/), [FormatScheme](../formatscheme/) is null and any overriding with this theme object are disabled. Read-only **bool**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Returns parent [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Read-only [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../theme/get_presentation/)() override | Returns the parent presentation. Read-only [IPresentation](../../aspose.slides/ipresentation/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../ithemeeffectivedata/)\> [GetEffective](../theme/geteffective/)() override | Gets effective theme data with the inheritance applied. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| void [InitColorScheme](./initcolorscheme/)() override | Init [ColorScheme](../colorscheme/) with new object for overriding [ColorScheme](../colorscheme/) of InheritedTheme. |
| void [InitColorSchemeFrom](./initcolorschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\>) override | Init [ColorScheme](../colorscheme/) with new object for overriding [ColorScheme](../colorscheme/) of InheritedTheme. |
| void [InitColorSchemeFromInherited](./initcolorschemefrominherited/)() override | Init [ColorScheme](../colorscheme/) with new object for overriding [ColorScheme](../colorscheme/) of InheritedTheme. And initialize data of this new object with data of the [ColorScheme](../colorscheme/) of InheritedTheme. |
| void [InitFontScheme](./initfontscheme/)() override | Init [FontScheme](../fontscheme/) with new object for overriding [FontScheme](../fontscheme/) of InheritedTheme. |
| void [InitFontSchemeFrom](./initfontschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\>) override | Init [FontScheme](../fontscheme/) with new object for overriding [FontScheme](../fontscheme/) of InheritedTheme. |
| void [InitFontSchemeFromInherited](./initfontschemefrominherited/)() override | Init [FontScheme](../fontscheme/) with new object for overriding [FontScheme](../fontscheme/) of InheritedTheme. And initialize data of this new object with data of the [FontScheme](../fontscheme/) of InheritedTheme. |
| void [InitFormatScheme](./initformatscheme/)() override | Init [FormatScheme](../formatscheme/) with new object for overriding [FormatScheme](../formatscheme/) of InheritedTheme. |
| void [InitFormatSchemeFrom](./initformatschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\>) override | Init [FormatScheme](../formatscheme/) with new object for overriding [FormatScheme](../formatscheme/) of InheritedTheme. |
| void [InitFormatSchemeFromInherited](./initformatschemefrominherited/)() override | Init [FormatScheme](../formatscheme/) with new object for overriding [FormatScheme](../formatscheme/) of InheritedTheme. And initialize data of this new object with data of the [FormatScheme](../formatscheme/) of InheritedTheme. |
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
## See Also

* Class [Theme](../theme/)
* Class [IOverrideTheme](../ioverridetheme/)
* Namespace [Aspose::Slides::Theme](../)
* Library [Aspose.Slides](../../)