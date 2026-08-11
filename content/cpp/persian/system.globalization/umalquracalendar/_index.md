---
title: UmAlQuraCalendar
second_title: Aspose.Slides برای مرجع API C++
description: "تقویم Um Al Qura. پیاده‌سازی نشده. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() اختصاص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از operator new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای ارسال به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 391
url: /fa/system.globalization/umalquracalendar/
---
## کلاس UmAlQuraCalendar

تقویم اُم القُرَة. پیاده‌سازی نشده است. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) اختصاص داده شوند. هرگز یک نمونه از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خرابی‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به‌عنوان آرگومان استفاده کنید.

```cpp
class UmAlQuraCalendar : public System::Globalization::Calendar
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | روزها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | ساعت‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | میلی‌ثانیه‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | دقایق را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | ماه‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | ثانیه‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | هفته‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | سال‌ها را به نقطه زمان اضافه می‌کند. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | اطلاعات RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | یک نسخه از شیء فعلی را ایجاد می‌کند و یک اشاره‌گر مشترک به آن باز می‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معناشناسی [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌عیاری سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌عیاری سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | نوع الگوریتم را دریافت می‌کند. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | اندیس دوران جاری را دریافت می‌کند. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | مقدار دوران جاری را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | فهرست دوران‌های موجود در تقویم را دریافت می‌کند. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | بررسی می‌کند که آیا تقویم فقط-خواندنی است یا نه. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | حداکثر نقطه زمانی که تقویم پشتیبانی می‌کند. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | حداقل نقطه زمانی که تقویم پشتیبانی می‌کند. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | آخرین سالی که می‌تواند با دو رقم نمایش داده شود را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | روز ماه را برای نقطه زمان مشخص‌شده دریافت می‌کند. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | روز هفته را برای نقطه زمان مشخص‌شده دریافت می‌کند. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | روز سال را برای نقطه زمان مشخص‌شده دریافت می‌کند. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | تعداد روزها در ماه مشخص را دریافت می‌کند. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | تعداد روزها در ماه مشخص را دریافت می‌کند. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | تعداد روزها در سال مشخص را دریافت می‌کند. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | تعداد روزها در سال مشخص را دریافت می‌کند. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | دوران را برای نقطه زمان مشخص‌شده دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | ساعات را برای نقطه زمان مشخص‌شده دریافت می‌کند. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | ماه کبیسه را برای سال مشخص‌شده دریافت می‌کند. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | اطلاعات RTTI. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | اطلاعات RTTI. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | میلی‌ثانیه‌ها را برای نقطه زمان مشخص‌شده دریافت می‌کند. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | دقایق را برای نقطه زمان مشخص‌شده دریافت می‌کند. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | ماه را برای نقطه زمان مشخص‌شده دریافت می‌کند. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | تعداد ماه‌ها در سال مشخص‌شده را دریافت می‌کند. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | تعداد ماه‌ها در سال مشخص‌شده را دریافت می‌کند. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | ثانیه‌ها را برای نقطه زمان مشخص‌شده دریافت می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | هفته سال را برای نقطه زمان مشخص‌شده دریافت می‌کند. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | سال را برای نقطه زمان مشخص‌شده دریافت می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | بررسی می‌کند که آیا روز کبیسه است. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | بررسی می‌کند که آیا روز کبیسه است. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | بررسی می‌کند که آیا روز کبیسه است. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | بررسی می‌کند که آیا ماه کبیسه است. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | بررسی می‌کند که آیا ماه کبیسه است. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | بررسی می‌کند که آیا ماه کبیسه است. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | بررسی می‌کند که آیا سال کبیسه است. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | بررسی می‌کند که آیا سال کبیسه است. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | بررسی می‌کند که آیا سال کبیسه است. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | مقادیر سال، ماه، روز و دوران را بررسی می‌کند. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | نسخه فقط-خواندنی تقویم را دریافت می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه ارجاعی شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده ارجاع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_TwoDigitYearMax](./set_twodigityearmax/)(int) override | آخرین سالی که می‌تواند با دو رقم نمایش داده شود را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده ارجاع مشترک را کاهش می‌دهد و مقدار آن را باز می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | شیء [DateTime](../../system/datetime/) را از اجزا ساخته می‌کند. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | شیء [DateTime](../../system/datetime/) را از اجزا ساخته می‌کند. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | سال را به سال چهاررقمی تبدیل می‌کند با استفاده از ویژگی TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | عبارت typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
|  [UmAlQuraCalendar](./umalquracalendar/)() | سازنده. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی با عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را حذف می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static constexpr [UmAlQuraEra](./umalquraera/) | دوران فعلی UmAlQura. |

## موارد مرتبط

* کلاس [Calendar](../calendar/)
* فضای‌نام [System::Globalization](../)
* کتابخانه [Aspose.Slides](../../)