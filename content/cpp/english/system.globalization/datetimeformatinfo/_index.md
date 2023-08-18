---
title: DateTimeFormatInfo
second_title: Aspose.Slides for C++ API Reference
description: "Set of date and time formatting parameters. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 66
url: /system.globalization/datetimeformatinfo/
---
## DateTimeFormatInfo class


Set of date and time formatting parameters. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DateTimeFormatInfo : public virtual System::Object,
                           public System::IFormatProvider,
                           public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Clones format info. |
|  [DateTimeFormatInfo](./datetimeformatinfo/)() | Default constructor, constructs invariant format info. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedDayNames](./get_abbreviateddaynames/)() const | Gets abbreviated day names. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthGenitiveNames](./get_abbreviatedmonthgenitivenames/)() const | Gets abbreviated month names in genitive form. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthNames](./get_abbreviatedmonthnames/)() const | Gets abbreviated month names. |
| [String](../../system/string/) [get_AMDesignator](./get_amdesignator/)() const | Gets AM designator. |
| [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\> [get_Calendar](./get_calendar/)() const | Gets calendar associated with formatter. |
| [CalendarWeekRule](../calendarweekrule/) [get_CalendarWeekRule](./get_calendarweekrule/)() const | Gets calendar week rule associated with formatter. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | Gets current thread's date and time formatter. |
| [String](../../system/string/) [get_DateSeparator](./get_dateseparator/)() const | Gets date separator. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_DayNames](./get_daynames/)() const | Gets day names. |
| [DayOfWeek](../../system/dayofweek/) [get_FirstDayOfWeek](./get_firstdayofweek/)() const | Gets first day of week. |
| [String](../../system/string/) [get_FullDateTimePattern](./get_fulldatetimepattern/)() const | Gets full date and time pattern. |
| static const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | Gets invariant date and time formatter. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Checks whether formatter is read-only. |
| [String](../../system/string/) [get_LongDatePattern](./get_longdatepattern/)() const | Gets long date pattern. |
| [String](../../system/string/) [get_LongTimePattern](./get_longtimepattern/)() const | Gets long time pattern. |
| [String](../../system/string/) [get_MonthDayPattern](./get_monthdaypattern/)() const | Gets month day pattern. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthGenitiveNames](./get_monthgenitivenames/)() const | Gets month names in genitive form. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthNames](./get_monthnames/)() const | Gets month names. |
| [String](../../system/string/) [get_NativeCalendarName](./get_nativecalendarname/)() const | Gets native calendar name if available. |
| [String](../../system/string/) [get_PMDesignator](./get_pmdesignator/)() const | Gets PM designator. |
| [String](../../system/string/) [get_RFC1123Pattern](./get_rfc1123pattern/)() const | Gets RFC1123 pattern. |
| [String](../../system/string/) [get_ShortDatePattern](./get_shortdatepattern/)() const | Gets short date pattern. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_ShortestDayNames](./get_shortestdaynames/)() const | Gets shortest day names possible. |
| [String](../../system/string/) [get_ShortTimePattern](./get_shorttimepattern/)() const | Gets short time pattern. |
| [String](../../system/string/) [get_SortableDateTimePattern](./get_sortabledatetimepattern/)() const | Gets sortable date and time pattern. |
| [String](../../system/string/) [get_TimeSeparator](./get_timeseparator/)() const | Gets time separator. |
| [String](../../system/string/) [get_UniversalSortableDateTimePattern](./get_universalsortabledatetimepattern/)() const | Gets universal sortable date and time pattern. |
| [String](../../system/string/) [get_YearMonthPattern](./get_yearmonthpattern/)() const | Gets year and month pattern. |
| [String](../../system/string/) [GetAbbreviatedDayName](./getabbreviateddayname/)([DayOfWeek](../../system/dayofweek/)) const | Gets abbreviated week day name. |
| [String](../../system/string/) [GetAbbreviatedEraName](./getabbreviatederaname/)(int) const | Gets abbreviated era name. |
| [String](../../system/string/) [GetAbbreviatedMonthName](./getabbreviatedmonthname/)(int) const | Gets abbreviated month name. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)() const | Gets all patterns in which date and time values can be formatted. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)(char16_t) const | Gets all patterns in which date and time values can be formatted using specified format string. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| [String](../../system/string/) [GetDayName](./getdayname/)([DayOfWeek](../../system/dayofweek/)) const | Gets week day name. |
| int [GetEra](./getera/)(const [String](../../system/string/)\&) const | Gets era by name. |
| [String](../../system/string/) [GetEraName](./geteraname/)(int) const | Gets era name. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Gets formatter of specific type. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Gets formatter associated with format provider. |
| [String](../../system/string/) [GetLeapYearMonthName](./getleapyearmonthname/)(int) const | Gets leap-year month name. |
| [String](../../system/string/) [GetMonthGenitiveName](./getmonthgenitivename/)(int) const | Gets genitive month name. |
| [String](../../system/string/) [GetMonthName](./getmonthname/)(int) const | Gets month name. |
| [String](../../system/string/) [GetShortestDayName](./getshortestdayname/)([DayOfWeek](../../system/dayofweek/)) const | Gets shortes name for the specified day of week. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [DateTimeFormatInfo](./)\& [operator=](./operator_equal/)(const [DateTimeFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [ReadOnly](./readonly/)(const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\&) | Gets read-only version of formatter. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [set_AbbreviatedDayNames](./set_abbreviateddaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Sets abbreviated day names. |
| void [set_AbbreviatedMonthGenitiveNames](./set_abbreviatedmonthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Sets abbreviated month names in genitive form. |
| void [set_AbbreviatedMonthNames](./set_abbreviatedmonthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Sets abbreviated month names. |
| void [set_AMDesignator](./set_amdesignator/)(const [String](../../system/string/)\&) | Sets AM designator. |
| void [set_Calendar](./set_calendar/)(const [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\>\&) | Sets calendar associated with formatter. |
| void [set_CalendarWeekRule](./set_calendarweekrule/)([CalendarWeekRule](../calendarweekrule/)) | Sets calendar week rule associated with formatter. |
| void [set_DateSeparator](./set_dateseparator/)(const [String](../../system/string/)\&) | Sets date separator. |
| void [set_DayNames](./set_daynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Sets day names. |
| void [set_FirstDayOfWeek](./set_firstdayofweek/)([DayOfWeek](../../system/dayofweek/)) | Sets first day of week. |
| void [set_FullDateTimePattern](./set_fulldatetimepattern/)(const [String](../../system/string/)\&) | Sets full date and time pattern. |
| void [set_LongDatePattern](./set_longdatepattern/)(const [String](../../system/string/)\&) | Sets long date pattern. |
| void [set_LongTimePattern](./set_longtimepattern/)(const [String](../../system/string/)\&) | Sets long time pattern. |
| void [set_MonthDayPattern](./set_monthdaypattern/)(const [String](../../system/string/)\&) | Sets month day pattern. |
| void [set_MonthGenitiveNames](./set_monthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Sets month names in genitive form. |
| void [set_MonthNames](./set_monthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Sets month names. |
| void [set_PMDesignator](./set_pmdesignator/)(const [String](../../system/string/)\&) | Sets PM designator. |
| void [set_ShortDatePattern](./set_shortdatepattern/)(const [String](../../system/string/)\&) | Sets short date pattern. |
| void [set_ShortestDayNames](./set_shortestdaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Sets shortest day names possible. |
| void [set_ShortTimePattern](./set_shorttimepattern/)(const [String](../../system/string/)\&) | Sets short time pattern. |
| void [set_TimeSeparator](./set_timeseparator/)(const [String](../../system/string/)\&) | Sets time separator. |
| void [set_YearMonthPattern](./set_yearmonthpattern/)(const [String](../../system/string/)\&) | Sets year and month pattern. |
| void [SetAllDateTimePatterns](./setalldatetimepatterns/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, char16_t) | Sets patterns for the specified format. |
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

* Class [Object](../../system/object/)
* Class [IFormatProvider](../../system/iformatprovider/)
* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.Slides](../../)