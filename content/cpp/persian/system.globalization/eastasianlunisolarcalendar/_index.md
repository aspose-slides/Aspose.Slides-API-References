---
title: EastAsianLunisolarCalendar
second_title: Aspose.Slides برای مرجع API C++
description: "تقویم هجری خورشیدی شرق آسیا. اشیای این کلاس باید فقط با استفاده از تابع System::MakeObject() اختصاص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای صحت‌سنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای پاس دادن به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 105
url: /fa/system.globalization/eastasianlunisolarcalendar/
---
## EastAsianLunisolarCalendar کلاس

تقویم خورشیدی-ماه‌گی شرق-آسیا. اشیای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های ادعا می‌شود. همواره این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای ارسال به توابع به‌عنوان آرگومان استفاده کنید.

```cpp
class EastAsianLunisolarCalendar : public System::Globalization::Calendar
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | روزها را به نقطه زمانی اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | ساعات را به نقطه زمانی اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | میلی‌ثانیه‌ها را به نقطه زمانی اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | دقایق را به نقطه زمانی اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | ماه‌ها را به نقطه زمانی اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | ثانیه‌ها را به نقطه زمانی اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | هفته‌ها را به نقطه زمانی اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | سال‌ها را به نقطه زمانی اضافه می‌کند. |
| [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | اطلاعات RTTI. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | یک کپی از شیء جاری ایجاد می‌کند و یک اشاره‌گر اشتراکی به آن بازمی‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از مفاهیم [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | اطلاعات RTTI. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | شاخص دورهٔ فعلی را دریافت می‌کند. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | مقدار دورهٔ فعلی را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](../calendar/get_eras/)() const | فهرست دوره‌های موجود در تقویم را دریافت می‌کند. |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](../calendar/get_id/)() const | شناسهٔ تقویم را دریافت می‌کند. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | بررسی می‌کند که آیا تقویم فقط-خواندنی است یا نه. |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](../calendar/get_maxsupporteddatetime/)() const | حداکثر نقطه زمانی که توسط تقویم پشتیبانی می‌شود. |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](../calendar/get_minsupporteddatetime/)() const | حداقل نقطه زمانی که توسط تقویم پشتیبانی می‌شود. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | آخرین سالی که می‌تواند با دو رقم نشان داده شود را دریافت می‌کند. |
| int [GetCelestialStem](./getcelestialstem/)(int) const | ساقهٔ آسمانی را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارشگر مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | روز ماه برای نقطه زمانی مشخص‌شده را دریافت می‌کند. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | روز هفته برای نقطه زمانی مشخص‌شده را دریافت می‌کند. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | روز سال برای نقطه زمانی مشخص‌شده را دریافت می‌کند. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | تعداد روزهای یک ماه خاص را دریافت می‌کند. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | تعداد روزهای یک ماه خاص را دریافت می‌کند. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | تعداد روزهای یک سال خاص را دریافت می‌کند. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | تعداد روزهای یک سال خاص را دریافت می‌کند. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | دورهٔ مربوط به نقطه زمانی مشخص‌شده را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# . امکان هش‌گذاری اشیای سفارشی را فراهم می‌کند. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | ساعات برای نقطه زمانی مشخص‌شده را دریافت می‌کند. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int) const | ماه کبیسه برای سال مشخص‌شده را دریافت می‌کند. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int, int) const | ماه کبیسه برای سال مشخص‌شده را دریافت می‌کند. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | میلی‌ثانیه‌ها برای نقطه زمانی مشخص‌شده را دریافت می‌کند. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | دقایق برای نقطه زمانی مشخص‌شده را دریافت می‌کند. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | ماه برای نقطه زمانی مشخص‌شده را دریافت می‌کند. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | تعداد ماه‌های سال مشخص‌شده را دریافت می‌کند. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | تعداد ماه‌های سال مشخص‌شده را دریافت می‌کند. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | ثانیه‌ها برای نقطه زمانی مشخص‌شده را دریافت می‌کند. |
| virtual int [GetSexagenaryYear](./getsexagenaryyear/)([DateTime](../../system/datetime/)) const | سال در چرخه شصت‌ساله را دریافت می‌کند. |
| int [GetTerrestrialBranch](./getterrestrialbranch/)(int) const | شاخهٔ زمینی را دریافت می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | هفتهٔ سال برای نقطه زمانی مشخص‌شده را دریافت می‌کند. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | سال برای نقطه زمانی مشخص‌شده را دریافت می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده. معادل عملگر 'is' در C#. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int) const | بررسی می‌کند که آیا روز کبیسه است. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int, int) const | بررسی می‌کند که آیا روز کبیسه است. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | بررسی می‌کند که آیا ماه کبیسه است. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | بررسی می‌کند که آیا ماه کبیسه است. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int) const | بررسی می‌کند که آیا سال کبیسه است. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int, int) const | بررسی می‌کند که آیا سال کبیسه است. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | مقدارهای سال، ماه، روز و دوره را بررسی می‌کند. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری با عبارت lock() در C# را پیاده‌سازی می‌کند. به‌طور مستقیم فراخوانی کنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت زیرکلاس‌ها از طریق کپی را فراهم می‌کند. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت زیرکلاس‌ها از طریق کپی را فراهم می‌کند. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | نسخهٔ فقط-خواندنی تقویم را دریافت می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را براساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را براساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | اشیاء نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد اشارت‌های اشتراکی را به مقدار مشخص کاهش می‌دهد. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | آخرین سالی که می‌تواند با دو رقم نمایان شود را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارشگر اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارشگر اشتراکی را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارشگر اشتراکی را کاهش داده و بازمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | شیء [DateTime](../../system/datetime/) را از اجزا می‌سازد. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | شیء [DateTime](../../system/datetime/) را از اجزا می‌سازد. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | سال را به سال چهار رقمی با استفاده از ویژگی TwoDigitYearMax تبدیل می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیای سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازقفل‌گذاری با عبارت lock() در C# را پیاده‌سازی می‌کند. به‌طور مستقیم فراخوانی کنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارشگر ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارشگر ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [Calendar](../calendar/)
* فضای‌نام [System::Globalization](../)
* کتابخانه [Aspose.Slides](../../)