---
title: IMathNaryOperator
second_title: مرجع API Aspose.Slides برای C++
description: "یک شیٔ ریاضی N-آری را مشخص می‌کند، مانند جمع و انتگرال. این شامل یک عملگر، یک پایه (یا عملوند) و حدهای بالایی و پایینی اختیاری است. مثال‌های عملگرهای N-آری عبارتند از: جمع، اجتماع، اشتراک، انتگرال"
type: docs
weight: 417
url: /fa/aspose.slides.mathtext/imathnaryoperator/
---
## IMathNaryOperator کلاس

یک شیٔ ریاضی N-آری را مشخص می‌کند، مانند جمع و انتگرال. این شیٔ شامل یک عملگر، پایه (یا عملوند) و حدهای بالا و پایین اختیاری است. مثال‌های عملگرهای N-آری عبارتند از: جمع، اجتماع، اشتراک، انتگرال

```cpp
class IMathNaryOperator : public virtual Aspose::Slides::MathText::IMathElement,
                          public Aspose::Slides::MathText::IMathNaryOperatorProperties
```
## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../imathelement/accent/)(char16_t) | یک علامت تلفظ (کاراکتری روی بالای این عنصر) را تنظیم می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::String](../../system/string/)) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافهٔ مشخص‌شده می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) | تابع مشخص‌شده را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافهٔ مشخص‌شده می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | کسر را با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/)) | کسر را با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) | کسر از نوع مشخص‌شده را با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) | کسر از نوع مشخص‌شده را با این صورت و مخرج مشخص‌شده ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)() | یک عنصر ریاضی را در پرانتز قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)(char16_t, char16_t) | این عنصر را در کاراکترهای مشخص‌شده مثل پرانتز یا سایر کاراکترهای چارچوب‌گذار قرار می‌دهد |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از مفهوم [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | تابعی از آرگومان را با استفاده از این نمونه به عنوان نام تابع می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::String](../../system/string/)) | تابعی از آرگومان را با استفاده از این نمونه به عنوان نام تابع می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Base](./get_base/)() | آرگومان پایه |
| virtual **bool** [get_GrowToMatchOperandHeight](../imathnaryoperatorproperties/get_growtomatchoperandheight/)() | کاراکتر عملگر به صورت عمودی رشد می‌کند تا با ارتفاع عملوند مطابقت داشته باشد. |
| virtual **bool** [get_HideSubscript](../imathnaryoperatorproperties/get_hidesubscript/)() | پنهان کردن زیرنویس |
| virtual **bool** [get_HideSuperscript](../imathnaryoperatorproperties/get_hidesuperscript/)() | پنهان کردن بالانویس |
| virtual [MathLimitLocations](../mathlimitlocations/) [get_LimitLocation](../imathnaryoperatorproperties/get_limitlocation/)() | موقعیت حدها (زیرنویس و بالانویس) |
| virtual char16_t [get_Operator](../imathnaryoperatorproperties/get_operator/)() | کاراکتر عملگر N-آری برای مثال: '\\u2211', '\\u222B' |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Subscript](./get_subscript/)() | یک آرگومان زیرنویس را مشخص می‌کند که برای مثال در حالت انتگرال، حد پایین را تعیین می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Superscript](./get_superscript/)() | یک آرگومان بالانویس را مشخص می‌کند که برای مثال در حالت انتگرال، حد بالا را تعیین می‌کند |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](../imathelement/getchildren/)() | دریافت عناصر فرزند |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مربوط به شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)() | این عنصر را در یک گروه با استفاده از کروشهٔ پایین قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) | این عنصر را در یک گروه با استفاده از کاراکتر گروه‌بندی مانند کروشهٔ پایین یا کاراکتر دیگر قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](./)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) | انتگرال را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](./)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | انتگرال را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](./)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/)) | انتگرال را بدون حدها می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](./)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) | انتگرال را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](./)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | انتگرال را می‌گیرد |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | یک عنصر ریاضی را به هم می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::String](../../system/string/)) | یک متن ریاضی را به هم می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری مطابق با عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](./)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | یک عملگر N-آری ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](./)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | یک عملگر N-آری ایجاد می‌کند |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. همهٔ ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../imathelement/overbar/)() | یک نوار بر بالای این عنصر تنظیم می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | ریشهٔ ریاضی به درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::String](../../system/string/)) | ریشهٔ ریاضی به درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقداری را با nullptr از طریق مقایسهٔ ارجاعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به‌وسیله مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_GrowToMatchOperandHeight](../imathnaryoperatorproperties/set_growtomatchoperandheight/)(**bool**) | کاراکتر عملگر به صورت عمودی رشد می‌کند تا با ارتفاع عملوند مطابقت داشته باشد. |
| virtual void [set_HideSubscript](../imathnaryoperatorproperties/set_hidesubscript/)(**bool**) | پنهان کردن زیرنویس |
| virtual void [set_HideSuperscript](../imathnaryoperatorproperties/set_hidesuperscript/)(**bool**) | پنهان کردن بالانویس |
| virtual void [set_LimitLocation](../imathnaryoperatorproperties/set_limitlocation/)([MathLimitLocations](../mathlimitlocations/)) | موقعیت حدها (زیرنویس و بالانویس) |
| virtual void [set_Operator](../imathnaryoperatorproperties/set_operator/)(char16_t) | کاراکتر عملگر N-آری برای مثال: '\\u2211', '\\u222B' |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | حد پایین را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::String](../../system/string/)) | حد پایین را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | زیرنویس ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::String](../../system/string/)) | زیرنویس ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | بالانویس ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::String](../../system/string/)) | بالانویس ایجاد می‌کند |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | حد بالا را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::String](../../system/string/)) | حد بالا را می‌گیرد |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)() | این عنصر را در یک جعبهٔ حاشیه‌ای قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) | این عنصر را در یک جعبهٔ حاشیه‌ای قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../imathelement/tobox/)() | این عنصر را در یک جعبهٔ غیر‌دیداری (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی اجزای یک معادله یا نمونهٔ دیگر متن ریاضی استفاده می‌شود. یک شیء جعبه‌شده می‌تواند (به‌عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ ترازبندی عمل کند، به‌عنوان نقطهٔ شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که اجازهٔ شکست خط داخلی را ندهد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../imathelement/tomatharray/)() | در یک آرایهٔ عمودی قرار می‌دهد |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../imathelement/underbar/)() | یک نوار بر پایین این عنصر تنظیم می‌کند |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی مطابق با عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## ملاحظات

مثال: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
```

## موارد مرتبط

* کلاس [IMathElement](../imathelement/)
* کلاس [IMathNaryOperatorProperties](../imathnaryoperatorproperties/)
* فضای‌نام [Aspose::Slides::MathText](../)
* کتابخانه [Aspose.Slides](../../)