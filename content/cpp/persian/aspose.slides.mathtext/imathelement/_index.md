---
title: IMathElement
second_title: Aspose.Slides برای C++ مرجع API
description: "رابط پایهٔ هر عنصر ریاضیاتی: کسر، متن ریاضی، تابع، عبارت با چندین عنصر و غیره"
type: docs
weight: 222
url: /fa/aspose.slides.mathtext/imathelement/
---
## کلاس IMathElement

رابط پایهٔ هر عنصر ریاضیاتی: کسر، متن ریاضی، تابع، عبارت شامل چندین عنصر و غیره

```cpp
class IMathElement : public virtual System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](./accent/)(char16_t) | یک علامت تلفظ تنظیم می‌کند (یک کاراکتر در بالای این عنصر) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](./asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](./asargumentoffunction/)([System::String](../../system/string/)) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](./asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](./asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافی مشخص می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](./asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) | تابع مشخص شده را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافی مشخص می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](./divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | کسر را با صورت این عنصر و مخرج مشخص می‌سازد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](./divide/)([System::String](../../system/string/)) | کسر را با صورت این عنصر و مخرج مشخص می‌سازد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](./divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [MathFractionTypes](../mathfractiontypes/)) | کسر از نوع مشخص را با صورت این عنصر و مخرج مشخص می‌سازد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](./divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) | کسر از نوع مشخص را با صورت این عنصر و مخرج مشخص می‌سازد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](./enclose/)() | یک عنصر ریاضی را در پرانتز قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](./enclose/)(char16_t, char16_t) | این عنصر را در کاراکترهای مشخص (مانند پرانتز یا کاراکترهای دیگر) به عنوان قاب می‌گیرد |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیا را با استفاده از منطق [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیا از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیا از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند به‌گونه‌ای که دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند به‌گونه‌ای که دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](./function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | تابعی از یک آرگومان را با استفاده از این نمونه به عنوان نام تابع می‌گیرد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](./function/)([System::String](../../system/string/)) | تابعی از یک آرگومان را با استفاده از این نمونه به عنوان نام تابع می‌گیرد. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>\> [GetChildren](./getchildren/)() | عناصر فرزند را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیا سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](./group/)() | این عنصر را با استفاده از یک کروشهٔ پایین در یک گروه قرار می‌دهد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](./group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) | این عنصر را با استفاده از یک کاراکتر گروهی مانند کروشهٔ پایین یا دیگری در یک گروه قرار می‌دهد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](./integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [MathLimitLocations](../mathlimitlocations/)) | انتگرال را می‌گیرد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](./integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | انتگرال را می‌گیرد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](./integral/)([MathIntegralTypes](../mathintegraltypes/)) | انتگرال را بدون حدود می‌گیرد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](./integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) | انتگرال را می‌گیرد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](./integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | انتگرال را می‌گیرد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](./join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | یک عنصر ریاضیاتی را ترکیب می‌کند و یک بلوک ریاضی ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](./join/)([System::String](../../system/string/)) | یک متن ریاضیاتی را ترکیب می‌کند و یک بلوک ریاضی ایجاد می‌کند. |
| void [Lock](../../system/object/lock/)() | قفل کردن بر پایهٔ دستور lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده گردد. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان شبیه‌سازی انواع سفارشی را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](./nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | یک عملگر N-ارگی ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](./nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | یک عملگر N-ارگی ایجاد می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](./overbar/)() | نوار بر روی بالای این عنصر را تنظیم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](./radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | ریشهٔ ریاضیاتی از درجه داده شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](./radical/)([System::String](../../system/string/)) | ریشهٔ ریاضیاتی از درجه داده شده را از آرگومان مشخص‌شده تعیین می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیا را به‌صورت مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیا را به‌صورت مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ ارجاع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](./setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | حد پایین را می‌گیرد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](./setlowerlimit/)([System::String](../../system/string/)) | حد پایین را می‌گیرد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](./setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | زیرنوشته ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](./setsubscript/)([System::String](../../system/string/)) | زیرنوشته ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](./setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | زیرنوشته و بالانوشته را در سمت چپ ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](./setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) | زیرنوشته و بالانوشته را در سمت چپ ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](./setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | زیرنوشته و بالانوشته را در سمت راست ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](./setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) | زیرنوشته و بالانوشته را در سمت راست ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](./setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | بالانوشته ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](./setsuperscript/)([System::String](../../system/string/)) | بالانوشته ایجاد می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعیف را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](./setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | حد بالا را می‌گیرد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](./setupperlimit/)([System::String](../../system/string/)) | حد بالا را می‌گیرد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](./toborderbox/)() | این عنصر را در یک جعبهٔ حاشیه‌ای قرار می‌دهد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](./toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) | این عنصر را در یک جعبهٔ حاشیه‌ای قرار می‌دهد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](./tobox/)() | این عنصر را در یک جعبهٔ غیر‌دیداری (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی اجزای یک معادله یا سایر نمونه‌های متن ریاضی استفاده می‌شود. یک شیء جعبه‌بندی‌شده می‌تواند (به عنوان مثال) به عنوان شبیه‌ساز عامل با یا بدون نقطهٔ تراز، به عنوان نقطهٔ شکست خط، یا به‌گونه‌ای گروه‌بندی شود که اجازهٔ شکست خط درون آن را ندهد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](./tomatharray/)() | در یک آرایهٔ عمودی قرار می‌دهد. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیا سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](./underbar/)() | نوار بر روی پایین این عنصر را تنظیم می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی بر پایهٔ دستور lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده گردد. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## ملاحظات

مثال: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
```

## مراجع

* کلاس [Object](../../system/object/)
* فضای نام [Aspose::Slides::MathText](../)
* کتابخانه [Aspose.Slides](../../)