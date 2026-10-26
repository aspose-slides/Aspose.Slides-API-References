---
title: NumberFormatInfo
second_title: "مرجع API Aspose.Slides برای C++"
description: "اطلاعاتی در مورد نحوه قالب‌بندی اعداد را نگه می‌دارد. عملیات تنظیم‌کننده فقط بر روی اشیائی که فقط-خواندنی نیستند فعال است. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات ادعا می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچانید و از این اشاره‌گر برای عبور به‌عنوان آرگومان به توابع استفاده کنید."
type: docs
weight: 248
url: /fa/system.globalization/numberformatinfo/
---
## کلاس NumberFormatInfo

اطلاعاتی در مورد نحوه قالب‌بندی اعداد را نگه می‌دارد. عملیات تنظیم‌کننده فقط بر روی اشیائی که فقط-خواندنی نیستند فعال است. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات ادعا می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچانید و از این اشاره‌گر برای عبور به‌عنوان آرگومان به توابع استفاده کنید.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## متدها

| متد | توضیح |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | یک نسخه کپی از اطلاعات قالب را ایجاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | تعداد رقم اعشار ارز را دریافت می‌کند. |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | جداساز اعشار ارز را دریافت می‌کند. |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | جداساز گروه ارز را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | تعداد رقم اعشار ارز در هر گروه را دریافت می‌کند. |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | الگو منفی ارز را دریافت می‌کند. |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | الگو مثبت ارز را دریافت می‌کند. |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | نماد ارز را دریافت می‌کند. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | اطلاعات قالب عددی تعریف‌شده توسط فرهنگ نخ جاری را دریافت می‌کند. |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | مقداری که نحوه نمایش شکل یک رقم را مشخص می‌کند، را دریافت می‌کند. |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | اطلاعات قالب عددی تعریف‌شده توسط فرهنگ ثابت را دریافت می‌کند. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | بررسی می‌کند که قالب فقط-خواندنی است یا نه. |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | نماد Not-a-Number را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | نمادهای اعداد (۰ تا ۹) را دریافت می‌کند. |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | نماد منفی بی‌نهایت را دریافت می‌کند. |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | علامت منفی را دریافت می‌کند. |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | تعداد رقم اعشار را دریافت می‌کند. |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | جداساز اعشار را دریافت می‌کند. |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | جداساز گروه اعداد را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | تعداد رقم‌ها در هر گروه را دریافت می‌کند. |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | الگوی منفی عدد را دریافت می‌کند. |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | تعداد مکان‌های اعشار در مقادیر درصد را دریافت می‌کند. |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | جداساز اعشار در مقادیر درصد را دریافت می‌کند. |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | جداساز گروه در مقادیر درصد را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | تعداد رقم‌ها در هر گروه مقدار درصد را دریافت می‌کند. |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | الگوی منفی درصد را دریافت می‌کند. |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | الگوی مثبت درصد را دریافت می‌کند. |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | نماد درصد را دریافت می‌کند. |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | نماد پرمیل را دریافت می‌کند. |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | نماد مثبت بی‌نهایت را دریافت می‌کند. |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | علامت مثبت را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | قالب‌بند نوع خاص را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. هش‌سازی اشیاء سفارشی را امکان‌پذیر می‌کند. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | قالب‌بند مرتبط با ارائه‌دهنده قالب را دریافت می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است یا خیر. معادل عملگر 'is' در C#. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| [NumberFormatInfo](./numberformatinfo/)() | سازنده پیش‌فرض ([NumberFormatInfo](./) ثابت). |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی در زیرکلاس‌ها را فراهم می‌کند. |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی در زیرکلاس‌ها را فراهم می‌کند. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | نسخه فقط-خواندنی قالب‌بند را دریافت می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را با مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | تعداد رقم اعشار ارز را تنظیم می‌کند. |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | جداساز اعشار ارز را تنظیم می‌کند. |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | جداساز گروه ارز را تنظیم می‌کند. |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | تعداد رقم اعشار ارز در هر گروه را تنظیم می‌کند. |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | الگوی منفی ارز را تنظیم می‌کند. |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | الگوی مثبت ارز را تنظیم می‌کند. |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | نماد ارز را تنظیم می‌کند. |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | مقداری که نحوه نمایش شکل یک رقم را مشخص می‌کند، تنظیم می‌کند. |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | نماد Not-a-Number را تنظیم می‌کند. |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | نمادهای اعداد (۰ تا ۹) را تنظیم می‌کند. |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | نماد منفی بی‌نهایت را تنظیم می‌کند. |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | علامت منفی را تنظیم می‌کند. |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | تعداد رقم اعشار را تنظیم می‌کند. |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | جداساز اعشار را تنظیم می‌کند. |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | جداساز گروه اعداد را تنظیم می‌کند. |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | تعداد رقم‌ها در هر گروه را تنظیم می‌کند. |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | الگوی منفی عدد را تنظیم می‌کند. |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | تعداد مکان‌های اعشار در مقادیر درصد را تنظیم می‌کند. |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | جداساز اعشار در مقادیر درصد را تنظیم می‌کند. |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | جداساز گروه در مقادیر درصد را تنظیم می‌کند. |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | تعداد رقم‌ها در هر گروه مقدار درصد را تنظیم می‌کند. |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | الگوی منفی درصد را تنظیم می‌کند. |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | الگوی مثبت درصد را تنظیم می‌کند. |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | نماد درصد را تنظیم می‌کند. |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | نماد پرمیل را تنظیم می‌کند. |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | نماد مثبت بی‌نهایت را تنظیم می‌کند. |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | علامت مثبت را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | استدلال nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مجموعه‌ها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [Object](../../system/object/)
* کلاس [IFormatProvider](../../system/iformatprovider/)
* کلاس [ICloneable](../../system/icloneable/)
* فضای‌نام [System::Globalization](../)
* کتابخانه [Aspose.Slides](../../)