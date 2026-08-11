---
title: IMathBox
second_title: Aspose.Slides برای C++ مرجع API
description: مشخص می‌کند بسته‌بندی منطقی (بسته‌بندی) عنصر ریاضی. برای مثال، یک شیء بسته‌بندی شده می‌تواند به‌عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز عمل کند، می‌تواند به‌عنوان نقطه شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که از شکست خطوط داخل آن جلوگیری شود. برای مثال، عملگر \"==\" باید بسته‌بندی شود تا از شکست خطوط جلوگیری شود.
type: docs
weight: 170
url: /fa/aspose.slides.mathtext/imathbox/
---
## کلاس IMathBox

مشخص می‌کند بسته‌بندی منطقی (بسته‌بندی) عنصر ریاضی. برای مثال، یک شیء بسته‌بندی شده می‌تواند به‌عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز استفاده شود، می‌تواند به‌عنوان نقطهٔ شکست خط عمل کرده، یا به‌گونه‌ای گروه‌بندی شود که از شکست خطوط داخل آن جلوگیری شود. برای مثال، عملگر \"==\" باید بسته‌بندی شود تا از شکست خطوط جلوگیری شود.

```cpp
class IMathBox : public virtual Aspose::Slides::MathText::IMathElement
```

## متدها

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../imathelement/accent/)(char16_t) | یک علامت اکسنت تنظیم می‌کند (کاراکتری در بالای این عنصر) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | تابع مشخص‌شده‌ای را می‌گیرد که این نمونه را به عنوان آرگومان استفاده می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::String](../../system/string/)) | تابع مشخص‌شده‌ای را می‌گیرد که این نمونه را به عنوان آرگومان استفاده می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) | تابع مشخص‌شده‌ای را می‌گیرد که این نمونه را به عنوان آرگومان استفاده می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | تابع مشخص‌شده‌ای را می‌گیرد که این نمونه را به عنوان آرگومان استفاده می‌کند و آرگومان اضافی مشخص‌شده‌ای را می‌پذیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) | تابع مشخص‌شده‌ای را می‌گیرد که این نمونه را به عنوان آرگومان استفاده می‌کند و آرگومان اضافی مشخص‌شده‌ای را می‌پذیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | کسر‌ای ایجاد می‌کند با این صورت و مخرج مشخص‌شده |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/)) | کسر‌ای ایجاد می‌کند با این صورت و مخرج مشخص‌شده |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) | کسر از نوع مشخص‌شده‌ای را با این صورت و مخرج مشخص می‌سازد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) | کسر از نوع مشخص‌شده‌ای را با این صورت و مخرج مشخص می‌سازد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)() | یک عنصر ریاضی را در پرانتز می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)(char16_t, char16_t) | این عنصر را در کاراکترهای مشخص‌شده مانند پرانتز یا کاراکترهای دیگر به‌عنوان چارچوب می‌گیرد |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند حتی اگر مطابق IEC 60559:1989 NaN برابر هیچ مقداری، شامل NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند حتی اگر مطابق IEC 60559:1989 NaN برابر هیچ مقداری، شامل NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | تابعی از یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::String](../../system/string/)) | تابعی از یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع استفاده می‌کند |
| virtual **bool** [get_AlignmentPoint](./get_alignmentpoint/)() | وقتی true باشد، این شبیه‌ساز عملگر به‌عنوان نقطهٔ تراز عمل می‌کند؛ یعنی نقاط تراز تعیین‌شده در معادلات دیگر می‌توانند با آن هم‌تراز شوند. پیش‌فرض: false |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Base](./get_base/)() | آرگومان پایه |
| virtual **bool** [get_Differential](./get_differential/)() | دیفرانسیال. وقتی true باشد، جعبه به‌عنوان دیفرانسیال عمل می‌کند (مثلاً \\uD835\\uDC51\\uD835\\uDC65 در یک انتگرال‌گذار) و فضای افقی مناسب برای دیفرانسیال ریاضی دریافت می‌کند. پیش‌فرض: false |
| virtual **uint8_t** [get_ExplicitBreak](./get_explicitbreak/)() | شکست صریح مشخص می‌کند آیا در ابتدای شیء Box شکست خط وجود دارد یا نه، به-طوری که خط در ابتدای جعبه شکسته شود. عدد عملگر در خط قبلی متن ریاضی را که باید به‌عنوان نقطهٔ تراز برای خط جاری استفاده شود، مشخص می‌کند؛ مقادیر ممکن: 1..255 پیش‌فرض: 0 (بدون شکست صریح) |
| virtual **bool** [get_NoBreak](./get_nobreak/)() | بدون شکست. این ویژگی خاصیت «قابل‌شکست نبودن» را برای جعبهٔ شیء مشخص می‌کند. وقتی true باشد، هیچ شکستی داخل جعبه رخ نمی‌دهد. این می‌تواند برای شبیه‌سازهای عملگری که بیش از یک عملگر دودویی تشکیل می‌دهند مهم باشد. وقتی این عنصر مشخص نشود، شکسته‌ها می‌توانند داخل جعبه رخ دهند. پیش‌فرض: true |
| virtual **bool** [get_OperatorEmulator](./get_operatoremulator/)() | شبیه‌ساز عملگر. وقتی true باشد، جعبه و محتویات آن مانند یک عملگر واحد رفتار می‌کنند و ویژگی‌های یک عملگر را به ارث می‌برند. یعنی به‌عنوان مثال کاراکتر می‌تواند به‌عنوان نقطهٔ شکست خط عمل کند و می‌تواند با عملگرهای دیگر هم‌تراز شود. شبیه‌سازهای عملگر اغلب زمانی استفاده می‌شوند که یک یا چند گلیف با هم ترکیب شوند و یک عملگر مانند '==' را بسازند. مقدار پیش‌فرض: false |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](../imathelement/getchildren/)() | دریافت عناصر فرزند |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظیر متد C# [Object.GetHashCode()](../../system/object/gethashcode/) است. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. نظیر فراخوانی C# [System.Object.GetType()](../../system/object/gettype/) است. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)() | این عنصر را با استفاده از کروشهٔ پایین در یک گروه قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) | این عنصر را با استفاده از کاراکتر گروه‌بندی مانند کروشهٔ پایین یا کاراکتر دیگر در یک گروه قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) | انتگرال را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | انتگرال را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/)) | انتگرال را بدون حدود می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) | انتگرال را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | انتگرال را می‌گیرد |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. نظیر عملگر 'is' در C#. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::String](../../system/string/)) | یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی ایجاد می‌کند |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌بندی دستور C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظیر متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) است. امکان کلون‌سازی انواع سفارشی را می‌دهد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | یک عملگر N-ارزی ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | یک عملگر N-ارزی ایجاد می‌کند |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../imathelement/overbar/)() | نوار را در بالای این عنصر تنظیم می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | ریشهٔ ریاضی درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::String](../../system/string/)) | ریشهٔ ریاضی درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ ارجاعی شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع مشترک را با مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_AlignmentPoint](./set_alignmentpoint/)(**bool**) | وقتی true باشد، این شبیه‌ساز عملگر به‌عنوان نقطهٔ تراز عمل می‌کند؛ یعنی نقاط تراز تعیین‌شده در معادلات دیگر می‌توانند با آن هم‌تراز شوند. پیش‌فرض: false |
| virtual void [set_Differential](./set_differential/)(**bool**) | دیفرانسیال. وقتی true باشد، جعبه به‌عنوان دیفرانسیال عمل می‌کند (مثلاً \\uD835\\uDC51\\uD835\\uDC65 در یک انتگرال‌گذار) و فضای افقی مناسب برای دیفرانسیال ریاضی دریافت می‌کند. پیش‌فرض: false |
| virtual void [set_ExplicitBreak](./set_explicitbreak/)(**uint8_t**) | شکست صریح مشخص می‌کند آیا در ابتدای شیء Box شکست خط وجود دارد یا نه، به-طوری که خط در ابتدای جعبه شکسته شود. عدد عملگر در خط قبلی متن ریاضی را که باید به‌عنوان نقطهٔ تراز برای خط جاری استفاده شود، مشخص می‌کند؛ مقادیر ممکن: 1..255 پیش‌فرض: 0 (بدون شکست صریح) |
| virtual void [set_NoBreak](./set_nobreak/)(**bool**) | بدون شکست. این ویژگی خاصیت «قابل‌شکست نبودن» را برای جعبهٔ شیء مشخص می‌کند. وقتی true باشد، هیچ شکستی داخل جعبه رخ نمی‌دهد. این می‌تواند برای شبیه‌سازهای عملگری که بیش از یک عملگر دودویی تشکیل می‌دهند مهم باشد. وقتی این عنصر مشخص نشود، شکسته‌ها می‌توانند داخل جعبه رخ دهند. پیش‌فرض: true |
| virtual void [set_OperatorEmulator](./set_operatoremulator/)(**bool**) | شبیه‌ساز عملگر. وقتی true باشد، جعبه و محتویات آن مانند یک عملگر واحد رفتار می‌کنند و ویژگی‌های یک عملگر را به ارث می‌برند. یعنی به‌عنوان مثال کاراکتر می‌تواند به‌عنوان نقطهٔ شکست خط عمل کند و می‌تواند با عملگرهای دیگر هم‌تراز شود. شبیه‌سازهای عملگر اغلب زمانی استفاده می‌شوند که یک یا چند گلیف با هم ترکیب شوند و یک عملگر مانند '==' را بسازند. مقدار پیش‌فرض: false |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | حد پایین را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::String](../../system/string/)) | حد پایین را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | زیرنویس ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::String](../../system/string/)) | زیرنویس ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | زیرنویس و بالانویس را در سمت چپ می‌سازد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) | زیرنویس و بالانویس را در سمت چپ می‌سازد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | زیرنویس و بالانویس را در سمت راست می‌سازد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) | زیرنویس و بالانویس را در سمت راست می‌سازد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | بالانویس ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::String](../../system/string/)) | بالانویس ایجاد می‌کند |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف تنظیم می‌کند (به‌جای اشتراکی). امکان سوئیچ کردن اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | حد بالایی را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::String](../../system/string/)) | حد بالایی را می‌گیرد |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزوده می‌کند. نباید مستقیماً فراخوانی شود؛ به‌جای آن، از هوشمند-اشاره‌گرها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن، از هوشمند-اشاره‌گرها یا ThisProtector استفاده کنید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)() | این عنصر را در یک جعبهٔ حاشیه‌ای قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) | این عنصر را در یک جعبهٔ حاشیه‌ای قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](./)\> [ToBox](../imathelement/tobox/)() | این عنصر را در یک جعبهٔ غیر‌دیداری (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی مؤلفه‌های یک معادله یا نمونه دیگر متن ریاضی استفاده می‌شود. یک شیء بسته‌بندی شده می‌تواند (برای مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز، به‌عنوان نقطهٔ شکست خط، یا به‌گونه‌ای گروه‌بندی شود که از شکست خطوط داخل آن جلوگیری شود. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../imathelement/tomatharray/)() | در یک آرایهٔ عمودی قرار می‌دهد |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظیر متد C# [Object.ToString()](../../system/object/tostring/) است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../imathelement/underbar/)() | نوار را در پایین این عنصر تنظیم می‌کند |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی دستور C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزوده می‌کند. نباید مستقیماً فراخوانی شود؛ به‌جای آن، از هوشمند-اشاره‌گرها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن، از هوشمند-اشاره‌گرها یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## توضیحات

مثال: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
```

## مراجع مرتبط

* کلاس [IMathElement](../imathelement/)
* فضای‌نام [Aspose::Slides::MathText](../)
* کتابخانه [Aspose.Slides](../../)