---
title: TimeZoneInfo
second_title: Aspose.Slides برای C++ مرجع API
description: "اطلاعاتی که یک منطقهٔ زمانی خاص را توصیف می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() اختصاص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا شکست‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 1340
url: /fa/system/timezoneinfo/
---
## TimeZoneInfo کلاس

یک اطلاعات توصیف‌کنندهٔ منطقهٔ زمانی خاص را نمایندگی می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../makeobject/) اختصاص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../smartptr/) بسته کنید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید.

```cpp
class TimeZoneInfo : public System::IEquatable<TimeZoneInfoPtr>
```

## متدها

| متد | توضیح |
| --- | --- |
| static void [ClearCachedData](./clearcacheddata/)() | داده‌های کش شدهٔ منطقهٔ زمانی را پاک می‌کند. |
| static [DateTime](../datetime/) [ConvertTime](./converttime/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&, const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) زمان از یک منطقهٔ زمانی به منطقهٔ دیگری. |
| static [DateTimeOffset](../datetimeoffset/) [ConvertTime](./converttime/)(const [DateTimeOffset](../datetimeoffset/)\&, const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) زمان به زمان در یک منطقهٔ زمانی مشخص. |
| static [DateTime](../datetime/) [ConvertTime](./converttime/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) زمان به زمان در یک منطقهٔ زمانی مشخص. |
| static [DateTime](../datetime/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)([DateTime](../datetime/), const [String](../string/)\&) | [Convert](../convert/) زمان به زمان در یک منطقهٔ زمانی مشخص. |
| static [DateTimeOffset](../datetimeoffset/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)(const [DateTimeOffset](../datetimeoffset/)\&, const [String](../string/)\&) | [Convert](../convert/) زمان به زمان در یک منطقهٔ زمانی مشخص. |
| static [DateTime](../datetime/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)([DateTime](../datetime/), const [String](../string/)\&, const [String](../string/)\&) | [Convert](../convert/) زمان به زمان در یک منطقهٔ زمانی مشخص. |
| static [DateTime](../datetime/) [ConvertTimeFromUtc](./converttimefromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | زمان UTC را به زمان در یک منطقهٔ زمانی مشخص تبدیل می‌کند. |
| static [DateTime](../datetime/) [ConvertTimeToUtc](./converttimetoutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | زمان را به زمان UTC تبدیل می‌کند. |
| static [DateTime](../datetime/) [ConvertTimeToUtc](./converttimetoutc/)([DateTime](../datetime/)) | زمان را به زمان UTC تبدیل می‌کند. |
| static [DateTime](../datetime/) [ConvertTimeToUtcNoThrow](./converttimetoutcnothrow/)([DateTime](../datetime/)) | زمان را به زمان UTC تبدیل می‌کند. FOR INTERNAL USE. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&, const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\>\&, **bool**) | یک منطقهٔ زمانی سفارشی ایجاد می‌کند. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&, const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\>\&) | یک منطقهٔ زمانی سفارشی ایجاد می‌کند. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&) | یک منطقهٔ زمانی سفارشی ایجاد می‌کند. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override |  |
| **bool** [Equals](./equals/)([TimeZoneInfoPtr](../timezoneinfoptr/)) override | تعیین می‌کند آیا اشیاء جاری و مشخص شده برابر هستند. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | اشیا را با استفاده از معنای [Object.Equals](../object/equals/) زبان C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | اشیای نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [FindSystemTimeZoneById](./findsystemtimezonebyid/)(const [String](../string/)\&) | منطقهٔ زمانی با شناسهٔ مشخص را دریافت می‌کند. |
| [TimeSpan](../timespan/) [get_BaseUtcOffset](./get_baseutcoffset/)() const | یک نمونه از [TimeSpan](../timespan/) را برمی‌گرداند که بازهٔ زمانی بین زمان استاندارد منطقهٔ زمانی جاری و زمان UTC را نشان می‌دهد. |
| [String](../string/) [get_DaylightName](./get_daylightname/)() const | نام زمان صرفه‌جویی نوری منطقهٔ زمانی جاری را دریافت می‌کند. |
| [String](../string/) [get_DisplayName](./get_displayname/)() const | نام منطقهٔ زمانی جاری را دریافت می‌کند. |
| [String](../string/) [get_Id](./get_id/)() const | شناسهٔ منطقهٔ زمانی که توسط شیء جاری نمایندگی می‌شود را برمی‌گرداند. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [get_Local](./get_local/)() | یک نمونه از [TimeZoneInfo](./) را برمی‌گرداند که منطقهٔ زمانی محلی را نمایندگی می‌کند. |
| [String](../string/) [get_StandardName](./get_standardname/)() const | نام زمان استاندارد منطقهٔ زمانی جاری را دریافت می‌کند. |
| **bool** [get_SupportsDaylightSavingTime](./get_supportsdaylightsavingtime/)() const | پرچمی که نشان می‌دهد آیا منطقهٔ زمانی قوانین daylight saving time دارد را دریافت می‌کند. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [get_Utc](./get_utc/)() | یک نمونه از [TimeZoneInfo](./) را برمی‌گرداند که منطقهٔ زمانی UTC را نمایندگی می‌کند. |
| [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\> [GetAdjustmentRules](./getadjustmentrules/)() const | یک آرایه شامل اشیای **AdjustmentRule** را برمی‌گرداند که قوانین تنظیمی اعمال‌شده بر شیء [TimeZoneInfo](./) جاری را نمایندگی می‌کند. |
| [ArrayPtr](../arrayptr/)\<[TimeSpan](../timespan/)\> [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)([DateTime](../datetime/)) const | تاریخ‌ها و زمان‌های UTC را که یک تاریخ و زمان مشخص می‌تواند به آن‌ها نگاشته شود دریافت می‌کند. |
| [ArrayPtr](../arrayptr/)\<[TimeSpan](../timespan/)\> [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)(const [DateTimeOffset](../datetimeoffset/)\&) const | تاریخ‌ها و زمان‌های UTC را که یک تاریخ و زمان مشخص می‌تواند به آن‌ها نگاشته شود دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| int [GetHashCode](./gethashcode/)() const override | معادل متد [Object.GetHashCode()](../object/gethashcode/) زبان C#. امکان هش‌گذاری اشیای سفارشی را فراهم می‌کند. |
| static [SharedPtr](../sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[TimeZoneInfoPtr](../timezoneinfoptr/)\>\> [GetSystemTimeZones](./getsystemtimezones/)() | مجموعهٔ مرتب‌شده‌ای از تمام منطقه‌های زمانی موجود در سیستم محلی را دریافت می‌کند. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../object/gettype/) در C#. |
| [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)([DateTime](../datetime/)) const | اختلاف بین زمان در این منطقهٔ زمانی و زمان UTC را برای تاریخ و زمان مشخص محاسبه می‌کند. |
| [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)(const [DateTimeOffset](../datetimeoffset/)\&) const | اختلاف بین زمان در این منطقهٔ زمانی و زمان UTC را برای تاریخ و زمان مشخص محاسبه می‌کند. |
| static [TimeSpan](../timespan/) [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | تابع کمکی داخلی که افست UTC را برای تاریخ-زمان UTC در یک منطقهٔ زمانی مشخص برمی‌گرداند. FOR INTERNAL USE. |
| static [TimeSpan](../timespan/) [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&, **bool**\&, **bool**\&) | تابع کمکی داخلی که افست UTC را برای تاریخ-زمان UTC در یک منطقهٔ زمانی مشخص برمی‌گرداند. FOR INTERNAL USE. |
| [TimeSpan](../timespan/) [GetUtcOffsetNoThrow](./getutcoffsetnothrow/)([DateTime](../datetime/)) const | اختلاف بین زمان در این منطقهٔ زمانی و زمان UTC را برای تاریخ و زمان مشخص محاسبه می‌کند. FOR INTERNAL USE. |
| **bool** [HasSameRules](./hassamerules/)(const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) const | بررسی می‌کند آیا منطقه‌های زمانی جاری و دیگری همان قوانین تنظیمی را دارند. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| **bool** [IsAmbiguousTime](./isambiguoustime/)([DateTime](../datetime/)) const | بررسی می‌کند آیا تاریخ و زمان مشخص مبهم است و می‌تواند به چندین زمان UTC نگاشته شود. |
| **bool** [IsAmbiguousTime](./isambiguoustime/)(const [DateTimeOffset](../datetimeoffset/)\&) const | بررسی می‌کند آیا تاریخ و زمان مشخص مبهم است و می‌تواند به چندین زمان UTC نگاشته شود. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)([DateTime](../datetime/)) const | بررسی می‌کند آیا تاریخ و زمان مشخص در بازهٔ daylight saving time قرار دارد. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)(const [DateTimeOffset](../datetimeoffset/)\&) const | بررسی می‌کند آیا تاریخ و زمان مشخص در بازهٔ daylight saving time قرار دارد. |
| **bool** [IsDaylightSavingTimeNoThrow](./isdaylightsavingtimenothrow/)([DateTime](../datetime/)) const | بررسی می‌کند آیا تاریخ و زمان مشخص در بازهٔ daylight saving time قرار دارد. |
| **bool** [IsInvalidTime](./isinvalidtime/)([DateTime](../datetime/)) const | بررسی می‌کند آیا تاریخ و زمان مشخص نامعتبر است. |
| void [Lock](../object/lock/)() | اجرای قفل‌گذاری دستور lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء [LockContext](../lockcontext/) استفاده کنید. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../object/memberwiseclone/) در C#. امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../object/object/)([Object](../object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از زیربنای‌ها را فراهم می‌سازد. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از زیربنای‌ها را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | اشیا را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | اشیا را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را با مقدار مشخص کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../string/) [ToString](./tostring/)() const override | معادل متد [Object.ToString()](../object/tostring/) در C#. امکان تبدیل اشیای سفارشی به رشته را فراهم می‌کند. |
| static [DateTime](../datetime/) [TransitionTimeToDateTime](./transitiontimetodatetime/)(**int32_t**, const **TransitionTime**\&) | تابع کمکی که سال و **TransitionTime** را به یک [DateTime](../datetime/) تبدیل می‌کند. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ساختار typeof([System.Object](../object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../object/unlock/)() | اجرای باز کردن قفل دستور lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء [LockContext](../lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [AdjustmentRulePtr](./adjustmentruleptr/) | یک نام مستعار برای یک اشاره‌گر مشترک به یک نمونه از کلاس **AdjustmentRule** است. |

## همچنین ببینید

* کلاس [IEquatable](../iequatable/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)