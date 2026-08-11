---
title: TextFrame
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر یک TextFrame است.
type: docs
weight: 5448
url: /fa/aspose.slides/textframe/
---
## کلاس TextFrame

نمایانگر یک [TextFrame](./) است.

```cpp
class TextFrame : public Aspose::Slides::ITextFrame,
                  public Aspose::Slides::IDOMObject
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیا را با استفاده از معنی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیای نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیای نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به عنوان برابر در نظر گرفته می‌شوند حتی اگر بر اساس IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به عنوان برابر در نظر گرفته می‌شوند حتی اگر بر اساس IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() override | دسترسی آسان به پیوندهای موجود را فراهم می‌کند. فقط‌خواندنی [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraph](../iparagraph/)\> [get_Paragraph](./get_paragraph/)(**int32_t**) override | یک Paragraph را در یک فریم در اندیس مشخص برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphCollection](../iparagraphcollection/)\> [get_Paragraphs](./get_paragraphs/)() override | فهرست تمام Paragraph‌ها را در یک فریم برمی‌گرداند. فقط‌خواندنی [IParagraphCollection](../iparagraphcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [get_ParentCell](./get_parentcell/)() override | Cell والد را برمی‌گرداند یا null اگر شی والد رابط [ICell](../icell/) را پیاده‌سازی نکند. فقط‌خواندنی [ICell](../icell/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_ParentShape](./get_parentshape/)() override | Shape والد را برمی‌گرداند یا null اگر شی والد رابط [IShape](../ishape/) را پیاده‌سازی نکند. فقط‌خواندنی [IShape](../ishape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Presentation والد یک [TextFrame](./) را برمی‌گرداند. فقط‌خواندنی [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | Slide والد یک [TextFrame](./) را برمی‌گرداند. فقط‌خواندنی [IBaseSlide](../ibaseslide/). |
| [System::String](../../system/string/) [get_Text](./get_text/)() override | متن ساده یک [TextFrame](./) را دریافت می‌کند. فقط‌خواندنی [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\> [get_TextFrameFormat](./get_textframeformat/)() override | شیء قالب‌بندی برای این شیء [TextFrame](./) را برمی‌گرداند. فقط‌خواندنی [ITextFrameFormat](../itextframeformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش C# [Object.GetHashCode()](../../system/object/gethashcode/) است. هش‌سازی اشیای سفارشی را امکان‌پذیر می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| void [HighlightRegex](./highlightregex/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[ITextHighlightingOptions](../itexthighlightingoptions/)\>) override | تمام تطابق‌های عبارت منظم را با رنگ مشخص برجسته می‌کند. |
| void [HighlightRegex](./highlightregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | تمام تطابق‌های عبارت منظم را با رنگ مشخص برجسته می‌کند. |
| void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/)) override | تمام تطابق‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[ITextHighlightingOptions](../itexthighlightingoptions/)\>) override | تمام تطابق‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | تمام تطابق‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() override | بخش‌های (runs) دارای قالب‌بندی یکسان را در تمام Paragraph‌ها ترکیب می‌کند. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با عبارت C# lock() را پیاده‌سازی می‌کند. مستقیم فراخوانی شود یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) است. امکان تکثیر (clone) انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت زیرکلاس‌ها توسط کپی‌ساز را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت زیرکلاس‌ها توسط کپی‌ساز را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیا را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیا را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را به‌صورت مرجعی با nullptr مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [ReplaceRegex](./replaceregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | تمام تطابق‌های عبارت منظم را با رشته مشخص جایگزین می‌کند. |
| void [ReplaceText](./replacetext/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | تمام رخدادهای متن مشخص را با متن دیگری که مشخص شده است جایگزین می‌کند. |
| void [set_Text](./set_text/)([System::String](../../system/string/)) override | متن ساده یک [TextFrame](./) را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [SplitTextByColumns](./splittextbycolumns/)() override | محتواِ متنی [ITextFrame](../itextframe/) را به آرایه‌ای از رشته‌ها تقسیم می‌کند، 

 که هر عنصر متناظر با یک ستون متن جداگانه درون فریم است. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش C# [Object.ToString()](../../system/object/tostring/) است. امکان تبدیل اشیای سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری را لغو می‌کند (unlock) در عبارت C# lock(). مستقیم فراخوانی شود یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## مراجع

* کلاس [ITextFrame](../itextframe/)
* کلاس [IDOMObject](../idomobject/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)