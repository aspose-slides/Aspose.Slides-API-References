---
title: JapaneseLunisolarCalendar
second_title: مرجع API Aspose.Slides برای C++
description: "تقویم خورشیدی-قمری ژاپنی. پیاده‌سازی نشده. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 196
url: /fa/system.globalization/japaneselunisolarcalendar/
---
## کلاس JapaneseLunisolarCalendar

تقویم خورشیدی-قمری ژاپنی. پیاده‌سازی نشده. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکال‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید.

```cpp
class JapaneseLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## متدها

| Method | Description |
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
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | یک کپی از شیء فعلی ایجاد می‌کند و اشاره‌گر اشتراکی به آن باز می‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسه نقاط اعشاری به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسه نقاط اعشاری به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](../eastasianlunisolarcalendar/get_algorithmtype/)() const override | اطلاعات RTTI. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | شاخص دوران کنونی را دریافت می‌کند. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | مقدار دوران کنونی را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | فهرست دوران‌های موجود در تقویم را دریافت می‌کند. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | بررسی می‌کند که آیا تقویم فقط خواندنی است یا خیر. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | بیشینه نقطه زمانی که تقویم از آن پشتیبانی می‌کند. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | حداقل نقطه زمانی که تقویم از آن پشتیبانی می‌کند. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | آخرین سالی که می‌توان با دو رقم نشان داد را دریافت می‌کند. |
| int [GetCelestialStem](../eastasianlunisolarcalendar/getcelestialstem/)(int) const | شاخه آسمانی را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | روز ماه را برای نقطه زمان مشخص دریافت می‌کند. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | روز هفته را برای نقطه زمان مشخص دریافت می‌کند. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | روز سال را برای نقطه زمان مشخص دریافت می‌کند. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | تعداد روزهای ماه خاص را دریافت می‌کند. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | تعداد روزهای ماه خاص را دریافت می‌کند. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | تعداد روزهای سال خاص را دریافت می‌کند. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | تعداد روزهای سال خاص را دریافت می‌کند. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | دوران را برای نقطه زمان مشخص دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان تولید هش برای اشیاء سفارشی را فراهم می‌کند. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | ساعت‌ها را برای نقطه زمان مشخص دریافت می‌کند. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | ماه کبیسه را برای سال مشخص دریافت می‌کند. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | اطلاعات RTTI. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | اطلاعات RTTI. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | میلی‌ثانیه‌ها را برای نقطه زمان مشخص دریافت می‌کند. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | دقیقه‌ها را برای نقطه زمان مشخص دریافت می‌کند. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | ماه را برای نقطه زمان مشخص دریافت می‌کند. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | تعداد ماه‌های سال مشخص را دریافت می‌کند. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | تعداد ماه‌های سال مشخص را دریافت می‌کند. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | ثانیه‌ها را برای نقطه زمان مشخص دریافت می‌کند. |
| virtual int [GetSexagenaryYear](../eastasianlunisolarcalendar/getsexagenaryyear/)([DateTime](../../system/datetime/)) const | سال را در چرخه شصت‌ساله دریافت می‌کند. |
| int [GetTerrestrialBranch](../eastasianlunisolarcalendar/getterrestrialbranch/)(int) const | شاخه زمینی را دریافت می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | هفته از سال را برای نقطه زمان مشخص دریافت می‌کند. |
| int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const override | سال را برای نقطه زمان مشخص دریافت می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | بررسی می‌کند که روز کبیسه است یا خیر. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | بررسی می‌کند که روز کبیسه است یا خیر. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | بررسی می‌کند که روز کبیسه است یا خیر. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | بررسی می‌کند که ماه کبیسه است یا خیر. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | بررسی می‌کند که ماه کبیسه است یا خیر. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | بررسی می‌کند که سال کبیسه است یا خیر. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | بررسی می‌کند که سال کبیسه است یا خیر. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | بررسی می‌کند که سال کبیسه است یا خیر. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | مقادیر سال، ماه، روز و دوران را بررسی می‌کند. |
|  [JapaneseLunisolarCalendar](./japaneselunisolarcalendar/)() | سازنده. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء ایجاد می‌کند. همه ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | نسخه فقط خواندنی تقویم را دریافت می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع برای شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژه [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژه [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع اشتراکی را به مقدار مشخص کاهش می‌دهد. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | آخرین سالی که می‌توان با دو رقم نشان داد را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع اشتراکی را افزایش می‌دهد. نباید مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع اشتراکی را کاهش می‌دهد و باز می‌گرداند. نباید مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | شیء [DateTime](../../system/datetime/) را از اجزاء می‌سازد. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | شیء [DateTime](../../system/datetime/) را از اجزاء می‌سازد. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | سال را به سال چهار رقمی با استفاده از ویژگی TwoDigitYearMax تبدیل می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | عبارت C# typeof([System.Object](../../system/object/)) را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری عبارت C# lock() را باز می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را حذف می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## فیلدها

| Field | Description |
| --- | --- |
| static constexpr [JapaneseEra](./japaneseera/) | دوران فعلی ژاپنی. |

## مراجع

* کلاس [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* فضای نام [System::Globalization](../)
* کتابخانه [Aspose.Slides](../../)