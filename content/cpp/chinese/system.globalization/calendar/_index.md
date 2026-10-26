---
title: Calendar
second_title: Aspose.Slides C++ API 参考
description: "Calendar 定义了日期的处理、计算、格式化等方式。仅在非只读对象上启用 setter 操作。此类的对象应仅使用 System::MakeObject() 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装成 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 1
url: /zh/system.globalization/calendar/
---
## Calendar 类


[Calendar](./) 定义了日期的处理、计算、格式化等方式。仅在非只读对象上启用 setter 操作。此类的对象只能使用 [System::MakeObject()](../../system/makeobject/) 函数分配。切勿在栈上或使用 new 运算符创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装成 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class Calendar : public System::ICloneable
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](./adddays/)([DateTime](../../system/datetime/), int) const | 向时间点添加天数。 |
| virtual [DateTime](../../system/datetime/) [AddHours](./addhours/)([DateTime](../../system/datetime/), int) const | 向时间点添加小时。 |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](./addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | 向时间点添加毫秒。 |
| virtual [DateTime](../../system/datetime/) [AddMinutes](./addminutes/)([DateTime](../../system/datetime/), int) const | 向时间点添加分钟。 |
| virtual [DateTime](../../system/datetime/) [AddMonths](./addmonths/)([DateTime](../../system/datetime/), int) const | 向时间点添加月份。 |
| virtual [DateTime](../../system/datetime/) [AddSeconds](./addseconds/)([DateTime](../../system/datetime/), int) const | 向时间点添加秒数。 |
| virtual [DateTime](../../system/datetime/) [AddWeeks](./addweeks/)([DateTime](../../system/datetime/), int) const | 向时间点添加周数。 |
| virtual [DateTime](../../system/datetime/) [AddYears](./addyears/)([DateTime](../../system/datetime/), int) const | 向时间点添加年份。 |
|  [Calendar](./calendar/)(const [Calendar](./)\&) | RTTI 信息。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | 创建当前对象的副本并返回指向它的共享指针。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 在 C# 样式中比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 在 C# 样式中比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 与任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅用于内部目的。 |
| virtual [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const | 获取算法类型。 |
| int [get_CurrentEra](./get_currentera/)() const | 获取当前时代的索引。 |
| int [get_CurrentEraValue](./get_currenteravalue/)() const | 获取当前时代的值。 |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const | 获取日历中存在的时代列表。 |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](./get_id/)() const | 获取日历标识符。 |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | 检查日历是否为只读。 |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const | 日历支持的最大时间点。 |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const | 日历支持的最小时间点。 |
| virtual int [get_TwoDigitYearMax](./get_twodigityearmax/)() const | 获取可由两位数字表示的最后一年。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数数据结构。 |
| virtual int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const | 获取指定时间点的月份天数。 |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const | 获取指定时间点的星期几。 |
| virtual int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const | 获取指定时间点的年度天数。 |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | 获取特定月份的天数。 |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | 获取特定月份的天数。 |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | 获取特定年份的天数。 |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | 获取特定年份的天数。 |
| virtual int [GetEra](./getera/)([DateTime](../../system/datetime/)) const | 获取指定时间点的时代。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。支持自定义对象的哈希计算。 |
| virtual int [GetHour](./gethour/)([DateTime](../../system/datetime/)) const | 获取指定时间点的小时数。 |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | 获取指定年份的闰月。 |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | 获取指定年份的闰月。 |
| virtual **double** [GetMilliseconds](./getmilliseconds/)([DateTime](../../system/datetime/)) const | 获取指定时间点的毫秒数。 |
| virtual int [GetMinute](./getminute/)([DateTime](../../system/datetime/)) const | 获取指定时间点的分钟数。 |
| virtual int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const | 获取指定时间点的月份。 |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | 获取指定年份的月份数。 |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | 获取指定年份的月份数。 |
| virtual int [GetSecond](./getsecond/)([DateTime](../../system/datetime/)) const | 获取指定时间点的秒数。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual int [GetWeekOfYear](./getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | 获取指定时间点的年度周数。 |
| virtual int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const | 获取指定时间点的年份。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否为 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | 检查该日是否为闰日。 |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | 检查该日是否为闰日。 |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | 检查该月是否为闰月。 |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | 检查该月是否为闰月。 |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | 检查该年是否为闰年。 |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | 检查该年是否为闰年。 |
| **bool** [IsValidDay](./isvalidday/)(int, int, int, int) const | 检查年份、月份、日期和时代值。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的锁定。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。支持克隆自定义类型。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上并不复制任何内容，只是初始化新对象并允许为子类进行拷贝构造。 |
| [Calendar](./)\& [operator=](./operator_equal/)(const [Calendar](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上并不复制任何内容，只是初始化新对象并允许为子类进行拷贝构造。 |
| static [CalendarPtr](../calendarptr/) [ReadOnly](./readonly/)(const [CalendarPtr](../calendarptr/)\&) | 获取日历的只读版本。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串和 nullptr 的情况。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用于字符串的情况。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual void [set_TwoDigitYearMax](./set_twodigityearmax/)(int) | 设置可由两位数字表示的最后一年。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享指针）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | 从组件构建 [DateTime](../../system/datetime/) 对象。 |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | 从组件构建 [DateTime](../../system/datetime/) 对象。 |
| virtual int [ToFourDigitYear](./tofourdigityear/)(int) const | 使用 TwoDigitYearMax 属性将年份转换为四位数年份。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# [Object.ToString()](../../system/object/tostring/) 方法。支持将自定义对象转换为字符串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 监视对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |
## 另见

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.Slides](../../)