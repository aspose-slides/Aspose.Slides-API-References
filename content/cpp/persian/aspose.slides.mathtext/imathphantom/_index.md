---
title: IMathPhantom
second_title: مرجع API Aspose.Slides برای C++
description: "نمایش یک شیء ریاضی فانتوم (<m:phant>) که چیدمان عنصر فرزند آن را تحت تأثیر قرار می‌دهد بدون اینکه لزوماً آن را نمایش دهد. فانتوم می‌تواند عبارت پایه خود را مخفی کند در حالی که عرض، ارتفاع یا عمق آن را حفظ می‌کند تا فرمول‌ها را هم‌تراز کند یا فضا رزرو نماید. قابلیت نمایش و رفتار هندسی توسط ویژگی‌هایی مانند Show، ZeroWid، ZeroAsc، ZeroDesc و Transp کنترل می‌شود."
type: docs
weight: 482
url: /fa/aspose.slides.mathtext/imathphantom/
---
## IMathPhantom کلاس


نمایش یک شیء ریاضی فانتوم (<m:phant>) که چیدمان عنصر فرزند آن را تحت تأثیر قرار می‌دهد بدون اینکه لزوماً آن را نمایش دهد. فانتوم می‌تواند عبارت پایه خود را مخفی کند در حالی که عرض، ارتفاع یا عمق آن را حفظ می‌کند تا فرمول‌ها را هم‌تراز کند یا فضای مورد نیاز را رزرو نماید. قابلیت نمایش و رفتار هندسی توسط ویژگی‌هایی مانند Show، ZeroWid، ZeroAsc، ZeroDesc و Transp کنترل می‌شود.

```cpp
class IMathPhantom : public virtual Aspose::Slides::MathText::IMathElement
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../imathelement/accent/)(char16_t) | یک علامت لهجه (یک کاراکتر در بالای این عنصر) را تنظیم می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | تابع مشخص شده را گرفته و این نمونه را به عنوان آرگومان استفاده می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::String](../../system/string/)) | تابع مشخص شده را گرفته و این نمونه را به عنوان آرگومان استفاده می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) | تابع مشخص شده را گرفته و این نمونه را به عنوان آرگومان استفاده می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | تابع مشخص شده را گرفته و این نمونه را به عنوان آرگومان به کار می‌برد و آرگومان اضافهٔ مشخص‌شده‌ای را نیز می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) | تابع مشخص شده را گرفته و این نمونه را به عنوان آرگومان به کار می‌برد و آرگومان اضافهٔ مشخص‌شده‌ای را نیز می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | یک کسر با صورت این نمونه و مخرج مشخص‌شده ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/)) | یک کسر با صورت این نمونه و مخرج مشخص‌شده ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) | کسر از نوع مشخص‌شده با صورت این نمونه و مخرج مشخص‌شده ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) | کسر از نوع مشخص‌شده با صورت این نمونه و مخرج مشخص‌شده ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)() | یک عنصر ریاضی را در پرانتز می‌پیچد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)(char16_t, char16_t) | این عنصر را در کاراکترهای مشخص‌شده مانند پرانتز یا سایر کاراکترها به عنوان قاب می‌پیچد |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از سمانتیک C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای کاربردهای داخلی. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | تابعی از یک آرگومان می‌گیرد که این نمونه به‌عنوان نام تابع استفاده می‌شود |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::String](../../system/string/)) | تابعی از یک آرگومان می‌گیرد که این نمونه به‌عنوان نام تابع استفاده می‌شود |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Base](./get_base/)() | آرگومان پایه |
| virtual **bool** [get_Show](./get_show/)() | مقداری را که نشان می‌دهد آیا عنصر پایه نمایش داده می‌شود بر می‌گرداند. |
| virtual **bool** [get_Transp](./get_transp/)() | مقداری را که نشان می‌دهد آیا فانتوم برای قوانین فاصله‌گذاری مبتنی بر کلاس شفاف است بر می‌گرداند. |
| virtual **bool** [get_ZeroAsc](./get_zeroasc/)() | مقداری را که نشان می‌دهد آیا ارتفاع بالایی (ارتفاع بالای خط پایه) عنصر پایه باید به‌عنوان صفر در نظر گرفته شود بر می‌گرداند. |
| virtual **bool** [get_ZeroDesc](./get_zerodesc/)() | مقداری را که نشان می‌دهد آیا نزول (عمق زیر خط پایه) عنصر پایه باید به‌عنوان صفر در نظر گرفته شود بر می‌گرداند. |
| virtual **bool** [get_ZeroWidth](./get_zerowidth/)() | مقداری را که نشان می‌دهد آیا عرض عنصر پایه باید به‌عنوان صفر در نظر گرفته شود بر می‌گرداند. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](../imathelement/getchildren/)() | دریافت عناصر فرزندان |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارندهٔ مرجع مرتبط با شیء را بر می‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را بر می‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)() | این عنصر را با استفاده از یک کروشهٔ پایین در یک گروه قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) | این عنصر را با استفاده از کاراکترهای گروه‌بندی مانند کروشهٔ پایین یا کاراکترهای دیگر در یک گروه قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) | انتگرال را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | انتگرال را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/)) | انتگرال را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) | انتگرال را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | انتگرال را می‌گیرد |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | یک عنصر ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::String](../../system/string/)) | یک متن ریاضی را می‌پیوندد و یک بلوک ریاضی تشکیل می‌دهد |
| void [Lock](../../system/object/lock/)() | بیانیهٔ قفل‌گذاری C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون کردن انواع سفارشی را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | یک عملگر چندآرگی ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | یک عملگر چندآرگی ایجاد می‌کند |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. واقعاً چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. واقعاً چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از زیرکلاس‌ها را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../imathelement/overbar/)() | نوار را در بالای این عنصر قرار می‌دهد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | ریشهٔ ریاضی درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::String](../../system/string/)) | ریشهٔ ریاضی درجهٔ داده‌شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار نوع مقدار را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_Show](./set_show/)(**bool**) | مقدار را که نشان می‌دهد آیا عنصر پایه نمایش داده می‌شود تنظیم می‌کند. |
| virtual void [set_Transp](./set_transp/)(**bool**) | مقدار را که نشان می‌دهد آیا فانتوم برای قوانین فاصله‌گذاری مبتنی بر کلاس شفاف است تنظیم می‌کند. |
| virtual void [set_ZeroAsc](./set_zeroasc/)(**bool**) | مقدار را که نشان می‌دهد آیا ارتفاع بالایی (ارتفاع بالای خط پایه) عنصر پایه باید به‌عنوان صفر در نظر گرفته شود تنظیم می‌کند. |
| virtual void [set_ZeroDesc](./set_zerodesc/)(**bool**) | مقدار را که نشان می‌دهد آیا نزول (عمق زیر خط پایه) عنصر پایه باید به‌عنوان صفر در نظر گرفته شود تنظیم می‌کند. |
| virtual void [set_ZeroWidth](./set_zerowidth/)(**bool**) | مقدار را که نشان می‌دهد آیا عرض عنصر پایه باید به‌عنوان صفر در نظر گرفته شود تنظیم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | حد پایین را می‌گیرد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::String](../../system/string/)) | حد پایین را می‌گیرد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | زیرنویس ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::String](../../system/string/)) | زیرنویس ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) | زیرنویس و بالانویس را در سمت چپ ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) | زیرنویس و بالانویس را در سمت راست ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | بالانویس ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::String](../../system/string/)) | بالانویس ایجاد می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان سوئیچ کردن اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | حد بالا را می‌گیرد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::String](../../system/string/)) | حد بالا را می‌گیرد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را بر می‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و بر می‌گرداند. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)() | این عنصر را در یک جعبهٔ حاشیه‌دار قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) | این عنصر را در یک جعبهٔ حاشیه‌دار قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../imathelement/tobox/)() | این عنصر را در یک جعبهٔ غیر‌دیداری (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی اجزای یک معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود. یک شیء جعبه‌دار می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عملگر با یا بدون نقطهٔ تراز عمل کند، به عنوان نقطهٔ شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که اجازهٔ شکست خط داخل آن داده نشود. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../imathelement/tomatharray/)() | در یک آرایهٔ عمودی قرار می‌دهد |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../imathelement/underbar/)() | نوار را در پایین این عنصر قرار می‌دهد. |
| void [Unlock](../../system/object/unlock/)() | بیانیهٔ قفل‌گذاری C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را تخریب می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## ملاحظات


مثال: 
```cpp
System::SharedPtr<IMathPhantom> phantom = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"1/2"));
phantom->set_Show(false); // مخفی کردن محتوا
phantom->set_ZeroWidth(false); // عرض را حفظ کنید
```

## نگاه کنید به

* کلاس [IMathElement](../imathelement/)
* فضای‌نام [Aspose::Slides::MathText](../)
* کتابخانه [Aspose.Slides](../../)