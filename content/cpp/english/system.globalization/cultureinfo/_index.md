---
title: CultureInfo
second_title: Aspose.Slides for C++ API Reference
description: "Collection of culture-specific values and algorithms. Setter operations are only enabled on non-read-only objects. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 53
url: /system.globalization/cultureinfo/
---
## CultureInfo class


Collection of culture-specific values and algorithms. Setter operations are only enabled on non-read-only objects. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CultureInfo : public virtual System::Object,
                    public System::IFormatProvider,
                    public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| void [ClearCachedData](./clearcacheddata/)() | Refreshes cached culture information. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Clones culture info. |
| static [CultureInfoPtr](../cultureinfoptr/) [CreateSpecificCulture](./createspecificculture/)(const [String](../../system/string/)\&) | Creates culture by name. |
| explicit  [CultureInfo](./cultureinfo/)(int) | RTTI information. |
|  [CultureInfo](./cultureinfo/)(int, **bool**) | Constructor. |
| explicit  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&) | Constructor. |
|  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&, **bool**) | Constructor. |
|  [CultureInfo](./cultureinfo/)(std::nullptr_t) | Always throws ArgumentNullException. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compares objects. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| virtual [CalendarPtr](../calendarptr/) [get_Calendar](./get_calendar/)() const | Gets calendar used by the culture. |
| virtual [CompareInfoPtr](../compareinfoptr/) [get_CompareInfo](./get_compareinfo/)() const | Gets string comparer that adheres to culture rules. |
| [CultureTypes](../culturetypes/) [get_CultureTypes](./get_culturetypes/)() const | Gets bitwise joint of culture types that describe the current culture. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentCulture](./get_currentculture/)() | Gets culture set for current thread. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentUICulture](./get_currentuiculture/)() | Gets current thread's UI culture. |
| virtual [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_DateTimeFormat](./get_datetimeformat/)() const | Gets date format information. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentCulture](./get_defaultthreadcurrentculture/)() | Gets default culture in the current application domain. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentUICulture](./get_defaultthreadcurrentuiculture/)() | Gets default UI culture in the current application domain. |
| virtual [String](../../system/string/) [get_DisplayName](./get_displayname/)() const | Gets culture display name. |
| virtual [String](../../system/string/) [get_EnglishName](./get_englishname/)() const | Gets culture English name. |
| [String](../../system/string/) [get_IetfLanguageTag](./get_ietflanguagetag/)() const | Gets the RFC 4646 name for a language. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InstalledUICulture](./get_installeduiculture/)() | Gets culture installed with the operating system. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InvariantCulture](./get_invariantculture/)() | Gets invariant culture. |
| virtual **bool** [get_IsNeutralCulture](./get_isneutralculture/)() const | Checks whether the culture is neutral. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Checks if culture object is read-only. |
| virtual int [get_KeyboardLayoutId](./get_keyboardlayoutid/)() const | Gets active input locale identifier. |
| virtual int [get_LCID](./get_lcid/)() const | Gets culture identifier. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | Gets culture name. |
| virtual [String](../../system/string/) [get_NativeName](./get_nativename/)() const | Gets culture native name. |
| virtual [NumberFormatInfoPtr](../numberformatinfoptr/) [get_NumberFormat](./get_numberformat/)() const | Gets number format information. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[CalendarPtr](../calendarptr/)\> [get_OptionalCalendars](./get_optionalcalendars/)() const | List of calendars that can be used with the culture. |
| virtual [CultureInfoPtr](../cultureinfoptr/) [get_Parent](./get_parent/)() const | Gets parent culture. |
| virtual [TextInfoPtr](../textinfoptr/) [get_TextInfo](./get_textinfo/)() const | Gets text parameters used by the culture. |
| virtual [String](../../system/string/) [get_ThreeLetterISOLanguageName](./get_threeletterisolanguagename/)() const | Gets three-letter ISO 639-2 language code. |
| virtual [String](../../system/string/) [get_ThreeLetterWindowsLanguageName](./get_threeletterwindowslanguagename/)() const | Gets three-letter code for language as defined in [Windows](../../system.windows/) API. |
| virtual [String](../../system/string/) [get_TwoLetterISOLanguageName](./get_twoletterisolanguagename/)() const | Gets two letters ISO language name associated with culture. |
| **bool** [get_UseUserOverride](./get_useuseroverride/)() const | Gets a flag indicating whether the [CultureInfo](./) uses user-selected culture settings. |
| [CultureInfoPtr](../cultureinfoptr/) [GetConsoleFallbackUICulture](./getconsolefallbackuiculture/)() const | Gets alternate culture suitable for console applications. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&) | Gets culture by its name. Same as CreateSpecificCulture. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Gets culture by its name. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(**int32_t**) | Gets culture by id. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfoByIetfLanguageTag](./getcultureinfobyietflanguagetag/)(const [String](../../system/string/)\&) | Deprecated. Gets a read-only [CultureInfo](./) object by the specified RFC 4646 language tag. |
| static [ArrayPtr](../../system/arrayptr/)\<[CultureInfoPtr](../cultureinfoptr/)\> [GetCultures](./getcultures/)([CultureTypes](../culturetypes/)) | Gets cultures that fall into specified types. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Gets format object for specific type. |
| int [GetHashCode](./gethashcode/)() const override | Returns object hash code. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| **bool** [IsInherited](./isinherited/)() const | Gets is-inherited flag. FOR INTERNAL USE. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [CultureInfo](./)\& [operator=](./operator_equal/)(const [CultureInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| **bool** [operator==](./operator_equal_equal/)(const [CultureInfo](./)\&) const | Compares culture parameters. |
| static [CultureInfoPtr](../cultureinfoptr/) [ReadOnly](./readonly/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Gets a read only version of culture. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| static void [set_CurrentCulture](./set_currentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Sets culture for current thread. |
| static void [set_CurrentUICulture](./set_currentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Sets current thread's UI culture. |
| virtual void [set_DateTimeFormat](./set_datetimeformat/)([DateTimeFormatInfoPtr](../datetimeformatinfoptr/)) | Sets date format information. |
| static void [set_DefaultThreadCurrentCulture](./set_defaultthreadcurrentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Sets default culture in the current application domain. |
| static void [set_DefaultThreadCurrentUICulture](./set_defaultthreadcurrentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Sets default UI culture in the current application domain. |
| virtual void [set_NumberFormat](./set_numberformat/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Gets number format information. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Converts culture to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [Object](../../system/object/)
* Class [IFormatProvider](../../system/iformatprovider/)
* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.Slides](../../)