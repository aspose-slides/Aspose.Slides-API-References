---
title: IMathMatrix
second_title: Aspose.Slides برای مرجع API C++
description: شی Matrix را مشخص می‌کند که از عناصر فرزند تشکیل شده است که در یک یا چند ردیف و ستون چیدمان می‌شوند. مهم است که توجه داشته باشید ماتریس‌ها delimiters داخلی ندارند. برای قرار دادن ماتریس در براکت‌ها باید از شی delimiter (IMathDelimiter) استفاده کنید. می‌توانید از آرگومان‌های null برای ایجاد فواصل در ماتریس‌ها استفاده کنید.
type: docs
weight: 391
url: /fa/aspose.slides.mathtext/imathmatrix/
---
## کلاس IMathMatrix

Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. It is important to note that matrices do not have built in delimiters. To place the matrix in the brackets you should use the delimiter object ([IMathDelimiter](../imathdelimiter/)). Null arguments can be used to create gaps in matrices.

```cpp
class IMathMatrix : public virtual Aspose::Slides::MathText::IMathElement
```

## متدها

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../imathelement/accent/)(char16_t) | یک علامت ترکیبی تنظیم می‌کند (کاراکتری در بالای این عنصر) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | تابع مشخص‌شده‌ای را با استفاده از این نمونه به عنوان آرگومان فراخوانی می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::String](../../system/string/)) | تابع مشخص‌شده‌ای را با استفاده از این نمونه به عنوان آرگومان فراخوانی می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) | تابع مشخص‌شده‌ای را با استفاده از این نمونه به عنوان آرگومان فراخوانی می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | تابع مشخص‌شده‌ای را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافه‌ی مشخص‌شده فراخوانی می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) | تابع مشخص‌شده‌ای را با استفاده از این نمونه به عنوان آرگومان و آرگومان اضافه‌ی مشخص‌شده فراخوانی می‌کند |
| virtual void [DeleteColumn](./deletecolumn/)(**int32_t**) | ستون مشخص‌شده را حذف می‌کند |
| virtual void [DeleteRow](./deleterow/)(**int32_t**) | ردیف مشخص‌شده را حذف می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | کسر را با صورت این عنصر و مخرج مشخص‌شده ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/)) | کسر را با صورت این عنصر و مخرج مشخص‌شده ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) | کسر از نوع مشخص‌شده را با صورت این عنصر و مخرج مشخص‌شده ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) | کسر از نوع مشخص‌شده را با صورت این عنصر و مخرج مشخص‌شده ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)() | عنصر ریاضی را در پرانتز می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)(char16_t, char16_t) | این عنصر را در کاراکترهای مشخص‌شده‌ای مانند پرانتز یا سایر کاراکترها به‌عنوان قاب می‌گیرد |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که دو NaN برابر درنظر گرفته می‌شوند حتی اگر بر اساس IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که دو NaN برابر درنظر گرفته می‌شوند حتی اگر بر اساس IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | تابعی با یک آرگومان را با استفاده از این نمونه به عنوان نام تابع می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::String](../../system/string/)) | تابعی با یک آرگومان را با استفاده از این نمونه به عنوان نام تابع می‌گیرد |
| virtual [MathVerticalAlignment](../mathverticalalignment/) [get_BaseJustification](./get_basejustification/)() | توجیه عمودی نسبت به متن اطراف را تعیین می‌کند. مقادیر ممکن top، bottom و center هستند. پیش‌فرض: Center |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | تعداد ستون‌های ماتریس |
| virtual **uint32_t** [get_ColumnGap](./get_columngap/)() | مقدار فاصله افقی بین ستون‌های ماتریس؛ اگر ColumnGapRule برابر 3 (\"Exactly\") باشد، واحد به-صورت twips (۱/۲۰نقطه) تفسیر می‌شود. اگر ColumnGapRule برابر 4 (\"Multiple\") باشد، واحد به-صورت تعداد افزایش ۰٫۵ em تفسیر می‌شود. در سایر موارد نادیده گرفته می‌شود. پیش‌فرض: 0 |
| virtual [MathSpacingRules](../mathspacingrules/) [get_ColumnGapRule](./get_columngaprule/)() | نوع فاصله افقی بین ستون‌های ماتریس؛ واحدهای فاصله افقی می‌توانند em یا point باشند (به‌صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0) |
| virtual **bool** [get_HidePlaceholders](./get_hideplaceholders/)() | جای‌گیرهای عناصر خالی ماتریس را مخفی می‌کند پیش‌فرض: false |
| virtual **uint32_t** [get_MinColumnWidth](./get_mincolumnwidth/)() | حداقل عرض ستون به twips (۱/۲۰نقطه). فاصلهٔ شکاف (که «Column Gap» یا «Gap Width» نامیده می‌شود) به MinColumnWidth اضافه می‌شود تا کل فاصلهٔ [Column](../../aspose.slides/column/) ماتریس (فاصله بین لبه‌های مشابه ستون‌های مختلف) تعیین شود. پیش‌فرض: 0. |
| virtual **int32_t** [get_RowCount](./get_rowcount/)() | تعداد ردیف‌های ماتریس |
| virtual **uint32_t** [get_RowGap](./get_rowgap/)() | مقدار فاصله عمودی بین ردیف‌های ماتریس؛ اگر RowGapRule برابر 3 (\"Exactly\") باشد، واحد به-صورت twips تفسیر می‌شود. اگر RowGapRule برابر 4 (\"Multiple\") باشد، واحد به-صورت نیم‌خط تفسیر می‌شود. پیش‌فرض: 0 |
| virtual [MathSpacingRules](../mathspacingrules/) [get_RowGapRule](./get_rowgaprule/)() | نوع فاصله عمودی بین ردیف‌های ماتریس؛ واحدهای فاصله عمودی می‌توانند line یا point باشند (به‌صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0) |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](../imathelement/getchildren/)() | دریافت عناصر فرزند |
| virtual [MathHorizontalAlignment](../mathhorizontalalignment/) [GetColumnAlignment](./getcolumnalignment/)(**int32_t**) | دریافت تراز افقی ستون مشخص‌شده |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارنده مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)() | این عنصر را با یک آکولاد پایین در یک گروه قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) | این عنصر را با یک کاراکتر گروه‌بندی (مانند آکولاد پایین یا کاراکتر دیگری) در یک گروه قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) | عناصر ماتریس |
| virtual void [idx_set](./idx_set/)(**int32_t**, **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | عناصر ماتریس |
| virtual void [InsertColumnAfter](./insertcolumnafter/)(**int32_t**) | پس از ستون مشخص‌شده یک ستون جدید درج می‌کند. ابتدا تمام عناصر ستون جدید null هستند. |
| virtual void [InsertColumnBefore](./insertcolumnbefore/)(**int32_t**) | پیش از ستون مشخص‌شده یک ستون جدید درج می‌کند. ابتدا تمام عناصر ستون جدید null هستند. |
| virtual void [InsertRowAfter](./insertrowafter/)(**int32_t**) | پس از ردیف مشخص‌شده یک ردیف جدید درج می‌کند. ابتدا تمام عناصر ردیف جدید null هستند. |
| virtual void [InsertRowBefore](./insertrowbefore/)(**int32_t**) | پیش از ردیف مشخص‌شده یک ردیف جدید درج می‌کند. ابتدا تمام عناصر ردیف جدید null هستند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) | انتگرال را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | انتگرال را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/)) | انتگرال را بدون حدود می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) | انتگرال را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | انتگرال را می‌گیرد |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه عملگر C# 'is'. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | یک عنصر ریاضی را می‌پیوندد و بلوک ریاضی تشکیل می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::String](../../system/string/)) | متن ریاضی را می‌پیونده و بلوک ریاضی تشکیل می‌دهد |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی عبارت C# lock() برای قفل‌گذاری. به‌صورت مستقیم صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | یک عملگر N-ary ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | یک عملگر N-ary ایجاد می‌کند |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند؛ فقط شیء جدید را مقداردهی می‌کند و امکان ساختن زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند؛ فقط شیء جدید را مقداردهی می‌کند و امکان ساختن زیرکلاس‌ها را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../imathelement/overbar/)() | یک نوار در بالای این عنصر قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | ریشهٔ ریاضی به‌صورت درجهٔ داده‌شده از آرگومان مشخص‌شده را تعیین می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::String](../../system/string/)) | ریشهٔ ریاضی به‌صورت درجهٔ داده‌شده از آرگومان مشخص‌شده را تعیین می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را با مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را با مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr مقایسه مرجع می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارش مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_BaseJustification](./set_basejustification/)([MathVerticalAlignment](../mathverticalalignment/)) | توجیه عمودی نسبت به متن اطراف را تعیین می‌کند. مقادیر ممکن top، bottom و center هستند. پیش‌فرض: Center |
| virtual void [set_ColumnGap](./set_columngap/)(**uint32_t**) | مقدار فاصله افقی بین ستون‌های ماتریس؛ اگر ColumnGapRule برابر 3 (\"Exactly\") باشد، واحد به-صورت twips تفسیر می‌شود. اگر ColumnGapRule برابر 4 (\"Multiple\") باشد، واحد به-صورت تعداد افزایش ۰٫۵ em تفسیر می‌شود. در سایر موارد نادیده گرفته می‌شود. پیش‌فرض: 0 |
| virtual void [set_ColumnGapRule](./set_columngaprule/)([MathSpacingRules](../mathspacingrules/)) | نوع فاصله افقی بین ستون‌های ماتریس؛ واحدهای فاصله افقی می‌توانند em یا point باشند (به‌صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0) |
| virtual void [set_HidePlaceholders](./set_hideplaceholders/)(**bool**) | جای‌گیرهای عناصر خالی ماتریس را مخفی می‌کند پیش‌فرض: false |
| virtual void [set_MinColumnWidth](./set_mincolumnwidth/)(**uint32_t**) | حداقل عرض ستون به twips (۱/۲۰نقطه). فاصلهٔ شکاف (که «Column Gap» یا «Gap Width» نامیده می‌شود) به MinColumnWidth اضافه می‌شود تا کل فاصلهٔ [Column](../../aspose.slides/column/) ماتریس (فاصله بین لبه‌های مشابه ستون‌های مختلف) تعیین شود. پیش‌فرض: 0. |
| virtual void [set_RowGap](./set_rowgap/)(**uint32_t**) | مقدار فاصله عمودی بین ردیف‌های ماتریس؛ اگر RowGapRule برابر 3 (\"Exactly\") باشد، واحد به-صورت twips تفسیر می‌شود. اگر RowGapRule برابر 4 (\"Multiple\") باشد، واحد به-صورت نیم‌خط تفسیر می‌شود. پیش‌فرض: 0 |
| virtual void [set_RowGapRule](./set_rowgaprule/)([MathSpacingRules](../mathspacingrules/)) | نوع فاصله عمودی بین ردیف‌های ماتریس؛ واحدهای فاصله عمودی می‌توانند line یا point باشند (به‌صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0) |
| virtual void [SetColumnAlignment](./setcolumnalignment/)(**int32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) | تنظیم تراز افقی ستون مشخص‌شده |
| virtual void [SetColumnsAlignment](./setcolumnsalignment/)(**int32_t**, **uint32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) | تنظیم تراز افقی ستون‌های مشخص‌شده |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | حد پایین را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::String](../../system/string/)) | حد پایین را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | زیرنویس ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::String](../../system/string/)) | زیرنویس ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | زیرنویس و بالانویس در سمت چپ ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) | زیرنویس و بالانویس در سمت چپ ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | زیرنویس و بالانویس در سمت راست ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) | زیرنویس و بالانویس در سمت راست ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | بالانویس ایجاد می‌کند |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::String](../../system/string/)) | بالانویس ایجاد می‌کند |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف تنظیم می‌کند (به‌جای shared). امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را می‌دهد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | حد بالا را می‌گیرد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::String](../../system/string/)) | حد بالا را می‌گیرد |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)() | این عنصر را در یک جعبهٔ حاشیه‌ای قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) | این عنصر را در یک جعبهٔ حاشیه‌ای قرار می‌دهد |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../imathelement/tobox/)() | این عنصر را در یک جعبهٔ غیر‌دیداری (گروه‌بندی منطقی) قرار می‌دهد که برای گروه‌بندی مؤلفه‌های یک معادله یا سایر متن‌های ریاضی استفاده می‌شود. یک شیء جعبه‌ای می‌تواند (به عنوان مثال) به‌عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز عمل کند، به‌عنوان نقطهٔ شکست خط عمل کند یا به‌گونه‌ای گروه‌بندی شود که از شکست خط درون آن جلوگیری شود. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../imathelement/tomatharray/)() | در یک آرایهٔ عمودی قرار می‌دهد |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازهٔ C# typeof([System.Object](../../system/object/)). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../imathelement/underbar/)() | نوار زیر این عنصر را تنظیم می‌کند |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی عبارت C# lock() برای بازکردن قفل. به‌صورت مستقیم صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |
## توضیحات

مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## موارد مرتبط

* کلاس [IMathElement](../imathelement/)
* فضای‌نامی [Aspose::Slides::MathText](../)
* کتابخانه [Aspose.Slides](../../)