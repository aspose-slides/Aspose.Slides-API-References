---
title: HijriCalendar
second_title: راهنمای API Aspose.Slides برای C++
description: "تقویم هجری. اشیای این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را بر روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های تأیید می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 157
url: /fa/system.globalization/hijricalendar/
---
## HijriCalendar کلاس

تقویم هجری. اشیای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) اختصاص داده شوند. هرگز نمونه‌ای از این نوع را بر روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های تأیید می‌شود. همواره این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید.

```cpp
class HijriCalendar : public System::Globalization::Calendar
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | روزها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | ساعت‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | میلی‌ثانیه‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | دقیقه‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | ماه‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | ثانیه‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | هفته‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | سال‌ها را به نقطه زمان اضافه می‌کند. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | اطلاعات RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | یک نسخه کپی از شیء فعلی ایجاد می‌کند و یک اشاره‌گر مشترک به آن برمی‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از مفاهیم [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیای نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیای نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، شامل NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، شامل NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | نوع الگوریتم را دریافت می‌کند. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | اندیس دوره فعلی را دریافت می‌کند. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | مقدار دوره فعلی را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | فهرست دوره‌های موجود در تقویم را دریافت می‌کند. |
| int [get_HijriAdjustment](./get_hijriadjustment/)() const | تنظیمات هجری را دریافت می‌کند. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | بررسی می‌کند که آیا تقویم فقط-خواندنی است یا نه. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | بیشینه نقطه زمان که توسط تقویم پشتیبانی می‌شود. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | کمینه نقطه زمان که توسط تقویم پشتیبانی می‌شود. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | آخرین سالی که می‌تواند با دو رقم نمایان شود را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | روز ماه برای نقطه زمان مشخص شده را دریافت می‌کند. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | روز هفته برای نقطه زمان مشخص شده را دریافت می‌کند. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | روز سال برای نقطه زمان مشخص شده را دریافت می‌کند. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | تعداد روزهای یک ماه خاص را دریافت می‌کند. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | تعداد روزهای یک ماه خاص را دریافت می‌کند. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | تعداد روزهای یک سال خاص را دریافت می‌کند. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | تعداد روزهای یک سال خاص را دریافت می‌کند. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | دوره برای نقطه زمان مشخص شده را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌سازی اشیای سفارشی را فراهم می‌کند. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | ساعات برای نقطه زمان مشخص شده را دریافت می‌کند. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | ماه کبیسه برای سال مشخص شده را دریافت می‌کند. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | اطلاعات RTTI. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | اطلاعات RTTI. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | میلی‌ثانیه‌ها برای نقطه زمان مشخص شده را دریافت می‌کند. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | دقیقه‌ها برای نقطه زمان مشخص شده را دریافت می‌کند. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | ماه برای نقطه زمان مشخص شده را دریافت می‌کند. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | تعداد ماه‌ها در سال مشخص شده را دریافت می‌کند. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | تعداد ماه‌ها در سال مشخص شده را دریافت می‌کند. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | ثانیه‌ها برای نقطه زمان مشخص شده را دریافت می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | هفته سال برای نقطه زمان مشخص شده را دریافت می‌کند. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | سال برای نقطه زمان مشخص شده را دریافت می‌کند. |
|  [HijriCalendar](./hijricalendar/)() | سازنده. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایندهٔ نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | بررسی می‌کند که آیا روز کبیسه است. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | بررسی می‌کند که آیا روز کبیسه است. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | بررسی می‌کند که آیا روز کبیسه است. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | بررسی می‌کند که آیا ماه کبیسه است. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | بررسی می‌کند که آیا ماه کبیسه است. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | بررسی می‌کند که آیا ماه کبیسه است. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | بررسی می‌کند که آیا سال کبیسه است. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | بررسی می‌کند که آیا سال کبیسه است. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | بررسی می‌کند که آیا سال کبیسه است. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | مقادیر سال، ماه، روز و دوره را بررسی می‌کند. |
| void [Lock](../../system/object/lock/)() | بیان قفل‌گذاری lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را می‌دهد. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر تخصیص. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را می‌دهد. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | نسخهٔ فقط-خواندنی تقویم را دریافت می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مرجع-مقایسهٔ شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_HijriAdjustment](./set_hijriadjustment/)(int) | تنظیمات هجری را تنظیم می‌کند. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | آخرین سالی که می‌تواند با دو رقم نمایان شود را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | شیء [DateTime](../../system/datetime/) را از اجزا می‌سازد. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | شیء [DateTime](../../system/datetime/) را از اجزا می‌سازد. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | سال را با استفاده از ویژگی TwoDigitYearMax به سال چهار رقمی تبدیل می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیای سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | سازوکار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | بیان بازقفل‌گذاری lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static constexpr [HijriEra](./hijriera/) | دورهٔ هجری فعلی. |

## موارد مرتبط

* کلاس [Calendar](../calendar/)
* فضای‌نام [System::Globalization](../)
* کتابخانه [Aspose.Slides](../../)