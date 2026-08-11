---
title: MathArray
second_title: Aspose.Slides برای C++ مرجع API
description: یک آرایهٔ عمودی از معادلات یا هر شیء ریاضی را مشخص می‌کند
type: docs
weight: 638
url: /fa/aspose.slides.mathtext/matharray/
---
## MathArray کلاس

Specifies a vertical array of equations or any mathematical objects

```cpp
class MathArray : public Aspose::Slides::MathText::MathElementBase,
                  public Aspose::Slides::MathText::IMathArray
```

## متدها

| متد | توضیح |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../mathelementbase/accent/)(char16_t) override | یک علامت لهجه تنظیم می‌کند (یک کاراکتر در بالای این عنصر) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::String](../../system/string/)) override | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) override | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان و یک آرگومان اضافهٔ مشخص می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) override | تابع مشخص‌شده را با استفاده از این نمونه به‌عنوان آرگومان و یک آرگومان اضافهٔ مشخص می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | کسر را با این صورت‌عدد و مخرج مشخص‌شده ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/)) override | کسر را با این صورت‌عدد و مخرج مشخص‌شده ایجاد می‌کند |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) override | کسر از نوع مشخص‌شده را با این صورت‌عدد و مخرج مشخص می‌سازد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) override | کسر از نوع مشخص‌شده را با این صورت‌عدد و مخرج مشخص می‌سازد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)() override | یک عنصر ریاضی را در پرانتز می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)(char16_t, char16_t) override | یک عنصر ریاضی را در کاراکترهای مشخص‌شده مانند پرانتز یا کاراکترهای دیگر به‌عنوان قاب می‌گیرد |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از C# [Object.Equals](../../system/object/equals/) semantics. مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند هرچند طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند هرچند طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | تابعی از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::String](../../system/string/)) override | تابعی از یک آرگومان را با استفاده از این نمونه به‌عنوان نام تابع می‌گیرد |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Argument](./get_argument/)(**int32_t**) override | آیتم را در ایندکس مشخص‌شدهٔ آرایه برمی‌گرداند. فقط-خواندنی [Aspose::Slides::MathText::IMathElement](../imathelement/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElementCollection](../imathelementcollection/)\> [get_Arguments](./get_arguments/)() override | مجموعهٔ آیتم‌های آرایه |
| [MathVerticalAlignment](../mathverticalalignment/) [get_BaseJustification](./get_basejustification/)() override | ترازبندی آرایه نسبت به متن محیطی را مشخص می‌کند. متن خارج از آرایه می‌تواند با پایین، بالا یا مرکز شیء آرایه هم‌تراز شود. مقدار پیش‌فرض: مرکز |
| **bool** [get_MaximumDistribution](./get_maximumdistribution/)() override | توزیع حداکثری. وقتی true باشد، آرایه به حداکثر عرض عنصر شامل‌کننده (صفحه، ستون، سلول و…) فاصله می‌دهد. |
| **bool** [get_ObjectDistribution](./get_objectdistribution/)() override | توزیع شیء. وقتی true باشد، محتویات آرایه به حداکثر عرض شیء آرایه فاصله می‌دهند. |
| **uint32_t** [get_RowSpacing](./get_rowspacing/)() override | فاصله‌گذاری بین ردیف‌های آرایه. فقط زمانی استفاده می‌شود که RowSpacingRule برابر ۳ باشد؛ در این حالت واحد اندازه‌گیری points است یا Multiple که نصف خط‌هاست. پیش‌فرض: ۰. |
| [MathRowSpacingRule](../mathrowspacingrule/) [get_RowSpacingRule](./get_rowspacingrule/)() override | نوع فاصلهٔ عمودی بین عناصر آرایه. پیش‌فرض: SingleLineGap |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](./getchildren/)() override | دریافت عناصر فرزند |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)() override | این عنصر را با استفاده از یک پرانتز منحنی پایین در یک گروه قرار می‌دهد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) override | این عنصر را با استفاده از یک کاراکتر گروه‌بندی مثل پرانتز منحنی پایین یا دیگری در یک گروه قرار می‌دهد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) override | انتگرال را می‌گیرد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | انتگرال را می‌گیرد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/)) override | انتگرال را بدون حد می‌گیرد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) override | انتگرال را می‌گیرد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | انتگرال را می‌گیرد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | یک عنصر ریاضی را می‌پیوندد و بلوک ریاضی تشکیل می‌دهد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::String](../../system/string/)) override | یک متن ریاضی را می‌پیوندد و بلوک ریاضی تشکیل می‌دهد. |
| void [Lock](../../system/object/lock/)() | عملگر قفل () در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء مراقبت [LockContext](../../system/lockcontext/) استفاده کنید. |
|  [MathArray](./matharray/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | آرایهٔ ریاضی ایجاد می‌کند و عنصر مشخص‌شده را در آن قرار می‌دهد. |
|  [MathArray](./matharray/)([System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\>\>) | آرایهٔ ریاضی ایجاد می‌کند و عناصر مشخص‌شده را در آن قرار می‌دهد. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون کردن انواع سفارشی را می‌دهد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | یک عملگر N-ary ایجاد می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | یک عملگر N-ary ایجاد می‌کند. |
|  [Object](../../system/object/object/)() | شیء ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن زیرکلاس‌ها با کپی را فراهم می‌آورد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن زیرکلاس‌ها با کپی را فراهم می‌آورد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../mathelementbase/overbar/)() override | نماد بالایی این عنصر را تنظیم می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | ریشهٔ ریاضی از درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::String](../../system/string/)) override | ریشهٔ ریاضی از درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارش مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_BaseJustification](./set_basejustification/)([MathVerticalAlignment](../mathverticalalignment/)) override | ترازبندی آرایه نسبت به متن محیطی را مشخص می‌کند. متن خارج از آرایه می‌تواند با پایین، بالا یا مرکز شیء آرایه هم‌تراز شود. مقدار پیش‌فرض: مرکز |
| void [set_MaximumDistribution](./set_maximumdistribution/)(**bool**) override | توزیع حداکثری. وقتی true باشد، آرایه به حداکثر عرض عنصر شامل‌کننده (صفحه، ستون، سلول و…) فاصله می‌دهد. |
| void [set_ObjectDistribution](./set_objectdistribution/)(**bool**) override | توزیع شیء. وقتی true باشد، محتویات آرایه به حداکثر عرض شیء آرایه فاصله می‌دهند. |
| void [set_RowSpacing](./set_rowspacing/)(**uint32_t**) override | فاصله‌گذاری بین ردیف‌های آرایه. فقط زمانی استفاده می‌شود که RowSpacingRule برابر ۳ باشد؛ در این حالت واحد اندازه‌گیری points است یا Multiple که نصف خط‌هاست. پیش‌فرض: ۰. |
| void [set_RowSpacingRule](./set_rowspacingrule/)([MathRowSpacingRule](../mathrowspacingrule/)) override | نوع فاصلهٔ عمودی بین عناصر آرایه. پیش‌فرض: SingleLineGap |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | حد پایین را می‌گیرد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::String](../../system/string/)) override | حد پایین را می‌گیرد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | نشان زیرنویس ایجاد می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::String](../../system/string/)) override | نشان زیرنویس ایجاد می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | نشان زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) override | نشان زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | نشان زیرنویس و بالانویس را در سمت راست ایجاد می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) override | نشان زیرنویس و بالانویس را در سمت راست ایجاد می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | بالانویس ایجاد می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::String](../../system/string/)) override | بالانویس ایجاد می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | حد بالایی را می‌گیرد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::String](../../system/string/)) override | حد بالایی را می‌گیرد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارش مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از هوشمندها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارش مرجع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از هوشمندها یا ThisProtector استفاده کنید. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)() override | این عنصر را در یک جعبهٔ مرزی قرار می‌دهد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) override | این عنصر را در یک جعبهٔ مرزی قرار می‌دهد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../mathelementbase/tobox/)() override | این عنصر را در یک جعبهٔ غیر‌قابل مشاهده (گروه‌بندی منطقی) که برای گروه‌بندی مؤلفه‌های یک معادله یا متن ریاضی استفاده می‌شود، قرار می‌دهد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../mathelementbase/tomatharray/)() override | در یک آرایهٔ عمودی قرار می‌دهد. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را می‌دهد. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../mathelementbase/underbar/)() override | نماد پایین این عنصر را تنظیم می‌کند. |
| void [Unlock](../../system/object/unlock/)() | عملگر قفل () در C# را برای باز کردن پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء مراقبت [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارش مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از هوشمندها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارش مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از هوشمندها یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داخلی را آزاد می‌کند. |

## نظرات

Example: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
```

## موارد مرتبط

* کلاس [MathElementBase](../mathelementbase/)
* کلاس [IMathArray](../imatharray/)
* فضای‌نام [Aspose::Slides::MathText](../)
* کتابخانه [Aspose.Slides](../../)