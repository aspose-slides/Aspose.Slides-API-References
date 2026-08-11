---
title: KoreanCalendar
second_title: مرجع API Aspose.Slides برای C++
description: "تقویم کره‌ای. اشیای این کلاس باید تنها با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را بر روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 222
url: /fa/system.globalization/koreancalendar/
---
## کلاس KoreanCalendar

تقویم کره‌ای. اشیای این کلاس باید تنها با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا باعث خطاهای زمان اجرا و/یا خطاهای ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای پاس دادن به توابع به عنوان آرگومان استفاده کنید.

```cpp
class KoreanCalendar : public System::Globalization::Calendar
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | روزها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | ساعات را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | میلی‌ثانیه‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | دقیقّه‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | ماه‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | ثانیه‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | هفته‌ها را به نقطه زمان اضافه می‌کند. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | سال‌ها را به نقطه زمان اضافه می‌کند. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | اطلاعات RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | یک نسخهٔ از شیء فعلی ایجاد می‌کند و یک اشاره‌گر مشترک به آن بر می‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | نوع الگوریتم را به دست می‌آورد. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | اندیس دورهٔ فعلی را می‌گیرد. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | مقدار دورهٔ فعلی را می‌گیرد. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | فهرست دوره‌های موجود در تقویم را می‌گیرد. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | بررسی می‌کند که آیا تقویم فقط-خواندنی است یا خیر. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | حداکثر نقطه زمانی که توسط تقویم پشتیبانی می‌شود. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | حداقل نقطه زمانی که توسط تقویم پشتیبانی می‌شود. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | آخرین سالی که می‌تواند با دو رقم نمایش داده شود را می‌گیرد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را می‌گیرد. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | روز ماه را برای نقطه زمانی مشخص شده می‌گیرد. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | روز هفته را برای نقطه زمانی مشخص شده می‌گیرد. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | روز سال را برای نقطه زمانی مشخص شده می‌گیرد. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | تعداد روزهای ماه خاص را می‌گیرد. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | تعداد روزهای ماه خاص را می‌گیرد. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | تعداد روزهای ماه خاص را می‌گیرد. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | تعداد روزهای سال خاص را می‌گیرد. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | تعداد روزهای سال خاص را می‌گیرد. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | تعداد روزهای سال خاص را می‌گیرد. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | دوره را برای نقطه زمانی مشخص شده می‌گیرد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان hashing اشیاء سفارشی را فراهم می‌کند. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | ساعت‌ها را برای نقطه زمانی مشخص شده می‌گیرد. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | ماه کبیسه را برای سال مشخص شده می‌گیرد. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | ماه کبیسه را برای سال مشخص شده می‌گیرد. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | ماه کبیسه را برای سال مشخص شده می‌گیرد. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | میلی‌ثانیه‌ها را برای نقطه زمانی مشخص شده می‌گیرد. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | دقیقّه‌ها را برای نقطه زمانی مشخص شده می‌گیرد. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | ماه را برای نقطه زمانی مشخص شده می‌گیرد. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | تعداد ماه‌ها در سال مشخص شده را می‌گیرد. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | اطلاعات RTTI. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | اطلاعات RTTI. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | ثانیه‌ها را برای نقطه زمانی مشخص شده می‌گیرد. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را می‌گیرد. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | هفتهٔ سال را برای نقطه زمانی مشخص شده می‌گیرد. |
| int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const override | سال را برای نقطه زمانی مشخص شده می‌گیرد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | بررسی می‌کند که آیا روز کبیسه است. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | بررسی می‌کند که آیا روز کبیسه است. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | بررسی می‌کند که آیا روز کبیسه است. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | بررسی می‌کند که آیا ماه کبیسه است. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | بررسی می‌کند که آیا ماه کبیسه است. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | بررسی می‌کند که آیا ماه کبیسه است. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | بررسی می‌کند که آیا سال کبیسه است. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | بررسی می‌کند که آیا سال کبیسه است. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | بررسی می‌کند که آیا سال کبیسه است. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | مقدارهای سال، ماه، روز و دوره را بررسی می‌کند. |
|  [KoreanCalendar](./koreancalendar/)() | سازنده. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌کردن توسط دستور C# lock(). مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای کلاس‌های مشتق را فراهم می‌کند. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای کلاس‌های مشتق را فراهم می‌کند. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | نسخهٔ فقط-خواندنی تقویم را می‌گیرد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | آخرین سالی که می‌تواند با دو رقم نمایش داده شود را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را می‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و بر می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | [DateTime](../../system/datetime/) را از اجزاء می‌سازد. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) را از اجزاء می‌سازد. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) را از اجزاء می‌سازد. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | سال را با استفاده از ویژگی TwoDigitYearMax به سال چهار رقم تبدیل می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازهٔ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی بازقفل‌کردن توسط دستور C# lock(). مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static constexpr [KoreanEra](./koreanera/) | دورهٔ فعلی کره‌ای. |

## موارد مرتبط

* کلاس [Calendar](../calendar/)
* فضای نام [System::Globalization](../)
* کتابخانه [Aspose.Slides](../../)