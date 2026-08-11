---
title: IMathBorderBox
second_title: Aspose.Slides برای C++ مرجع API
description: یک مرز مستطیلی یا نوع دیگری از مرز را دور IMathElement می‌کشد.
type: docs
weight: 144
url: /fa/aspose.slides.mathtext/imathborderbox/
---
## کلاس IMathBorderBox

یک مرز مستطیلی یا نوع دیگری از مرز را دور [IMathElement](../imathelement/) می‌کشد.

```cpp
class IMathBorderBox : public virtual Aspose::Slides::MathText::IMathElement
```

## متدها

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../imathelement/accent/)(char16_t) | یک علامت تلفظ (یک کاراکتر در بالای این عنصر) را تنظیم می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | تابع مشخص‌شده‌ای را می‌گیرد و این نمونه را به عنوان آرگومان استفاده می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::String](../../system/string/)) | تابع مشخص‌شده‌ای را می‌گیرد و این نمونه را به عنوان آرگومان استفاده می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) | تابع مشخص‌شده‌ای را می‌گیرد و این نمونه را به عنوان آرگومان استفاده می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | تابع مشخص‌شده‌ای را می‌گیرد و این نمونه را به عنوان آرگومان و یک آرگومان اضافهٔ مشخص‌شده استفاده می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) | تابع مشخص‌شده‌ای را می‌گیرد و این نمونه را به عنوان آرگومان و یک آرگومان اضافهٔ مشخص‌شده استفاده می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | کسر را با صورت این عنصر و مخرج مشخص‌شده ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/)) | کسر را با صورت این عنصر و مخرج مشخص‌شده ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) | کسر از نوع مشخص‌شده را با صورت این عنصر و مخرج مشخص‌شده ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) | کسر از نوع مشخص‌شده را با صورت این عنصر و مخرج مشخص‌شده ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)() | یک عنصر ریاضی را در پرانتز قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)(char16_t, char16_t) | این عنصر را در کاراکترهای مشخص‌شده مانند پرانتز یا کاراکترهای دیگر به عنوان قاب قرار می‌دهد |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناوری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ‌ارزشی، از جمله NaN نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناوری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ‌ارزشی، از جمله NaN نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | تابعی از یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع به کار می‌رود |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::String](../../system/string/)) | تابعی از یک آرگومان می‌گیرد که این نمونه به عنوان نام تابع به کار می‌رود |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Base](./get_base/)() | آرگومان پایه |
| virtual **bool** [get_HideBottom](./get_hidebottom/)() | پنهان کردن لبهٔ پایین (به‌طور پیش‌فرض false) - وضعیت مخفی یا نمایش داده شدهٔ لبهٔ پایین جعبهٔ مرزی را مشخص می‌کند. |
| virtual **bool** [get_HideLeft](./get_hideleft/)() | پنهان کردن لبهٔ چپ (به‌طور پیش‌فرض false) - وضعیت مخفی یا نمایش داده شدهٔ لبهٔ چپ جعبهٔ مرزی را مشخص می‌کند. |
| virtual **bool** [get_HideRight](./get_hideright/)() | پنهان کردن لبهٔ راست (به‌طور پیش‌فرض false) - وضعیت مخفی یا نمایش داده شدهٔ لبهٔ راست جعبهٔ مرزی را مشخص می‌کند. |
| virtual **bool** [get_HideTop](./get_hidetop/)() | پنهان کردن لبهٔ بالا (به‌طور پیش‌فرض false) - وضعیت مخفی یا نمایش داده شدهٔ لبهٔ بالا جعبهٔ مرزی را مشخص می‌کند. |
| virtual **bool** [get_StrikethroughBottomLeftToTopRight](./get_strikethroughbottomlefttotopright/)() | خط مورب از پایین-چپ به بالا-راست (به‌طور پیش‌فرض false). وضعیت مخفی یا نمایش داده شدهٔ یک خط مورب از گوشهٔ پایین-چپ به گوشهٔ بالا-راست جعبهٔ مرزی را مشخص می‌کند. |
| virtual **bool** [get_StrikethroughHorizontal](./get_strikethroughhorizontal/)() | خط افقی (به‌طور پیش‌فرض false) - وضعیت مخفی یا نمایش داده شدهٔ یک خط افقی خط خورده را مشخص می‌کند. |
| virtual **bool** [get_StrikethroughTopLeftToBottomRight](./get_strikethroughtoplefttobottomright/)() | خط مورب از بالا-چپ به پایین-راست (به‌طور پیش‌فرض false). وضعیت مخفی یا نمایش داده شدهٔ یک خط مورب از گوشهٔ بالا-چپ به گوشهٔ پایین-راست جعبهٔ مرزی را مشخص می‌کند. |
| virtual **bool** [get_StrikethroughVertical](./get_strikethroughvertical/)() | خط عمودی (به‌طور پیش‌فرض false) - وضعیت مخفی یا نمایش داده شدهٔ یک خط عمودی خط خورده را مشخص می‌کند. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](../imathelement/getchildren/)() | دریافت عناصر فرزند |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)() | این عنصر را با استفاده از یک پرانتز خمیدهٔ پایین در یک گروه قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) | این عنصر را با استفاده از کاراکتر گروه‌بندی مانند پرانتز خمیدهٔ پایین یا کاراکتر دیگر در یک گروه قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) | انتگرال را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | انتگرال را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/)) | انتگرال را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) | انتگرال را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | انتگرال را می‌گیرد |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نشانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | یک عنصر ریاضی را ترکیب می‌کند و یک بلوک ریاضی تشکیل می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::String](../../system/string/)) | یک متن ریاضی را ترکیب می‌کند و یک بلوک ریاضی تشکیل می‌دهد |
| void [Lock](../../system/object/lock/)() | اجرای قفل کردن با دستور lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | یک اپراتور N-ary ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | یک اپراتور N-ary ایجاد می‌کند |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌نماید. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را می‌دهد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../imathelement/overbar/)() | یک میله در بالای این عنصر تنظیم می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | ریشهٔ ریاضی از درجهٔ داده شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::String](../../system/string/)) | ریشهٔ ریاضی از درجهٔ داده شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_HideBottom](./set_hidebottom/)(**bool**) | پنهان کردن لبهٔ پایین (به‌طور پیش‌فرض false) - وضعیت مخفی یا نمایش داده شدهٔ لبهٔ پایین جعبهٔ مرزی را مشخص می‌کند. |
| virtual void [set_HideLeft](./set_hideleft/)(**bool**) | پنهان کردن لبهٔ چپ (به‌طور پیش‌فرض false) - وضعیت مخفی یا نمایش داده شدهٔ لبهٔ چپ جعبهٔ مرزی را مشخص می‌کند. |
| virtual void [set_HideRight](./set_hideright/)(**bool**) | پنهان کردن لبهٔ راست (به‌طور پیش‌فرض false) - وضعیت مخفی یا نمایش داده شدهٔ لبهٔ راست جعبهٔ مرزی را مشخص می‌کند. |
| virtual void [set_HideTop](./set_hidetop/)(**bool**) | پنهان کردن لبهٔ بالا (به‌طور پیش‌فرض false) - وضعیت مخفی یا نمایش داده شدهٔ لبهٔ بالا جعبهٔ مرزی را مشخص می‌کند. |
| virtual void [set_StrikethroughBottomLeftToTopRight](./set_strikethroughbottomlefttotopright/)(**bool**) | خط مورب از پایین-چپ به بالا-راست (به‌طور پیش‌فرض false). وضعیت مخفی یا نمایش داده شدهٔ یک خط مورب از گوشهٔ پایین-چپ به گوشهٔ بالا-راست جعبهٔ مرزی را مشخص می‌کند. |
| virtual void [set_StrikethroughHorizontal](./set_strikethroughhorizontal/)(**bool**) | خط افقی (به‌طور پیش‌فرض false) - وضعیت مخفی یا نمایش داده شدهٔ یک خط افقی خط خورده را مشخص می‌کند. |
| virtual void [set_StrikethroughTopLeftToBottomRight](./set_strikethroughtoplefttobottomright/)(**bool**) | خط مورب از بالا-چپ به پایین-راست (به‌طور پیش‌فرض false). وضعیت مخفی یا نمایش داده شدهٔ یک خط مورب از گوشهٔ بالا-چپ به گوشهٔ پایین-راست جعبهٔ مرزی را مشخص می‌کند. |
| virtual void [set_StrikethroughVertical](./set_strikethroughvertical/)(**bool**) | خط عمودی (به‌طور پیش‌فرض false) - وضعیت مخفی یا نمایش داده شدهٔ یک خط عمودی خط خورده را مشخص می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | حد پایین را دریافت می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::String](../../system/string/)) | حد پایین را دریافت می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | زیرنویس ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::String](../../system/string/)) | زیرنویس ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | زیرنویس و بالا نویس را در سمت چپ ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) | زیرنویس و بالا نویس را در سمت چپ ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | زیرنویس و بالا نویس را در سمت راست ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) | زیرنویس و بالا نویس را در سمت راست ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | بالا نویس ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::String](../../system/string/)) | بالا نویس ایجاد می‌کند |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تعویض اشاره‌گرها در سازندها به حالت ضعیف را فراهم می‌آورد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | حد بالا را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::String](../../system/string/)) | حد بالا را می‌گیرد |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](./)\> [ToBorderBox](../imathelement/toborderbox/)() | این عنصر را در یک جعبهٔ مرزی قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](./)\> [ToBorderBox](../imathelement/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) | این عنصر را در یک جعبهٔ مرزی قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../imathelement/tobox/)() | این عنصر را در یک جعبهٔ غیر‌نمایشی (گروه‌بندی منطقی) که برای گروه‌بندی مؤلفه‌های یک معادله یا متن ریاضی دیگر استفاده می‌شود، قرار می‌دهد. یک شیء جعبه‌ای می‌تواند (به‌عنوان مثال) به‌عنوان یک شبیه‌ساز عملگر با یا بدون نقطهٔ تنظیم، به‌عنوان نقطهٔ شکست خط، یا به‌صورت گروه‌بندی شده برای جلوگیری از شکست خط درون خود عمل کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../imathelement/tomatharray/)() | در یک آرایهٔ عمودی قرار می‌دهد |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../imathelement/underbar/)() | یک میله در پایین این عنصر تنظیم می‌کند |
| void [Unlock](../../system/object/unlock/)() | اجرای باز کردن قفل با دستور lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## ملاحظات

مثال: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## ارجاعات

* کلاس [IMathElement](../imathelement/)
* فضای نام [Aspose::Slides::MathText](../)
* کتابخانه [Aspose.Slides](../../)