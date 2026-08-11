---
title: MathBox
second_title: مرجع API Aspose.Slides برای C++
description: جعبه‌بندی منطقی (بسته‌بندی) عنصر ریاضی را مشخص می‌کند. به عنوان مثال، یک شیء جعبه‌شده می‌تواند به‌عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز عمل کند، به‌عنوان نقطهٔ شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که از ایجاد شکست خط درون آن جلوگیری شود. به عنوان مثال، عملگر \"==\" باید جعبه‌بندی شود تا از شکست خط جلوگیری شود.
type: docs
weight: 742
url: /fa/aspose.slides.mathtext/mathbox/
---
## کلاس MathBox

منطقی بودن جعبه‌بندی (بسته‌بندی) عنصر ریاضی را مشخص می‌کند. به عنوان مثال، یک شیء جعبه‌شده می‌تواند به‌عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز عمل کند، به‌عنوان نقطهٔ شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که از شکست خط درون آن جلوگیری شود. به‌عنوان مثال، عملگر \"==\" باید جعبه‌بندی شود تا از شکست خط جلوگیری شود.

```cpp
class MathBox : public Aspose::Slides::MathText::MathElementBase,
                public Aspose::Slides::MathText::IMathBox,
                public Aspose::Slides::MathText::IHasControlCharacterProperties
```

## متدها

| متد | توضیح |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../mathelementbase/accent/)(char16_t) override | یک علامت اکسنت تنظیم می‌کند (یک کاراکتر در بالای این عنصر) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | عملکرد مشخص‌شده‌ای را می‌گیرد که این نمونه را به‌عنوان آرگومان استفاده می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::String](../../system/string/)) override | عملکرد مشخص‌شده‌ای را می‌گیرد که این نمونه را به‌عنوان آرگومان استفاده می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) override | عملکرد مشخص‌شده‌ای را می‌گیرد که این نمونه را به‌عنوان آرگومان استفاده می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | عملکرد مشخص‌شده‌ای را می‌گیرد که این نمونه را به‌عنوان آرگومان استفاده می‌کند و آرگومان اضافی مشخص‌شده‌ای را دریافت می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) override | عملکرد مشخص‌شده‌ای را می‌گیرد که این نمونه را به‌عنوان آرگومان استفاده می‌کند و آرگومان اضافی مشخص‌شده‌ای را دریافت می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | یک کسر با صورت این عنصر و مخرج مشخص‌شده ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/)) override | یک کسر با صورت این عنصر و مخرج مشخص‌شده ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) override | یک کسر از نوع مشخص‌شده با صورت این عنصر و مخرج مشخص‌شده ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) override | یک کسر از نوع مشخص‌شده با صورت این عنصر و مخرج مشخص‌شده ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)() override | یک عنصر ریاضی را در پرانتز محصور می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)(char16_t, char16_t) override | یک عنصر ریاضی را در کاراکترهای مشخص‌شده مانند پرانتز یا کاراکترهای دیگر به‌عنوان قاب می‌گیرد |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از سمانتیک‌های C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | یک تابع از یک آرگومان می‌گیرد که این نمونه را به‌عنوان نام تابع استفاده می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::String](../../system/string/)) override | یک تابع از یک آرگومان می‌گیرد که این نمونه را به‌عنوان نام تابع استفاده می‌کند |
| **bool** [get_AlignmentPoint](./get_alignmentpoint/)() override | در صورت درست بودن، این شبیه‌ساز عملگر به‌عنوان نقطه تراز عمل می‌کند؛ یعنی نقاط تراز تعیین‌شده در معادلات دیگر می‌توانند با آن هم‌تراز شوند. Default: false |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Base](./get_base/)() override | آرگومان پایه |
| **bool** [get_Differential](./get_differential/)() override | دیفرانسیل. در صورت درست بودن، جعبه به‌عنوان دیفرانسیل عمل می‌کند (مثال: \\uD835\\uDC51\\uD835\\uDC65 در یک انتگرال)، و فضای افقی مناسب برای دیفرانسیل ریاضی را دریافت می‌کند. Default: false |
| **uint8_t** [get_ExplicitBreak](./get_explicitbreak/)() override | شکست صریح مشخص می‌کند آیا در ابتدای شیء Box شکست خط وجود دارد یا خیر، به‌گونه‌ای که خط در ابتدای جعبه بسته شود. تعداد عملگر در خط قبلی متن ریاضی که به‌عنوان نقطه تراز برای خط فعلی متن ریاضی استفاده می‌شود، مقادیر ممکن: 1..255 Default: 0 (no explicit break) |
| **bool** [get_NoBreak](./get_nobreak/)() override | بدون شکست. این ویژگی ویژگی "قابل شکست نیست" را بر روی جعبه شیء مشخص می‌کند. در صورت درست بودن، هیچ شکستی درون جعبه امکان‌پذیر نیست. این می‌تواند برای شبیه‌سازهای عملگر که بیش از یک عملگر باینری تشکیل می‌دهند مهم باشد. اگر این عنصر مشخص نشود، شکسته‌ها می‌توانند درون جعبه رخ دهند. Default: true |
| **bool** [get_OperatorEmulator](./get_operatoremulator/)() override | شبیه‌ساز عملگر. در صورت درست بودن، جعبه و محتویات آن به عنوان یک عملگر واحد رفتار می‌کنند و ویژگی‌های یک عملگر را به ارث می‌برند. این به این معناست که کاراکتر می‌تواند به‌عنوان نقطهٔ شکست خط عمل کند و به عملگرهای دیگر هم‌تراز شود. شبیه‌سازهای عملگر معمولاً وقتی یک یا چند گلیف ترکیب می‌شوند تا یک عملگر مانند '==' بسازند، استفاده می‌شوند. Default value: false |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](./getchildren/)() override | دریافت عناصر فرزند |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظیر متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. نظیر فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)() override | این عنصر را با استفاده از آکولاد پایین در یک گروه قرار می‌دهد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) override | این عنصر را با استفاده از کاراکتر گروه‌بندی مانند آکولاد پایین یا کاراکتر دیگر در یک گروه قرار می‌دهد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) override | انتگرال را می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | انتگرال را می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/)) override | انتگرال را بدون حدود می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) override | انتگرال را می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | انتگرال را می‌گیرد |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. نظیر عملگر 'is' در C#. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::String](../../system/string/)) override | یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| void [Lock](../../system/object/lock/)() | بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
|  [MathBox](./mathbox/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | متغیر [MathBox](./) را با عنصر مشخص‌شده به‌عنوان آرگومان مقداردهی اولیه می‌کند |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظیر متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | یک عملگر N-ارگی ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | یک عملگر N-ارگی ایجاد می‌کند |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی زیرکلاس‌ها را فراهم می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../mathelementbase/overbar/)() override | یک میله در بالای این عنصر تنظیم می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | ریشهٔ ریاضی به توان داده‌شده از آرگومان مشخص‌شده را تعیین می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::String](../../system/string/)) override | ریشهٔ ریاضی به توان داده‌شده از آرگومان مشخص‌شده را تعیین می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقداری را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع اشتراکی را با مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_AlignmentPoint](./set_alignmentpoint/)(**bool**) override | در صورت درست بودن، این شبیه‌ساز عملگر به‌عنوان نقطه تراز عمل می‌کند؛ یعنی نقاط تراز تعیین‌شده در معادلات دیگر می‌توانند با آن هم‌تراز شوند. Default: false |
| void [set_Differential](./set_differential/)(**bool**) override | دیفرانسیل. در صورت درست بودن، جعبه به‌عنوان دیفرانسیل عمل می‌کند (مثال: \\uD835\\uDC51\\uD835\\uDC65 در یک انتگرال)، و فضای افقی مناسب برای دیفرانسیل ریاضی را دریافت می‌کند. Default: false |
| void [set_ExplicitBreak](./set_explicitbreak/)(**uint8_t**) override | شکست صریح مشخص می‌کند آیا در ابتدای شیء Box شکست خط وجود دارد یا خیر، به‌گونه‌ای که خط در ابتدای جعبه بسته شود. تعداد عملگر در خط قبلی متن ریاضی که به‌عنوان نقطه تراز برای خط فعلی متن ریاضی استفاده می‌شود، مقادیر ممکن: 1..255 Default: 0 (no explicit break) |
| void [set_NoBreak](./set_nobreak/)(**bool**) override | بدون شکست. این ویژگی ویژگی "قابل شکست نیست" را بر روی جعبه شیء مشخص می‌کند. در صورت درست بودن، هیچ شکستی درون جعبه امکان‌پذیر نیست. این می‌تواند برای شبیه‌سازهای عملگر که بیش از یک عملگر باینری تشکیل می‌دهند مهم باشد. اگر این عنصر مشخص نشود، شکسته‌ها می‌توانند درون جعبه رخ دهند. Default: true |
| void [set_OperatorEmulator](./set_operatoremulator/)(**bool**) override | شبیه‌ساز عملگر. در صورت درست بودن، جعبه و محتویات آن به عنوان یک عملگر واحد رفتار می‌کنند و ویژگی‌های یک عملگر را به ارث می‌برند. این به این معناست که کاراکتر می‌تواند به‌عنوان نقطهٔ شکست خط عمل کند و به عملگرهای دیگر هم‌تراز شود. شبیه‌سازهای عملگر معمولاً وقتی یک یا چند گلیف ترکیب می‌شوند تا یک عملگر مانند '==' بسازند، استفاده می‌شوند. Default value: false |
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
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به‌عنوان اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌سازد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | حد بالایی را می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::String](../../system/string/)) override | حد بالایی را می‌گیرد |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار جاری شمارنده مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع اشتراکی را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع اشتراکی را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)() override | این عنصر را در یک جعبه مرزی قرار می‌دهد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) override | این عنصر را در یک جعبه مرزی قرار می‌دهد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../mathelementbase/tobox/)() override | این عنصر را در یک جعبه غیر بصری (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی مؤلفه‌های یک معادله یا سایر متن‌های ریاضی استفاده می‌شود. یک شیء جعبه‌شده می‌تواند (به عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز عمل کند، به‌عنوان نقطه شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که از شکست خط درون آن جلوگیری شود. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../mathelementbase/tomatharray/)() override | در یک آرایهٔ عمودی قرار می‌دهد |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظیر متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../mathelementbase/underbar/)() override | یک میله در پایین این عنصر تنظیم می‌کند |
| void [Unlock](../../system/object/unlock/)() | بیان lock() در C# را برای باز کردن قفل پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## نکات

مثال: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## موارد مرتبط

* کلاس [MathElementBase](../mathelementbase/)
* کلاس [IMathBox](../imathbox/)
* کلاس [IHasControlCharacterProperties](../ihascontrolcharacterproperties/)
* فضای‌نام [Aspose::Slides::MathText](../)
* کتابخانه [Aspose.Slides](../../)