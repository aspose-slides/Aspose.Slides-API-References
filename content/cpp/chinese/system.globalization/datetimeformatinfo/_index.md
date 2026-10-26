---
title: DateTimeFormatInfo
second_title: Aspose.Slides for C++ API 参考
description: "日期和时间格式化参数的集合。此类的对象只能使用 System::MakeObject() 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 66
url: /zh/system.globalization/datetimeformatinfo/
---
## DateTimeFormatInfo 类

Set of date and time formatting parameters. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DateTimeFormatInfo : public virtual System::Object,
                           public System::IFormatProvider,
                           public System::ICloneable
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | 克隆格式信息。 |
| [DateTimeFormatInfo](./datetimeformatinfo/)() | 默认构造函数，构造不变的格式信息。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，在此比较中，即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，在此比较中，即使根据 IEC 60559:1989，NaN 不等于任何值（包括 NaN），两个 NaN 仍被视为相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedDayNames](./get_abbreviateddaynames/)() const | 获取缩写的星期名称。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthGenitiveNames](./get_abbreviatedmonthgenitivenames/)() const | 获取所有格形式的缩写月份名称。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthNames](./get_abbreviatedmonthnames/)() const | 获取缩写的月份名称。 |
| [String](../../system/string/) [get_AMDesignator](./get_amdesignator/)() const | 获取上午指示符。 |
| [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\> [get_Calendar](./get_calendar/)() const | 获取与格式化器关联的日历。 |
| [CalendarWeekRule](../calendarweekrule/) [get_CalendarWeekRule](./get_calendarweekrule/)() const | 获取与格式化器关联的日历周规则。 |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | 获取当前线程的日期和时间格式化器。 |
| [String](../../system/string/) [get_DateSeparator](./get_dateseparator/)() const | 获取日期分隔符。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_DayNames](./get_daynames/)() const | 获取星期名称。 |
| [DayOfWeek](../../system/dayofweek/) [get_FirstDayOfWeek](./get_firstdayofweek/)() const | 获取一周的第一天。 |
| [String](../../system/string/) [get_FullDateTimePattern](./get_fulldatetimepattern/)() const | 获取完整的日期和时间模式。 |
| static const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | 获取不变的日期和时间格式化器。 |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | 检查格式化器是否为只读。 |
| [String](../../system/string/) [get_LongDatePattern](./get_longdatepattern/)() const | 获取长日期模式。 |
| [String](../../system/string/) [get_LongTimePattern](./get_longtimepattern/)() const | 获取长时间模式。 |
| [String](../../system/string/) [get_MonthDayPattern](./get_monthdaypattern/)() const | 获取月份-日期模式。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthGenitiveNames](./get_monthgenitivenames/)() const | 获取所有格形式的月份名称。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthNames](./get_monthnames/)() const | 获取月份名称。 |
| [String](../../system/string/) [get_NativeCalendarName](./get_nativecalendarname/)() const | 获取本地日历名称（若可用）。 |
| [String](../../system/string/) [get_PMDesignator](./get_pmdesignator/)() const | 获取下午指示符。 |
| [String](../../system/string/) [get_RFC1123Pattern](./get_rfc1123pattern/)() const | 获取 RFC1123 模式。 |
| [String](../../system/string/) [get_ShortDatePattern](./get_shortdatepattern/)() const | 获取短日期模式。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_ShortestDayNames](./get_shortestdaynames/)() const | 获取可能的最短星期名称。 |
| [String](../../system/string/) [get_ShortTimePattern](./get_shorttimepattern/)() const | 获取短时间模式。 |
| [String](../../system/string/) [get_SortableDateTimePattern](./get_sortabledatetimepattern/)() const | 获取可排序的日期和时间模式。 |
| [String](../../system/string/) [get_TimeSeparator](./get_timeseparator/)() const | 获取时间分隔符。 |
| [String](../../system/string/) [get_UniversalSortableDateTimePattern](./get_universalsortabledatetimepattern/)() const | 获取通用可排序的日期和时间模式。 |
| [String](../../system/string/) [get_YearMonthPattern](./get_yearmonthpattern/)() const | 获取年份和月份模式。 |
| [String](../../system/string/) [GetAbbreviatedDayName](./getabbreviateddayname/)([DayOfWeek](../../system/dayofweek/)) const | 获取缩写的工作日名称。 |
| [String](../../system/string/) [GetAbbreviatedEraName](./getabbreviatederaname/)(int) const | 获取缩写的时代名称。 |
| [String](../../system/string/) [GetAbbreviatedMonthName](./getabbreviatedmonthname/)(int) const | 获取缩写的月份名称。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)() const | 获取日期和时间值可以格式化的所有模式。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)(char16_t) const | 使用指定的格式字符串获取日期和时间值可以格式化的所有模式。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| [String](../../system/string/) [GetDayName](./getdayname/)([DayOfWeek](../../system/dayofweek/)) const | 获取工作日名称。 |
| int [GetEra](./getera/)(const [String](../../system/string/)\&) const | 通过名称获取时代。 |
| [String](../../system/string/) [GetEraName](./geteraname/)(int) const | 获取时代名称。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | 获取特定类型的格式化器。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的类比。启用自定义对象的哈希。 |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | 获取与格式提供程序关联的格式化器。 |
| [String](../../system/string/) [GetLeapYearMonthName](./getleapyearmonthname/)(int) const | 获取闰年月份名称。 |
| [String](../../system/string/) [GetMonthGenitiveName](./getmonthgenitivename/)(int) const | 获取所有格形式的月份名称。 |
| [String](../../system/string/) [GetMonthName](./getmonthname/)(int) const | 获取月份名称。 |
| [String](../../system/string/) [GetShortestDayName](./getshortestdayname/)([DayOfWeek](../../system/dayofweek/)) const | 获取指定星期的最短名称。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
| [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | 拷贝构造函数。实际上不复制任何内容，只是初始化新对象并允许子类进行拷贝构造。 |
| [DateTimeFormatInfo](./)\& [operator=](./operator_equal/)(const [DateTimeFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类进行拷贝构造。 |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [ReadOnly](./readonly/)(const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\&) | 获取格式化器的只读版本。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | 针对字符串和 nullptr 情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | 针对字符串情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 将共享引用计数降低指定值。 |
| void [set_AbbreviatedDayNames](./set_abbreviateddaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 设置缩写的星期名称。 |
| void [set_AbbreviatedMonthGenitiveNames](./set_abbreviatedmonthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 设置所有格形式的缩写月份名称。 |
| void [set_AbbreviatedMonthNames](./set_abbreviatedmonthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 设置缩写的月份名称。 |
| void [set_AMDesignator](./set_amdesignator/)(const [String](../../system/string/)\&) | 设置上午指示符。 |
| void [set_Calendar](./set_calendar/)(const [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\>\&) | 设置与格式化器关联的日历。 |
| void [set_CalendarWeekRule](./set_calendarweekrule/)([CalendarWeekRule](../calendarweekrule/)) | 设置与格式化器关联的日历周规则。 |
| void [set_DateSeparator](./set_dateseparator/)(const [String](../../system/string/)\&) | 设置日期分隔符。 |
| void [set_DayNames](./set_daynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 设置星期名称。 |
| void [set_FirstDayOfWeek](./set_firstdayofweek/)([DayOfWeek](../../system/dayofweek/)) | 设置一周的第一天。 |
| void [set_FullDateTimePattern](./set_fulldatetimepattern/)(const [String](../../system/string/)\&) | 设置完整的日期和时间模式。 |
| void [set_LongDatePattern](./set_longdatepattern/)(const [String](../../system/string/)\&) | 设置长日期模式。 |
| void [set_LongTimePattern](./set_longtimepattern/)(const [String](../../system/string/)\&) | 设置长时间模式。 |
| void [set_MonthDayPattern](./set_monthdaypattern/)(const [String](../../system/string/)\&) | 设置月份-日期模式。 |
| void [set_MonthGenitiveNames](./set_monthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 设置所有格形式的月份名称。 |
| void [set_MonthNames](./set_monthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 设置月份名称。 |
| void [set_PMDesignator](./set_pmdesignator/)(const [String](../../system/string/)\&) | 设置下午指示符。 |
| void [set_ShortDatePattern](./set_shortdatepattern/)(const [String](../../system/string/)\&) | 设置短日期模式。 |
| void [set_ShortestDayNames](./set_shortestdaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 设置可能的最短星期名称。 |
| void [set_ShortTimePattern](./set_shorttimepattern/)(const [String](../../system/string/)\&) | 设置短时间模式。 |
| void [set_TimeSeparator](./set_timeseparator/)(const [String](../../system/string/)\&) | 设置时间分隔符。 |
| void [set_YearMonthPattern](./set_yearmonthpattern/)(const [String](../../system/string/)\&) | 设置年份和月份模式。 |
| void [SetAllDateTimePatterns](./setalldatetimepatterns/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, char16_t) | 为指定的格式设置模式。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 参见

* 类 [Object](../../system/object/)
* 类 [IFormatProvider](../../system/iformatprovider/)
* 类 [ICloneable](../../system/icloneable/)
* 命名空间 [System::Globalization](../)
* 库 [Aspose.Slides](../../)