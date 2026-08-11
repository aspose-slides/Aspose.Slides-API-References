---
title: MathMatrix
second_title: مرجع API Aspose.Slides برای C++
description: شیء Matrix را مشخص می‌کند که از عناصر فرزند تشکیل شده‌اند که در یک یا چند ردیف و ستون چینیده‌اند. باید توجه داشت که ماتریس‌ها جداکننده‌های داخلی ندارند. برای قرار دادن ماتریس در براکت‌ها باید از شیء delimiter (IMathDelimiter) استفاده کنید. آرگومان‌های null می‌توانند برای ایجاد فواصل در ماتریس‌ها استفاده شوند.
type: docs
weight: 950
url: /fa/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix کلاس

شیء Matrix را مشخص می‌کند که از عناصر فرزند تشکیل شده‌اند که در یک یا چند ردیف و ستون چیده شده‌اند. باید توجه داشته باشید که ماتریس‌ها جداکننده‌های داخلی ندارند. برای قرار دادن ماتریس در براکت‌ها باید از شیء delimiter ([IMathDelimiter](../imathdelimiter/)) استفاده کنید. آرگومان‌های null می‌توانند برای ایجاد فواصل در ماتریس‌ها استفاده شوند.

```cpp
class MathMatrix : public Aspose::Slides::MathText::MathElementBase,
                   public Aspose::Slides::MathText::IMathMatrix,
                   public Aspose::Slides::MathText::IHasControlCharacterProperties
```

## متدها

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../mathelementbase/accent/)(char16_t) override | یک علامت ارتقا (کاراکتری در بالای این عنصر) را تنظیم می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | توابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::String](../../system/string/)) override | توابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) override | توابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | توابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافی مشخص‌شده می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) override | توابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافی مشخص‌شده می‌گیرد |
| void [DeleteColumn](./deletecolumn/)(**int32_t**) override | ستون مشخص‌شده را حذف می‌کند |
| void [DeleteRow](./deleterow/)(**int32_t**) override | سطر مشخص‌شده را حذف می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | کسر با صورت این و مخرج مشخص‌شده ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/)) override | کسر با صورت این و مخرج مشخص‌شده ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) override | کسر از نوع مشخص‌شده با صورت این و مخرج مشخص‌شده ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) override | کسر از نوع مشخص‌شده با صورت این و مخرج مشخص‌شده ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)() override | یک عنصر ریاضی را در پرانتز می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)(char16_t, char16_t) override | یک عنصر ریاضی را در کاراکترهای مشخص‌شده مانند پرانتز یا سایر کاراکترها به عنوان چارچوب می‌گیرد |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | یک تابع از یک آرگومان را با استفاده از این نمونه به عنوان نام تابع می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::String](../../system/string/)) override | یک تابع از یک آرگومان را با استفاده از این نمونه به عنوان نام تابع می‌گیرد |
| [MathVerticalAlignment](../mathverticalalignment/) [get_BaseJustification](./get_basejustification/)() override | تراز عمودی نسبت به متن اطراف را مشخص می‌کند. مقادیر ممکن بالا، پایین و مرکز هستند. پیش‌فرض: مرکز |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | تعداد ستون‌ها در ماتریس |
| **uint32_t** [get_ColumnGap](./get_columngap/)() override | مقدار فاصله افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule روی 3 (\"Exactly\") تنظیم شده باشد، واحد به صورت تویپ (1/20 نقطه) تفسیر می‌شود. اگر ColumnGapRule روی 4 (\"Multiple\") تنظیم شده باشد، واحد به صورت تعداد افزایشی 0.5 ام تفسیر می‌شود. در سایر موارد نادیده گرفته می‌شود. پیش‌فرض: 0 |
| [MathSpacingRules](../mathspacingrules/) [get_ColumnGapRule](./get_columngaprule/)() override | نوع فاصله افقی بین ستون‌های یک ماتریس؛ واحدهای فاصله افقی می‌توانند em یا point باشند (به صورت تویپ ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0) |
| **bool** [get_HidePlaceholders](./get_hideplaceholders/)() override | مخفی کردن مکان‌گیرهای عناصر خالی ماتریس پیش‌فرض: false |
| **uint32_t** [get_MinColumnWidth](./get_mincolumnwidth/)() override | حداقل عرض ستون به تویپ (1/20 نقطه). فاصله شکاف (که به عنوان \"Column Gap\" یا \"Gap Width\" نیز شناخته می‌شود) به MinColumnWidth اضافه می‌شود تا کل فاصله Matrix [Column](../../aspose.slides/column/) (فاصله بین لبه‌های مشابه ستون‌های مختلف) را تعیین کند. پیش‌فرض: 0. |
| **int32_t** [get_RowCount](./get_rowcount/)() override | تعداد سطرها در ماتریس |
| **uint32_t** [get_RowGap](./get_rowgap/)() override | مقدار فاصله عمودی بین سطرهای یک ماتریس؛ اگر RowGapRule روی 3 (\"Exactly\") تنظیم شده باشد، واحد به صورت تویپ (1/20 نقطه) تفسیر می‌شود. اگر RowGapRule روی 4 (\"Multiple\") تنظیم شده باشد، واحد به صورت نیم‌خط‌ها تفسیر می‌شود. پیش‌فرض: 0 |
| [MathSpacingRules](../mathspacingrules/) [get_RowGapRule](./get_rowgaprule/)() override | نوع فاصله عمودی بین سطرهای یک ماتریس؛ واحدهای فاصله عمودی می‌توانند خطوط یا نقاط (به صورت تویپ) باشند. پیش‌فرض: SingleSpacingGap (0) |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](./getchildren/)() override | دریافت عناصر فرزند |
| [MathHorizontalAlignment](../mathhorizontalalignment/) [GetColumnAlignment](./getcolumnalignment/)(**int32_t**) override | دریافت تراز افقی ستون مشخص‌شده |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)() override | این عنصر را با استفاده از یک کروشهٔ پایین در یک گروه قرار می‌دهد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) override | این عنصر را با استفاده از یک کاراکتر گروه‌بند مانند کروشهٔ پایین یا دیگری در یک گروه قرار می‌دهد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) override | عنصر ماتریس |
| void [idx_set](./idx_set/)(**int32_t**, **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | عنصر ماتریس |
| void [InsertColumnAfter](./insertcolumnafter/)(**int32_t**) override | افزودن یک ستون جدید پس از ستون مشخص‌شده؛ در ابتدا همه عناصر ستون جدید null هستند. |
| void [InsertColumnBefore](./insertcolumnbefore/)(**int32_t**) override | افزودن یک ستون جدید قبل از ستون مشخص‌شده؛ در ابتدا همه عناصر ستون جدید null هستند. |
| void [InsertRowAfter](./insertrowafter/)(**int32_t**) override | افزودن یک سطر جدید پس از سطر مشخص‌شده؛ در ابتدا همه عناصر سطر جدید null هستند. |
| void [InsertRowBefore](./insertrowbefore/)(**int32_t**) override | افزودن یک سطر جدید قبل از سطر مشخص‌شده؛ در ابتدا همه عناصر سطر جدید null هستند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) override | انتگرال را می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | انتگرال را می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/)) override | انتگرال را بدون حد‌ها می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) override | انتگرال را می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | انتگرال را می‌گیرد |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه عملگر C# 'is'. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | یک عنصر ریاضی را ترکیب کرده و بلوک ریاضی ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::String](../../system/string/)) override | متن ریاضی را ترکیب کرده و بلوک ریاضی ایجاد می‌کند |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی عبارت C# lock() برای قفل‌گذاری. مستقیم فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
|  [MathMatrix](./mathmatrix/)(**int32_t**, **int32_t**) | یک نمونه جدید از کلاس [MathMatrix](./) را مقداردهی اولیه می‌کند. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان شبیه‌سازی انواع سفارشی را فراهم می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | یک عملگر N-ary ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | یک عملگر N-ary ایجاد می‌کند |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../mathelementbase/overbar/)() override | میله‌ای در بالای این عنصر تنظیم می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | ریشه ریاضی از درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::String](../../system/string/)) override | ریشه ریاضی از درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارش مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_BaseJustification](./set_basejustification/)([MathVerticalAlignment](../mathverticalalignment/)) override | تراز عمودی نسبت به متن اطراف را مشخص می‌کند. مقادیر ممکن بالا، پایین و مرکز هستند. پیش‌فرض: مرکز |
| void [set_ColumnGap](./set_columngap/)(**uint32_t**) override | مقدار فاصله افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule روی 3 (\"Exactly\") تنظیم شده باشد، واحد به صورت تویپ (1/20 نقطه) تفسیر می‌شود. اگر ColumnGapRule روی 4 (\"Multiple\") تنظیم شده باشد، واحد به صورت تعداد افزایشی 0.5 ام تفسیر می‌شود. در سایر موارد نادیده گرفته می‌شود. پیش‌فرض: 0 |
| void [set_ColumnGapRule](./set_columngaprule/)([MathSpacingRules](../mathspacingrules/)) override | نوع فاصله افقی بین ستون‌های یک ماتریس؛ واحدهای فاصله افقی می‌توانند em یا point باشند (به صورت تویپ ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0) |
| void [set_HidePlaceholders](./set_hideplaceholders/)(**bool**) override | مخفی کردن مکان‌گیرهای عناصر خالی ماتریس پیش‌فرض: false |
| void [set_MinColumnWidth](./set_mincolumnwidth/)(**uint32_t**) override | حداقل عرض ستون به تویپ (1/20 نقطه). فاصله شکاف (که به عنوان \"Column Gap\" یا \"Gap Width\" نیز شناخته می‌شود) به MinColumnWidth اضافه می‌شود تا کل فاصله Matrix [Column](../../aspose.slides/column/) (فاصله بین لبه‌های مشابه ستون‌های مختلف) را تعیین کند. پیش‌فرض: 0. |
| void [set_RowGap](./set_rowgap/)(**uint32_t**) override | مقدار فاصله عمودی بین سطرهای یک ماتریس؛ اگر RowGapRule روی 3 (\"Exactly\") تنظیم شده باشد، واحد به صورت تویپ (1/20 نقطه) تفسیر می‌شود. اگر RowGapRule روی 4 (\"Multiple\") تنظیم شده باشد، واحد به صورت نیم‌خط‌ها تفسیر می‌شود. پیش‌فرض: 0 |
| void [set_RowGapRule](./set_rowgaprule/)([MathSpacingRules](../mathspacingrules/)) override | نوع فاصله عمودی بین سطرهای یک ماتریس؛ واحدهای فاصله عمودی می‌توانند خطوط یا نقاط (به صورت تویپ) باشند. پیش‌فرض: SingleSpacingGap (0) |
| void [SetColumnAlignment](./setcolumnalignment/)(**int32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) override | تنظیم تراز افقی ستون مشخص‌شده |
| void [SetColumnsAlignment](./setcolumnsalignment/)(**int32_t**, **uint32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) override | تنظیم تراز افقی ستون‌های مشخص‌شده |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | دریافت حد پایین |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::String](../../system/string/)) override | دریافت حد پایین |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | زیرنویس ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::String](../../system/string/)) override | زیرنویس ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | زیرنویس و بالانویس در سمت چپ ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) override | زیرنویس و بالانویس در سمت چپ ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | زیرنویس و بالانویس در سمت راست ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) override | زیرنویس و بالانویس در سمت راست ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | بالانویس ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::String](../../system/string/)) override | بالانویس ایجاد می‌کند |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | تنظیم آرگومان قالب n-ام به یک اشاره‌گر ضعیف (به‌جای shared). اجازه می‌دهد اشاره‌گرها در کانتینرها به حالت weak تغییر کنند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | دریافت حد بالایی |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::String](../../system/string/)) override | دریافت حد بالایی |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌یابد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش و بازمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)() override | این عنصر را در یک border-box قرار می‌دهد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) override | این عنصر را در یک border-box قرار می‌دهد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../mathelementbase/tobox/)() override | این عنصر را در یک جعبه غیر‌دیداری (گروه‌بندی منطقی) که برای گروه‌بندی اجزای یک معادله یا متن ریاضی استفاده می‌شود، قرار می‌دهد. یک شیء جعبه‌دار می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطه‌تنظیم باشد، به‌عنوان نقطه‌شکنی خط، یا به‌صورت گروه‌بندی شود تا از شکست خط درون آن جلوگیری شود. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../mathelementbase/tomatharray/)() override | در یک آرایه افقی قرار می‌گیرد |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته‌ را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازندهٔ typeof([System.Object](../../system/object/)) در C#. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../mathelementbase/underbar/)() override | میله‌گیری در پایین این عنصر را تنظیم می‌کند |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی عبارت C# lock() برای بازکردن قفل. مستقیم فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## توضیحات

مثال: ```cpp
System::SharedPtr<IMathMatrix> matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## موارد مرتبط

* کلاس [MathElementBase](../mathelementbase/)
* کلاس [IMathMatrix](../imathmatrix/)
* کلاس [IHasControlCharacterProperties](../ihascontrolcharacterproperties/)
* فضای‌نام [Aspose::Slides::MathText](../)
* کتابخانه [Aspose.Slides](../../)