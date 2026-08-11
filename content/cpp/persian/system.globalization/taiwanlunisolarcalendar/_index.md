---
title: TaiwanLunisolarCalendar
second_title: مرجع API Aspose.Slides برای C++
description: "تقویم خورشیدی-ماه‌پروژهٔ تایوان. هنوز پیاده‌سازی نشده. اشیای این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های اعتبارسنجی می‌شود. همیشه این کلاس را درون اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 339
url: /fa/system.globalization/taiwanlunisolarcalendar/
---
## TaiwanLunisolarCalendar کلاس

تقویم خورشیدی-ماه‌پروژهٔ تایوان. پیاده‌سازی نشده است. اشیای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از اپراتور new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های اعتبارسنجی می‌شود. همیشه این کلاس را درون اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به عنوان آرگومان به توابع استفاده کنید.

```cpp
class TaiwanLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## متدها

| Method | Description |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | روزها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | ساعت‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | میلی‌ثانیه‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | دقایق را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | ماه‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | ثانیه‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | هفته‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | سال‌ها را به نقطه زمان اضافه می‌کند. |
| [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | اطلاعات RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | یک کپی از شیء جاری ایجاد می‌کند و یک shared pointer به آن بر می‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیا را با استفاده از قواعد C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیای نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیای نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌عطف به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN با هیچ مقداری برابر نیست، حتی NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌عطف دوبل به سبک C# را شبیه‌سازی می‌کند که دو NaN را برابر می‌داند، هرچند بر اساس IEC 60559:1989 NaN برابر هیچ مقداری نیست، حتی NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](../eastasianlunisolarcalendar/get_algorithmtype/)() const override | اطلاعات RTTI. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | اندیس دورهٔ فعلی را دریافت می‌کند. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | مقدار دورهٔ فعلی را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | فهرست دوره‌های موجود در تقویم را دریافت می‌کند. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | بررسی می‌کند که آیا تقویم فقط-خواندنی است یا خیر. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | بیشینه نقطه زمان که توسط تقویم پشتیبانی می‌شود. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | کمینه نقطه زمان که توسط تقویم پشتیبانی می‌شود. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | آخرین سالی که می‌تواند توسط دو رقم نشان داده شود را دریافت می‌کند. |
| int [GetCelestialStem](../eastasianlunisolarcalendar/getcelestialstem/)(int) const | شاخهٔ آسمانی را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | روز ماه را برای نقطه زمان مشخص دریافت می‌کند. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | روز هفته را برای نقطه زمان مشخص دریافت می‌کند. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | روز سال را برای نقطه زمان مشخص دریافت می‌کند. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | تعداد روزهای یک ماه خاص را دریافت می‌کند. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | تعداد روزهای یک ماه خاص را دریافت می‌کند. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | تعداد روزهای یک ماه خاص را دریافت می‌کند. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | تعداد روزهای یک سال خاص را دریافت می‌کند. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | تعداد روزهای یک سال خاص را دریافت می‌کند. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | دوره مربوط به نقطه زمان مشخص را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌سازی اشیا سفارشی را فراهم می‌کند. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | ساعت‌ها را برای نقطه زمان مشخص دریافت می‌کند. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | ماه کبیسه را برای سال مشخص دریافت می‌کند. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | ماه کبیسه را برای سال مشخص دریافت می‌کند. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | ماه کبیسه را برای سال مشخص دریافت می‌کند. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | میلی‌ثانیه‌ها را برای نقطه زمان مشخص دریافت می‌کند. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | دقایق را برای نقطه زمان مشخص دریافت می‌کند. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | ماه را برای نقطه زمان مشخص دریافت می‌کند. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | تعداد ماه‌ها در سال مشخص را دریافت می‌کند. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | اطلاعات RTTI. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | اطلاعات RTTI. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | ثانیه‌ها را برای نقطه زمان مشخص دریافت می‌کند. |
| virtual int [GetSexagenaryYear](../eastasianlunisolarcalendar/getsexagenaryyear/)([DateTime](../../system/datetime/)) const | سال در چرخه شصت‌ساله را دریافت می‌کند. |
| int [GetTerrestrialBranch](../eastasianlunisolarcalendar/getterrestrialbranch/)(int) const | شاخهٔ زمینی را دریافت می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | هفتهٔ سال را برای نقطه زمان مشخص دریافت می‌کند. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | سال را برای نقطه زمان مشخص دریافت می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | بررسی می‌کند که آیا روز کبیسه است. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | بررسی می‌کند که آیا روز کبیسه است. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | بررسی می‌کند که آیا روز کبیسه است. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | بررسی می‌کند که آیا ماه کبیسه است. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | بررسی می‌کند که آیا ماه کبیسه است. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | بررسی می‌کند که آیا سال کبیسه است. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | بررسی می‌کند که آیا سال کبیسه است. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | بررسی می‌کند که آیا سال کبیسه است. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | مقادیر سال، ماه، روز و دوره را بررسی می‌کند. |
| void [Lock](../../system/object/lock/)() | قفل کردن با بیان C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | نسخهٔ فقط-خواندنی تقویم را دریافت می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیا را بر پایهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیا را بر پایهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع‌وار شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | آخرین سالی که می‌تواند توسط دو رقم نمایان شود را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان الگو nام را به weak pointer تنظیم می‌کند (به جای shared). امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از smart pointers یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از smart pointers یا ThisProtector استفاده کنید. |
| [TaiwanLunisolarCalendar](./taiwanlunisolarcalendar/)() | سازنده. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) را از اجزا می‌سازد. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) را از اجزا می‌سازد. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | سال را به سال چهاررقمی با استفاده از ویژگی TwoDigitYearMax تبدیل می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیا سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | عبارت C# typeof([System.Object](../../system/object/)) را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی بیان C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از smart pointers یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* فضای‌نام [System::Globalization](../)
* کتابخانه [Aspose.Slides](../../)