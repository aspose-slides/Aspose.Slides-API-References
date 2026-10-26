---
title: IMathDelimiter
second_title: راهنمای API Aspose.Slides برای C++
description: "شیء جداکننده را مشخص می‌کند که شامل کاراکترهای باز و بسته (مانند پرانتز، براکت، کروشه و خطوط عمودی) و یک یا چند عنصر ریاضی در داخل آن است که با یک کاراکتر مشخص جدا می‌شوند. مثال‌ها: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662]"
type: docs
weight: 196
url: /fa/aspose.slides.mathtext/imathdelimiter/
---
## IMathDelimiter کلاس

شیء جداکننده را مشخص می‌کند که شامل کاراکترهای باز و بسته (مانند پرانتز، کروشه، براکت و خطوط عمودی) و یک یا چند عنصر ریاضی در داخل آن است که با یک کاراکتر مشخص جدا می‌شوند. مثال‌ها: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662]

```cpp
class IMathDelimiter : public virtual Aspose::Slides::MathText::IMathElement
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../imathelement/accent/)(char16_t) | یک علامت اکسنت تنظیم می‌کند (یک کاراکتر در بالای این عنصر) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | یک تابع مشخص‌شده را می‌گیرد که این نمونه را به عنوان آرگومان استفاده می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::String](../../system/string/)) | یک تابع مشخص‌شده را می‌گیرد که این نمونه را به عنوان آرگومان استفاده می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) | یک تابع مشخص‌شده را می‌گیرد که این نمونه را به عنوان آرگومان استفاده می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | یک تابع مشخص‌شده را می‌گیرد که این نمونه را به عنوان آرگومان و آرگومان اضافی مشخص‌شده استفاده می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) | یک تابع مشخص‌شده را می‌گیرد که این نمونه را به عنوان آرگومان و آرگومان اضافی مشخص‌شده استفاده می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](./)\> [Delimit](./delimit/)(char16_t) | آرگومان‌ها را با کاراکتر جداکننده مشخص‌شده جدا می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | کسر را با صورت این شیء و مخرج مشخص‌شده ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/)) | کسر را با صورت این شیء و مخرج مشخص‌شده ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) | کسر از نوع مشخص‌شده را با صورت این شیء و مخرج مشخص‌شده ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) | کسر از نوع مشخص‌شده را با صورت این شیء و مخرج مشخص‌شده ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](./)\> [Enclose](../imathelement/enclose/)() | یک عنصر ریاضی را در پرانتز می‌گذارد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](./)\> [Enclose](../imathelement/enclose/)(char16_t, char16_t) | این عنصر را در کاراکترهای مشخص‌شده مانند پرانتز یا کاراکترهای دیگر به عنوان چارچوب می‌نشیند |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با منطق C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری از جمله NaN نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری از جمله NaN نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی استفاده می‌شود. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | تابعی از یک آرگومان می‌گیرد که این نمونه را به عنوان نام تابع استفاده می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::String](../../system/string/)) | تابعی از یک آرگومان می‌گیرد که این نمونه را به عنوان نام تابع استفاده می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Argument](./get_argument/)(**int32_t**) | عنصر ریاضی را در اندیس مشخص‌شده آرایه برمی‌گرداند. فقط-خواندنی [Aspose::Slides::MathText::IMathElement](../imathelement/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathElementCollection](../imathelementcollection/)\> [get_Arguments](./get_arguments/)() | یک یا چند عنصر ریاضی که با کاراکترهای جداکننده جدا شده‌اند |
| virtual char16_t [get_BeginningCharacter](./get_beginningcharacter/)() | کاراکتر شروع جداکننده کاراکتر شروع یا باز را مشخص می‌کند. جداکننده‌های ریاضی کاراکترهای محاطی مانند پرانتز، براکت و کروشه هستند. مقدار پیش‌فرض: '('. |
| virtual [MathDelimiterShape](../mathdelimitershape/) [get_DelimiterShape](./get_delimitershape/)() | شکل جداکننده‌ها را در شیء جداکننده تعیین می‌کند. وقتی [MathDelimiterShape::Centered](../mathdelimitershape/) باشد، جداکننده‌ها حول محور ریاضی متن متمرکز می‌شوند و سعی می‌کند کل ارتفاع محتوا را پوشش دهند. وقتی [MathDelimiterShape::Match](../mathdelimitershape/) باشد، ارتفاع و شکل آنها دقیقاً با محتوا مطابقت می‌کند. |
| virtual char16_t [get_EndingCharacter](./get_endingcharacter/)() | کاراکتر پایان جداکننده کاراکتر پایان یا بسته را مشخص می‌کند. جداکننده‌های ریاضی کاراکترهای محاطی مانند پرانتز، براکت و کروشه هستند. مقدار پیش‌فرض: ')'. |
| virtual **bool** [get_GrowToMatchOperandHeight](./get_growtomatchoperandheight/)() | رشد کاراکتر شروع، کاراکتر جداکننده و کاراکتر پایان را مشخص می‌کند. وقتی true باشد، جداکننده‌ها به صورت عمودی برای تطبیق با ارتفاع عملوند رشد می‌کنند. مقدار پیش‌فرض true است |
| virtual char16_t [get_SeparatorCharacter](./get_separatorcharacter/)() | کاراکتر جداکننده کاراکتری را که آرگومان‌ها را در شیء جداکننده جدا می‌کند، مشخص می‌کند. مقدار پیش‌فرض: '|'. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](../imathelement/getchildren/)() | دریافت عناصر فرزند |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | داده ساختار شمارنده ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)() | این عنصر را با استفاده از یک کروشه پایین در یک گروه قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) | این عنصر را با استفاده از یک کاراکتر گروه‌بندی مانند کروشه پایین یا کاراکتر دیگری در یک گروه قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) | انتگرال را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | انتگرال را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/)) | انتگرال را بدون حدود می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) | انتگرال را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | انتگرال را می‌گیرد |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::String](../../system/string/)) | متن ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| void [Lock](../../system/object/lock/)() | بیانیه C# lock() را برای قفل‌گذاری اجرا می‌کند. به‌طور مستقیم فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | یک عملگر N-ary ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | یک عملگر N-ary ایجاد می‌کند |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن سازنده کپی برای کلاس‌های مشتق را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور تخصیص. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن سازنده کپی برای کلاس‌های مشتق را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../imathelement/overbar/)() | یک خط افقی در بالای این عنصر تنظیم می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | ریشه ریاضی از درجه داده شده بر پایه آرگومان مشخص‌شده را تعیین می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::String](../../system/string/)) | ریشه ریاضی از درجه داده شده بر پایه آرگومان مشخص‌شده را تعیین می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه ارجاعی یک شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد ارجاع مشترک را با مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_BeginningCharacter](./set_beginningcharacter/)(char16_t) | کاراکتر شروع جداکننده کاراکتر شروع یا باز را مشخص می‌کند. جداکننده‌های ریاضی کاراکترهای محاطی مانند پرانتز، براکت و کروشه هستند. مقدار پیش‌فرض: '('. |
| virtual void [set_DelimiterShape](./set_delimitershape/)([MathDelimiterShape](../mathdelimitershape/)) | شکل جداکننده‌ها را در شیء جداکننده تعیین می‌کند. وقتی [MathDelimiterShape::Centered](../mathdelimitershape/) باشد، جداکننده‌ها حول محور ریاضی متن متمرکز می‌شوند و سعی می‌کند کل ارتفاع محتوا را پوشش دهند. وقتی [MathDelimiterShape::Match](../mathdelimitershape/) باشد، ارتفاع و شکل آنها دقیقاً با محتوا مطابقت می‌کند. |
| virtual void [set_EndingCharacter](./set_endingcharacter/)(char16_t) | کاراکتر پایان جداکننده کاراکتر پایان یا بسته را مشخص می‌کند. جداکننده‌های ریاضی کاراکترهای محاطی مانند پرانتز، براکت و کروشه هستند. مقدار پیش‌فرض: ')'. |
| virtual void [set_GrowToMatchOperandHeight](./set_growtomatchoperandheight/)(**bool**) | رشد کاراکتر شروع، کاراکتر جداکننده و کاراکتر پایان را مشخص می‌کند. وقتی true باشد، جداکننده‌ها به صورت عمودی برای تطبیق با ارتفاع عملوند رشد می‌کنند. مقدار پیش‌فرض true است |
| virtual void [set_SeparatorCharacter](./set_separatorcharacter/)(char16_t) | کاراکتر جداکننده کاراکتری را که آرگومان‌ها را در شیء جداکننده جدا می‌کند، مشخص می‌کند. مقدار پیش‌فرض: '|'. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | حد پایین را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::String](../../system/string/)) | حد پایین را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | زیرنوشت ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::String](../../system/string/)) | زیرنوشت ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | زیرنوشت و بالانوشت را در سمت چپ ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) | زیرنوشت و بالانوشت را در سمت چپ ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | زیرنوشت و بالانوشت را در سمت راست ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) | زیرنوشت و بالانوشت را در سمت راست ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | بالانوشت ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::String](../../system/string/)) | بالانوشت ایجاد می‌کند |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب n-ام را به یک پوینتر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تغییر پوینترها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | حد بالا را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::String](../../system/string/)) | حد بالا را می‌گیرد |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده ارجاع مشترک را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده ارجاع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)() | این عنصر را در یک جعبه حاشیه‌ای قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) | این عنصر را در یک جعبه حاشیه‌ای قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../imathelement/tobox/)() | این عنصر را در یک جعبه غیرقابل مشاهده (گروه‌بندی منطقی) که برای گروه‌بندی اجزای یک معادله یا سایر متن‌های ریاضی استفاده می‌شود، قرار می‌دهد. یک شیء جعبه‌ای می‌تواند (به‌عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز، به‌عنوان نقطه شکستن خط، یا به‌صورت گروه‌بندی شود تا از شکست خط در داخل آن جلوگیری کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../imathelement/tomatharray/)() | در یک آرایه عمودی قرار می‌دهد |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار C# typeof([System.Object](../../system/object/)) را اجرا می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../imathelement/underbar/)() | یک خط افقی در پایین این عنصر تنظیم می‌کند |
| void [Unlock](../../system/object/unlock/)() | بیانیه C# lock() را برای بازکردن قفل اجرا می‌کند. به‌طور مستقیم فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده ارجاع ضعیف را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده ارجاع ضعیف را کاهش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را تخریب می‌کند. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## ملاحظات

مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## مراجع

* کلاس [IMathElement](../imathelement/)
* فضای‌نام [Aspose::Slides::MathText](../)
* کتابخانه [Aspose.Slides](../../)