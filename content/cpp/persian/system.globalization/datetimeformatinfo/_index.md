---
title: DateTimeFormatInfo
second_title: مرجع API Aspose.Slides برای C++
description: "مجموعه‌ای از پارامترهای قالب‌بندی تاریخ و زمان. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را در پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا خواهد شد. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بسط داده و از این اشاره‌گر برای عبور به عنوان آرگومان به توابع استفاده کنید."
type: docs
weight: 66
url: /fa/system.globalization/datetimeformatinfo/
---
## DateTimeFormatInfo کلاس

مجموعه‌ای از پارامترهای قالب‌بندی تاریخ و زمان. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را در پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا خواهد شد. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بسط داده و از این اشاره‌گر برای عبور به عنوان آرگومان به توابع استفاده کنید.

```cpp
class DateTimeFormatInfo : public virtual System::Object,
                           public System::IFormatProvider,
                           public System::ICloneable
```

## متدها

| متد | توضیحات |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | یک کپی از اطلاعات قالب را می‌سازد. |
| [DateTimeFormatInfo](./datetimeformatinfo/)() | سازنده پیش‌فرض، اطلاعات قالب نا‌متغیر را می‌سازد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از اصول [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ‌ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ‌ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedDayNames](./get_abbreviateddaynames/)() const | نام‌های کوتاه روزها را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthGenitiveNames](./get_abbreviatedmonthgenitivenames/)() const | نام‌های کوتاه ماه‌ها را در حالت ملکی دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthNames](./get_abbreviatedmonthnames/)() const | نام‌های کوتاه ماه‌ها را دریافت می‌کند. |
| [String](../../system/string/) [get_AMDesignator](./get_amdesignator/)() const | نماد صبح (AM) را دریافت می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\> [get_Calendar](./get_calendar/)() const | تقویم مرتبط با قالب‌ساز را دریافت می‌کند. |
| [CalendarWeekRule](../calendarweekrule/) [get_CalendarWeekRule](./get_calendarweekrule/)() const | قاعدهٔ هفتهٔ تقویم مرتبط با قالب‌ساز را دریافت می‌کند. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | قالب‌ساز تاریخ و زمان رشتهٔ کنونی را دریافت می‌کند. |
| [String](../../system/string/) [get_DateSeparator](./get_dateseparator/)() const | جداکنندهٔ تاریخ را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_DayNames](./get_daynames/)() const | نام‌های روزها را دریافت می‌کند. |
| [DayOfWeek](../../system/dayofweek/) [get_FirstDayOfWeek](./get_firstdayofweek/)() const | اولین روز هفته را دریافت می‌کند. |
| [String](../../system/string/) [get_FullDateTimePattern](./get_fulldatetimepattern/)() const | الگوی کامل تاریخ و زمان را دریافت می‌کند. |
| static const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | قالب‌ساز تاریخ و زمان ثابت را دریافت می‌کند. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | بررسی می‌کند که آیا قالب‌ساز فقط-خواندنی است یا نه. |
| [String](../../system/string/) [get_LongDatePattern](./get_longdatepattern/)() const | الگوی تاریخ طولانی را دریافت می‌کند. |
| [String](../../system/string/) [get_LongTimePattern](./get_longtimepattern/)() const | الگوی زمان طولانی را دریافت می‌کند. |
| [String](../../system/string/) [get_MonthDayPattern](./get_monthdaypattern/)() const | الگوی روز ماه را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthGenitiveNames](./get_monthgenitivenames/)() const | نام‌های ماه را در حالت ملکی دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthNames](./get_monthnames/)() const | نام‌های ماه را دریافت می‌کند. |
| [String](../../system/string/) [get_NativeCalendarName](./get_nativecalendarname/)() const | نام تقویم بومی را در صورت موجود بودن دریافت می‌کند. |
| [String](../../system/string/) [get_PMDesignator](./get_pmdesignator/)() const | نماد بعدازظهر (PM) را دریافت می‌کند. |
| [String](../../system/string/) [get_RFC1123Pattern](./get_rfc1123pattern/)() const | الگوی RFC1123 را دریافت می‌کند. |
| [String](../../system/string/) [get_ShortDatePattern](./get_shortdatepattern/)() const | الگوی تاریخ کوتاه را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_ShortestDayNames](./get_shortestdaynames/)() const | کمترین نام‌های روز ممکن را دریافت می‌کند. |
| [String](../../system/string/) [get_ShortTimePattern](./get_shorttimepattern/)() const | الگوی زمان کوتاه را دریافت می‌کند. |
| [String](../../system/string/) [get_SortableDateTimePattern](./get_sortabledatetimepattern/)() const | الگوی تاریخ و زمان قابل‌مرتب‌سازی را دریافت می‌کند. |
| [String](../../system/string/) [get_TimeSeparator](./get_timeseparator/)() const | جداکنندهٔ زمان را دریافت می‌کند. |
| [String](../../system/string/) [get_UniversalSortableDateTimePattern](./get_universalsortabledatetimepattern/)() const | الگوی تاریخ و زمان قابل‌مرتب‌سازی عمومی را دریافت می‌کند. |
| [String](../../system/string/) [get_YearMonthPattern](./get_yearmonthpattern/)() const | الگوی سال و ماه را دریافت می‌کند. |
| [String](../../system/string/) [GetAbbreviatedDayName](./getabbreviateddayname/)([DayOfWeek](../../system/dayofweek/)) const | نام کوتاه روز هفته را دریافت می‌کند. |
| [String](../../system/string/) [GetAbbreviatedEraName](./getabbreviatederaname/)(int) const | نام کوتاه دوره را دریافت می‌کند. |
| [String](../../system/string/) [GetAbbreviatedMonthName](./getabbreviatedmonthname/)(int) const | نام کوتاه ماه را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)() const | تمام الگوهایی را که مقادیر تاریخ و زمان می‌توانند در آن قالب‌بندی شوند دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)(char16_t) const | تمام الگوهایی را که مقادیر تاریخ و زمان می‌توانند با استفاده از رشتهٔ قالب مشخص قالب‌بندی شوند دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| [String](../../system/string/) [GetDayName](./getdayname/)([DayOfWeek](../../system/dayofweek/)) const | نام روز هفته را دریافت می‌کند. |
| int [GetEra](./getera/)(const [String](../../system/string/)\&) const | دوره را بر اساس نام دریافت می‌کند. |
| [String](../../system/string/) [GetEraName](./geteraname/)(int) const | نام دوره را دریافت می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | قالب‌ساز نوع خاصی را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | قالب‌ساز مرتبط با ارائه‌گر قالب را دریافت می‌کند. |
| [String](../../system/string/) [GetLeapYearMonthName](./getleapyearmonthname/)(int) const | نام ماه سال کبیسه را دریافت می‌کند. |
| [String](../../system/string/) [GetMonthGenitiveName](./getmonthgenitivename/)(int) const | نام ماه در حالت ملکی را دریافت می‌کند. |
| [String](../../system/string/) [GetMonthName](./getmonthname/)(int) const | نام ماه را دریافت می‌کند. |
| [String](../../system/string/) [GetShortestDayName](./getshortestdayname/)([DayOfWeek](../../system/dayofweek/)) const | کوتاه‌ترین نام برای روز هفتهٔ مشخص‌شده را دریافت می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است یا نه. معادل عملگر 'is' در C#. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان تکثیر انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [DateTimeFormatInfo](./)\& [operator=](./operator_equal/)(const [DateTimeFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر اختصاص. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [ReadOnly](./readonly/)(const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\&) | نسخهٔ فقط-خواندنی قالب‌ساز را دریافت می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr از لحاظ ارجاع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_AbbreviatedDayNames](./set_abbreviateddaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | نام‌های کوتاه روزها را تنظیم می‌کند. |
| void [set_AbbreviatedMonthGenitiveNames](./set_abbreviatedmonthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | نام‌های کوتاه ماه‌ها را در حالت ملکی تنظیم می‌کند. |
| void [set_AbbreviatedMonthNames](./set_abbreviatedmonthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | نام‌های کوتاه ماه‌ها را تنظیم می‌کند. |
| void [set_AMDesignator](./set_amdesignator/)(const [String](../../system/string/)\&) | نماد صبح (AM) را تنظیم می‌کند. |
| void [set_Calendar](./set_calendar/)(const [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\>\&) | تقویم مرتبط با قالب‌ساز را تنظیم می‌کند. |
| void [set_CalendarWeekRule](./set_calendarweekrule/)([CalendarWeekRule](../calendarweekrule/)) | قواعد هفتهٔ تقویم مرتبط با قالب‌ساز را تنظیم می‌کند. |
| void [set_DateSeparator](./set_dateseparator/)(const [String](../../system/string/)\&) | جداکنندهٔ تاریخ را تنظیم می‌کند. |
| void [set_DayNames](./set_daynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | نام‌های روزها را تنظیم می‌کند. |
| void [set_FirstDayOfWeek](./set_firstdayofweek/)([DayOfWeek](../../system/dayofweek/)) | اولین روز هفته را تنظیم می‌کند. |
| void [set_FullDateTimePattern](./set_fulldatetimepattern/)(const [String](../../system/string/)\&) | الگوی کامل تاریخ و زمان را تنظیم می‌کند. |
| void [set_LongDatePattern](./set_longdatepattern/)(const [String](../../system/string/)\&) | الگوی تاریخ طولانی را تنظیم می‌کند. |
| void [set_LongTimePattern](./set_longtimepattern/)(const [String](../../system/string/)\&) | الگوی زمان طولانی را تنظیم می‌کند. |
| void [set_MonthDayPattern](./set_monthdaypattern/)(const [String](../../system/string/)\&) | الگوی روز ماه را تنظیم می‌کند. |
| void [set_MonthGenitiveNames](./set_monthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | نام‌های ماه را در حالت ملکی تنظیم می‌کند. |
| void [set_MonthNames](./set_monthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | نام‌های ماه را تنظیم می‌کند. |
| void [set_PMDesignator](./set_pmdesignator/)(const [String](../../system/string/)\&) | نماد بعدازظهر (PM) را تنظیم می‌کند. |
| void [set_ShortDatePattern](./set_shortdatepattern/)(const [String](../../system/string/)\&) | الگوی تاریخ کوتاه را تنظیم می‌کند. |
| void [set_ShortestDayNames](./set_shortestdaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | کوتاه‌ترین نام‌های روز ممکن را تنظیم می‌کند. |
| void [set_ShortTimePattern](./set_shorttimepattern/)(const [String](../../system/string/)\&) | الگوی زمان کوتاه را تنظیم می‌کند. |
| void [set_TimeSeparator](./set_timeseparator/)(const [String](../../system/string/)\&) | جداکنندهٔ زمان را تنظیم می‌کند. |
| void [set_YearMonthPattern](./set_yearmonthpattern/)(const [String](../../system/string/)\&) | الگوی سال و ماه را تنظیم می‌کند. |
| void [SetAllDateTimePatterns](./setalldatetimepatterns/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, char16_t) | الگوها را برای قالب مشخص‌شده تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و بازمی‌گرداند. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری دستور lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [Object](../../system/object/)
* کلاس [IFormatProvider](../../system/iformatprovider/)
* کلاس [ICloneable](../../system/icloneable/)
* فضای‌نام [System::Globalization](../)
* کتابخانه [Aspose.Slides](../../)