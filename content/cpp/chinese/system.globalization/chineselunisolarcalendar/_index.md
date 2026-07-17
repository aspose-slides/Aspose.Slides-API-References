---
title: ChineseLunisolarCalendar
second_title: Aspose.Slides C++ API 参考
description: "中文阴阳历。此类的对象应仅使用 System::MakeObject() 函数分配。不要在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 27
url: /zh/system.globalization/chineselunisolarcalendar/
---
## ChineseLunisolarCalendar 类


Chinese lunisolar calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ChineseLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | 向时间点添加天数。 |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | 向时间点添加小时。 |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | 向时间点添加毫秒。 |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | 向时间点添加分钟。 |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | 向时间点添加月份。 |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | 向时间点添加秒数。 |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | 向时间点添加周数。 |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | 向时间点添加年份。 |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI 信息。 |
|  [ChineseLunisolarCalendar](./chineselunisolarcalendar/)() | 默认构造函数。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | 创建当前对象的副本并返回指向它的共享指针。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](../eastasianlunisolarcalendar/get_algorithmtype/)() const override | RTTI 信息。 |
| int [get_CurrentEra](../calendar/get_currentera/)() const | 获取当前纪元的索引。 |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | 获取当前纪元的值。 |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | 获取日历中存在的纪元列表。 |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | 检查日历是否为只读。 |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | 日历支持的最大时间点。 |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | 日历支持的最小时间点。 |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | 获取可由两位数表示的最后一年。 |
| int [GetCelestialStem](../eastasianlunisolarcalendar/getcelestialstem/)(int) const | 获取天干。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | 获取指定时间点的月份中的天数。 |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | 获取指定时间点的星期几。 |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | 获取指定时间点的年度中的天数。 |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | 获取特定月份的天数。 |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | 获取特定月份的天数。 |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | 获取特定月份的天数。 |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | 获取特定年份的天数。 |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | 获取特定年份的天数。 |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | 获取指定时间点的纪元。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | 获取指定时间点的小时数。 |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | 获取指定年份的闰月。 |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | 获取指定年份的闰月。 |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | 获取指定年份的闰月。 |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | 获取指定时间点的毫秒数。 |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | 获取指定时间点的分钟数。 |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | 获取指定时间点的月份。 |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | 获取指定年份的月份数。 |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI 信息。 |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | RTTI 信息。 |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | 获取指定时间点的秒数。 |
| virtual int [GetSexagenaryYear](../eastasianlunisolarcalendar/getsexagenaryyear/)([DateTime](../../system/datetime/)) const | 获取天干地支循环中的年份。 |
| int [GetTerrestrialBranch](../eastasianlunisolarcalendar/getterrestrialbranch/)(int) const | 获取地支。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | 获取指定时间点的年度周数。 |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | 获取指定时间点的年份。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否是 targetType 描述的类型实例。相当于 C# 'is' 运算符。 |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | 检查该日是否为闰日。 |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | 检查该日是否为闰日。 |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | 检查该日是否为闰日。 |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | 检查该月是否为闰月。 |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | 检查该月是否为闰月。 |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | 检查该月是否为闰月。 |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | 检查该年是否为闰年。 |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | 检查该年是否为闰年。 |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | 检查该年是否为闰年。 |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | 检查年份、月份、日期和纪元的数值。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并允许子类复制构造。 |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类复制构造。 |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | 获取只读版本的日历。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情况的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | 设置可由两位数表示的最后一年。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设置为弱指针（而不是共享指针）。允许在容器中切换指针为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | 从组件构造 [DateTime](../../system/datetime/) 对象。 |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | 从组件构造 [DateTime](../../system/datetime/) 对象。 |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | 使用 TwoDigitYearMax 属性将年份转换为四位数。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 结构。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不应直接调用；请改用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| static constexpr [ChineseEra](./chineseera/) | 当前中文纪元。 |
## 另见

* 类 [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* 命名空间 [System::Globalization](../)
* 库 [Aspose.Slides](../../)