---
title: MathDelimiter
second_title: مرجع API Aspose.Slides برای C++
description: "آبجکت جداساز را مشخص می‌کند که شامل کاراکترهای باز و بسته (مانند پرانتز، آکولاد، براکت و خطوط عمودی) و یک یا چند عنصر ریاضی درون آن است که با یک کاراکتر مشخص از هم جدا شده‌اند. مثال‌ها: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662]"
type: docs
weight: 768
url: /fa/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter کلاس

آبجکت جداساز را مشخص می‌کند که شامل کاراکترهای باز و بسته (مانند پرانتز، آکولاد، براکت و خطوط عمودی) و یک یا چند عنصر ریاضی درون آن است که با یک کاراکتر مشخص از هم جدا شده‌اند. مثال‌ها: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662]

```cpp
class MathDelimiter : public Aspose::Slides::MathText::MathElementBase,
                      public Aspose::Slides::MathText::IMathDelimiter,
                      public Aspose::Slides::MathText::IHasControlCharacterProperties
```

## متدها

| متد | توضیح |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../mathelementbase/accent/)(char16_t) override | یک علامت اکسنت (کاراکتری در بالای این عنصر) را تنظیم می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | تابع مشخصی را که این نمونه به‌عنوان آرگومان استفاده می‌کند می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::String](../../system/string/)) override | تابع مشخصی را که این نمونه به‌عنوان آرگومان استفاده می‌کند می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) override | تابع مشخصی را که این نمونه به‌عنوان آرگومان استفاده می‌کند می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | تابع مشخصی را که این نمونه به‌عنوان آرگومان استفاده می‌کند و آرگومان اضافی مشخص شده را می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) override | تابع مشخصی را که این نمونه به‌عنوان آرگومان استفاده می‌کند و آرگومان اضافی مشخص شده را می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Delimit](./delimit/)(char16_t) override | آرگومان‌ها را با استفاده از کاراکتر جداساز مشخص شده محدود می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | یک کسر با صورت این عنصر و مخرج مشخص شده ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/)) override | یک کسر با صورت این عنصر و مخرج مشخص شده ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) override | یک کسر از نوع مشخص شده با صورت این عنصر و مخرج مشخص شده ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) override | یک کسر از نوع مشخص شده با صورت این عنصر و مخرج مشخص شده ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](./enclose/)(char16_t, char16_t) override | یک عنصر ریاضی را در کاراکترهای مشخص شده مانند پرانتز یا کاراکترهای دیگر به‌صورت قاب می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)() override | یک عنصر ریاضی را در پرانتز می‌گیرد |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از semantics C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌فلانی به-سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌فلانی به-سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | تابعی از یک آرگومان می‌گیرد که این نمونه به‌عنوان نام تابع استفاده می‌شود |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::String](../../system/string/)) override | تابعی از یک آرگومان می‌گیرد که این نمونه به‌عنوان نام تابع استفاده می‌شود |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Argument](./get_argument/)(**int32_t**) override | عنصر ریاضی در اندیس مشخص شده از آرایه را برمی‌گرداند. فقط-خواندنی [Aspose::Slides::MathText::IMathElement](../imathelement/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElementCollection](../imathelementcollection/)\> [get_Arguments](./get_arguments/)() override | یک یا چند عنصر ریاضی که با کاراکترهای جداساز جدا شده‌اند |
| char16_t [get_BeginningCharacter](./get_beginningcharacter/)() override | کاراکتر شروع جداساز را مشخص می‌کند. کاراکتر پیش‌فرض: '('. |
| [MathDelimiterShape](../mathdelimitershape/) [get_DelimiterShape](./get_delimitershape/)() override | شکل جداسازها در آبجکت جداساز را مشخص می‌کند. وقتی [MathDelimiterShape::Centered](../mathdelimitershape/) است، جداسازها حول محور ریاضی متن مرکز می‌شوند و همچنان برای تمام ارتفاع محتوا تنظیم می‌شوند. وقتی [MathDelimiterShape::Match](../mathdelimitershape/) است، ارتفاع و شکل آن‌ها دقیقاً با محتوا مطابقت می‌کند. |
| char16_t [get_EndingCharacter](./get_endingcharacter/)() override | کاراکتر پایان جداساز را مشخص می‌کند. کاراکتر پیش‌فرض: ')'. |
| **bool** [get_GrowToMatchOperandHeight](./get_growtomatchoperandheight/)() override | رشد کاراکترهای BeginningCharacter، SeparatorCharacter و EndingCharacter را مشخص می‌کند. وقتی true باشد، جداسازها به‌صورت عمودی برای تطابق با ارتفاع عملوند رشد می‌کنند. مقدار پیش‌فرض true است. |
| char16_t [get_SeparatorCharacter](./get_separatorcharacter/)() override | کاراکتر جداساز را مشخص می‌کند که آرگومان‌ها را در آبجکت جداساز جدا می‌کند. پیش‌فرض: '|'. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](./getchildren/)() override | دریافت عناصر فرزند |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)() override | این عنصر را با استفاده از یک کروشه‌پایینی در یک گروه قرار می‌دهد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) override | این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند کروشه‌پایینی یا دیگری در یک گروه قرار می‌دهد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) override | انتگرال را می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | انتگرال را می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/)) override | انتگرال را بدون حدها می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) override | انتگرال را می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | انتگرال را می‌گیرد |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::String](../../system/string/)) override | یک متن ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| void [Lock](../../system/object/lock/)() | اجرای قفل (lock()) در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
|  [MathDelimiter](./mathdelimiter/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | [MathDelimiter](./) را با عنصر مشخص به‌عنوان آرگومان پایهٔ واحد مقداردهی اولیه می‌کند |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | یک عملگر N-تایی ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | یک عملگر N-تایی ایجاد می‌کند |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی در زیرکلاس‌ها را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی در زیرکلاس‌ها را فراهم می‌سازد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../mathelementbase/overbar/)() override | نوار را در بالای این عنصر تنظیم می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | ریشهٔ ریاضی از درجهٔ داده‌شده را بر اساس آرگومان مشخص‌شده مشخص می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::String](../../system/string/)) override | ریشهٔ ریاضی از درجهٔ داده‌شده را بر اساس آرگومان مشخص‌شده مشخص می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_BeginningCharacter](./set_beginningcharacter/)(char16_t) override | کاراکتر شروع جداساز را مشخص می‌کند. کاراکتر پیش‌فرض: '('. |
| void [set_DelimiterShape](./set_delimitershape/)([MathDelimiterShape](../mathdelimitershape/)) override | شکل جداسازها در آبجکت جداساز را مشخص می‌کند. وقتی [MathDelimiterShape::Centered](../mathdelimitershape/) است، جداسازها حول محور ریاضی متن مرکز می‌شوند و همچنان برای تمام ارتفاع محتوا تنظیم می‌شوند. وقتی [MathDelimiterShape::Match](../mathdelimitershape/) است، ارتفاع و شکل آن‌ها دقیقاً با محتوا مطابقت می‌کند. |
| void [set_EndingCharacter](./set_endingcharacter/)(char16_t) override | کاراکتر پایان جداساز را مشخص می‌کند. کاراکتر پیش‌فرض: ')'. |
| void [set_GrowToMatchOperandHeight](./set_growtomatchoperandheight/)(**bool**) override | رشد کاراکترهای BeginningCharacter، SeparatorCharacter و EndingCharacter را مشخص می‌کند. وقتی true باشد، جداسازها به‌صورت عمودی برای تطابق با ارتفاع عملوند رشد می‌کنند. مقدار پیش‌فرض true است. |
| void [set_SeparatorCharacter](./set_separatorcharacter/)(char16_t) override | کاراکتر جداساز را مشخص می‌کند که آرگومان‌ها را در آبجکت جداساز جدا می‌کند. پیش‌فرض: '|'. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | حد پایین را می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::String](../../system/string/)) override | حد پایین را می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | زیرنویس ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::String](../../system/string/)) override | زیرنویس ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) override | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) override | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | بالانویس ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::String](../../system/string/)) override | بالانویس ایجاد می‌کند |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | حد بالایی را می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::String](../../system/string/)) override | حد بالایی را می‌گیرد |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش می‌دهد و باز می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)() override | این عنصر را در یک جعبهٔ مرزی قرار می‌دهد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) override | این عنصر را در یک جعبهٔ مرزی قرار می‌دهد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../mathelementbase/tobox/)() override | این عنصر را در یک جعبهٔ غیر‌دیداری (گروه‌بندی منطقی) که برای گروه‌بندی مؤلفه‌های یک معادله یا متن ریاضی دیگر استفاده می‌شود، قرار می‌دهد. یک شیء جعبه‌ای می‌تواند (به عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز عمل کند، به‌عنوان نقطهٔ شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که اجازه شکست خط داخل آن را ندهد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../mathelementbase/tomatharray/)() override | در یک آرایهٔ عمودی قرار می‌دهد |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../mathelementbase/underbar/)() override | نوار را در پایین این عنصر تنظیم می‌کند |
| void [Unlock](../../system/object/unlock/)() | اجرای بازقفل (unlock) در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## ملاحظات

مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## موارد مرتبط

* کلاس [MathElementBase](../mathelementbase/)
* کلاس [IMathDelimiter](../imathdelimiter/)
* کلاس [IHasControlCharacterProperties](../ihascontrolcharacterproperties/)
* فضای‌نام [Aspose::Slides::MathText](../)
* کتابخانه [Aspose.Slides](../../)