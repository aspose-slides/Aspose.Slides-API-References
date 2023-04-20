---
title: Calendar
second_title: Aspose.Slides for C++ API Reference
description: "Calendar which defines how the dates are handled, calculated, formatted, etc. Setter operations are only enabled on non-read-only objects. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 1
url: /cpp/system.globalization/calendar/
---
## Calendar class


[Calendar](./) which defines how the dates are handled, calculated, formatted, etc. Setter operations are only enabled on non-read-only objects. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Calendar : public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](./adddays/)([DateTime](../../system/datetime/), int) const | Adds days to time point. |
| virtual [DateTime](../../system/datetime/) [AddHours](./addhours/)([DateTime](../../system/datetime/), int) const | Adds hours to time point. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](./addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Adds milliseconds to time point. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](./addminutes/)([DateTime](../../system/datetime/), int) const | Adds minutes to time point. |
| virtual [DateTime](../../system/datetime/) [AddMonths](./addmonths/)([DateTime](../../system/datetime/), int) const | Adds months to time point. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](./addseconds/)([DateTime](../../system/datetime/), int) const | Adds seconds to time point. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](./addweeks/)([DateTime](../../system/datetime/), int) const | Adds weeks to time point. |
| virtual [DateTime](../../system/datetime/) [AddYears](./addyears/)([DateTime](../../system/datetime/), int) const | Adds years to time point. |
|  [Calendar](./calendar/)(const [Calendar](./)\&) | RTTI information. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | Creates a copy of the current object and returns a shared pointer to it. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| virtual [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const | Gets algorithm type. |
| int [get_CurrentEra](./get_currentera/)() const | Gets index of current era. |
| int [get_CurrentEraValue](./get_currenteravalue/)() const | Gets value of current era. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const | Gets list of eras existing in calendar. |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](./get_id/)() const | Gets calendar identifier. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Checks if the calendar is read only. |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const | Maximal point in time that is supported by the calendar. |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const | Minimal point in time that is supported by the calendar. |
| virtual int [get_TwoDigitYearMax](./get_twodigityearmax/)() const | Gets the last year that can be represented by a 2-digit. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const | Gets day of month for the specified time point. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const | Gets day of week for the specified time point. |
| virtual int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const | Gets day of year for the specified time point. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Gets number of days in specific month. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Gets number of days in specific month. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Gets number of days in specific year. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Gets number of days in specific year. |
| virtual int [GetEra](./getera/)([DateTime](../../system/datetime/)) const | Gets era for the specified time point. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual int [GetHour](./gethour/)([DateTime](../../system/datetime/)) const | Gets hours for the specified time point. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Gets the leap month for the specified year. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Gets the leap month for the specified year. |
| virtual **double** [GetMilliseconds](./getmilliseconds/)([DateTime](../../system/datetime/)) const | Gets milliseconds for the specified time point. |
| virtual int [GetMinute](./getminute/)([DateTime](../../system/datetime/)) const | Gets minutes for the specified time point. |
| virtual int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const | Gets month for the specified time point. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Gets number of months in the specified year. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Gets number of months in the specified year. |
| virtual int [GetSecond](./getsecond/)([DateTime](../../system/datetime/)) const | Gets seconds for the specified time point. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual int [GetWeekOfYear](./getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Gets week of the year for the specified time point. |
| virtual int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const | Gets year for the specified time point. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Checks if the day is leap. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Checks if the day is leap. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Checks if the month is leap. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Checks if the month is leap. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Checks if the year is leap. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Checks if the year is leap. |
| **bool** [IsValidDay](./isvalidday/)(int, int, int, int) const | Checks year, month, day and era values. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Calendar](./)\& [operator=](./operator_equal/)(const [Calendar](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](./readonly/)(const [CalendarPtr](../calendarptr/)\&) | Gets read only version of calendar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| virtual void [set_TwoDigitYearMax](./set_twodigityearmax/)(int) | Sets the last year that can be represented by a 2-digit. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Constructs [DateTime](../../system/datetime/) object from components. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Constructs [DateTime](../../system/datetime/) object from components. |
| virtual int [ToFourDigitYear](./tofourdigityear/)(int) const | Converts the year to 4-digit year using TwoDigitYearMax property. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.Slides](../../)