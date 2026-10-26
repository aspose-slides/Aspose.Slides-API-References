---
title: CultureInfo
second_title: مرجع API Aspose.Slides برای C++
description: "مجموعه‌ای از مقادیر و الگوریتم‌های مخصوص به فرهنگ. عملیات تنظیم فقط برای اشیائی که فقط-خواندنی نیستند فعال است. اشیای این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای ارسال به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 53
url: /fa/system.globalization/cultureinfo/
---
## CultureInfo کلاس

مجموعه‌ای از مقادیر و الگوریتم‌های مخصوص به فرهنگ. عملیات تنظیم فقط برای اشیائی که فقط-خواندنی نیستند فعال است. اشیای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای ارسال به توابع به‌عنوان آرگومان استفاده کنید.

```cpp
class CultureInfo : public virtual System::Object,
                    public System::IFormatProvider,
                    public System::ICloneable
```

## متدها

| Method | Description |
| --- | --- |
| void [ClearCachedData](./clearcacheddata/)() | اطلاعات کش‌شده فرهنگ را بازنشانی می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | اطلاعات فرهنگ را کلون می‌کند. |
| static [CultureInfoPtr](../cultureinfoptr/) [CreateSpecificCulture](./createspecificculture/)(const [String](../../system/string/)\&) | فرهنگی را بر اساس نام ایجاد می‌کند. |
| explicit  [CultureInfo](./cultureinfo/)(int) | اطلاعات RTTI. |
|  [CultureInfo](./cultureinfo/)(int, **bool**) | سازنده. |
| explicit  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&) | سازنده. |
|  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&, **bool**) | سازنده. |
|  [CultureInfo](./cultureinfo/)(std::nullptr_t) | همیشه ArgumentNullException را پرتاب می‌کند. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | اشیا را مقایسه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیا را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیا از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [CalendarPtr](../calendarptr/) [get_Calendar](./get_calendar/)() const | تقویمی که توسط فرهنگ استفاده می‌شود را دریافت می‌کند. |
| virtual [CompareInfoPtr](../compareinfoptr/) [get_CompareInfo](./get_compareinfo/)() const | مقایس‌گر رشته‌ای که مطابق با قوانین فرهنگ است را دریافت می‌کند. |
| [CultureTypes](../culturetypes/) [get_CultureTypes](./get_culturetypes/)() const | اتحاد بیتی انواع فرهنگ که فرهنگ جاری را توصیف می‌کند را دریافت می‌کند. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentCulture](./get_currentculture/)() | فرهنگی که برای رشتهٔ جاری تنظیم شده است را دریافت می‌کند. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentUICulture](./get_currentuiculture/)() | فرهنگ UI رشتهٔ جاری را دریافت می‌کند. |
| virtual [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_DateTimeFormat](./get_datetimeformat/)() const | اطلاعات قالب تاریخ را دریافت می‌کند. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentCulture](./get_defaultthreadcurrentculture/)() | فرهنگ پیش‌فرض در دامنهٔ برنامهٔ جاری را دریافت می‌کند. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentUICulture](./get_defaultthreadcurrentuiculture/)() | فرهنگ UI پیش‌فرض در دامنهٔ برنامهٔ جاری را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_DisplayName](./get_displayname/)() const | نام نمایشی فرهنگ را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_EnglishName](./get_englishname/)() const | نام انگلیسی فرهنگ را دریافت می‌کند. |
| [String](../../system/string/) [get_IetfLanguageTag](./get_ietflanguagetag/)() const | نام RFC 4646 برای یک زبان را دریافت می‌کند. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InstalledUICulture](./get_installeduiculture/)() | فرهنگی که با سیستم‌عامل نصب شده است را دریافت می‌کند. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InvariantCulture](./get_invariantculture/)() | فرهنگ ثابت را دریافت می‌کند. |
| virtual **bool** [get_IsNeutralCulture](./get_isneutralculture/)() const | بررسی می‌کند که آیا فرهنگ خنثی است یا نه. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | بررسی می‌کند که آیا شیء فرهنگ فقط‌خواندنی است یا نه. |
| virtual int [get_KeyboardLayoutId](./get_keyboardlayoutid/)() const | شناسهٔ محلور ورودی فعال را دریافت می‌کند. |
| virtual int [get_LCID](./get_lcid/)() const | شناسهٔ فرهنگ را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | نام فرهنگ را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_NativeName](./get_nativename/)() const | نام بومی فرهنگ را دریافت می‌کند. |
| virtual [NumberFormatInfoPtr](../numberformatinfoptr/) [get_NumberFormat](./get_numberformat/)() const | اطلاعات قالب عددی را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[CalendarPtr](../calendarptr/)\> [get_OptionalCalendars](./get_optionalcalendars/)() const | فهرست تقویم‌هایی که می‌توانند با این فرهنگ استفاده شوند. |
| virtual [CultureInfoPtr](../cultureinfoptr/) [get_Parent](./get_parent/)() const | فرهنگ والد را دریافت می‌کند. |
| virtual [TextInfoPtr](../textinfoptr/) [get_TextInfo](./get_textinfo/)() const | پارامترهای متنی مورد استفاده توسط فرهنگ را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_ThreeLetterISOLanguageName](./get_threeletterisolanguagename/)() const | کد سه‌حرفه‌ای ISO 639-2 زبان را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_ThreeLetterWindowsLanguageName](./get_threeletterwindowslanguagename/)() const | کد سه‌حرفه‌ای زبان همان‌طور که در API [Windows](../../system.windows/) تعریف شده، را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_TwoLetterISOLanguageName](./get_twoletterisolanguagename/)() const | نام دو حرفی ISO زبان مرتبط با فرهنگ را دریافت می‌کند. |
| **bool** [get_UseUserOverride](./get_useuseroverride/)() const | پرچمی را دریافت می‌کند که نشان می‌دهد آیا [CultureInfo](./) از تنظیمات فرهنگ انتخاب‌شده توسط کاربر استفاده می‌کند یا نه. |
| [CultureInfoPtr](../cultureinfoptr/) [GetConsoleFallbackUICulture](./getconsolefallbackuiculture/)() const | فرهنگ جایگزین مناسب برای برنامه‌های کنسولی را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&) | فرهنگ را بر اساس نام آن دریافت می‌کند. مشابه CreateSpecificCulture. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | فرهنگ را بر اساس نام آن دریافت می‌کند. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(**int32_t**) | فرهنگ را بر اساس شناسه دریافت می‌کند. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfoByIetfLanguageTag](./getcultureinfobyietflanguagetag/)(const [String](../../system/string/)\&) | منسوخ شده. شیء [CultureInfo](./) فقط‌خواندنی را بر اساس برچسب زبانی RFC 4646 مشخص شده دریافت می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<[CultureInfoPtr](../cultureinfoptr/)\> [GetCultures](./getcultures/)([CultureTypes](../culturetypes/)) | فرهنگ‌هایی که در نوع‌های مشخص شده قرار می‌گیرند را دریافت می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | شیء قالب برای نوع خاص را دریافت می‌کند. |
| int [GetHashCode](./gethashcode/)() const override | کد هش شیء را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوعی که targetType توصیف می‌کند است یا نه. معادل عملگر 'is' در C#. |
| **bool** [IsInherited](./isinherited/)() const | پرچم ارث‌بری را دریافت می‌کند. فقط برای استفاده داخلی. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌آورد. |
| [CultureInfo](./)\& [operator=](./operator_equal/)(const [CultureInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) |  |
| **bool** [operator==](./operator_equal_equal/)(const [CultureInfo](./)\&) const | پارامترهای فرهنگ را مقایسه می‌کند. |
| static [CultureInfoPtr](../cultureinfoptr/) [ReadOnly](./readonly/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | نسخهٔ فقط‌خواندنی فرهنگ را دریافت می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیا را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیا را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقداری را با nullptr از نظر ارجاع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص کاهش می‌دهد. |
| static void [set_CurrentCulture](./set_currentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | فرهنگ را برای رشتهٔ جاری تنظیم می‌کند. |
| static void [set_CurrentUICulture](./set_currentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | فرهنگ UI رشتهٔ جاری را تنظیم می‌کند. |
| virtual void [set_DateTimeFormat](./set_datetimeformat/)([DateTimeFormatInfoPtr](../datetimeformatinfoptr/)) | اطلاعات قالب تاریخ را تنظیم می‌کند. |
| static void [set_DefaultThreadCurrentCulture](./set_defaultthreadcurrentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | فرهنگ پیش‌فرض را در دامنهٔ برنامهٔ جاری تنظیم می‌کند. |
| static void [set_DefaultThreadCurrentUICulture](./set_defaultthreadcurrentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | فرهنگ UI پیش‌فرض را در دامنهٔ برنامهٔ جاری تنظیم می‌کند. |
| virtual void [set_NumberFormat](./set_numberformat/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | اطلاعات قالب عددی را دریافت می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../../system/string/) [ToString](./tostring/)() const override | فرهنگ را به رشته تبدیل می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری از عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [Object](../../system/object/)
* کلاس [IFormatProvider](../../system/iformatprovider/)
* کلاس [ICloneable](../../system/icloneable/)
* فضای‌نام [System::Globalization](../)
* کتابخانه [Aspose.Slides](../../)