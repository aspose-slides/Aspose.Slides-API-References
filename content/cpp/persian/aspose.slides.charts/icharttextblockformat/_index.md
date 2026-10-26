---
title: IChartTextBlockFormat
second_title: مرجع API Aspose.Slides برای C++
description: ویژگی‌های قالب‌بندی برای عناصر متنی نمودار را نمایندگی می‌کند.
type: docs
weight: 885
url: /fa/aspose.slides.charts/icharttextblockformat/
---
## IChartTextBlockFormat کلاس

نمایش‌دهندهٔ ویژگی‌های قالب‌بندی برای عناصر متنی نمودار.

```cpp
class IChartTextBlockFormat : public virtual System::Object
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از C# [Object.Equals](../../system/object/equals/) سیمانتیک مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [TextAnchorType](../../aspose.slides/textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | متن لنگر عمودی را در یک [TextFrame](../../aspose.slides/textframe/) برمی‌گرداند. مطالعه کنید [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual [TextAutofitType](../../aspose.slides/textautofittype/) [get_AutofitType](./get_autofittype/)() | حالت خودانطباق متن را برمی‌گرداند. تغییر این ویژگی ممکن است فقط برای این بخش‌های نمودار تأثیر داشته باشد: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ اثری برای رندر ندارد). مطالعه کنید [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_CenterText](./get_centertext/)() | اگر [NullableBool::True](../../aspose.slides/nullablebool/) متن باید به صورت افقی در جعبه وسط‌چین شود. مطالعه کنید [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | حاشیهٔ پایین (نقطه) را در یک [TextFrame](../../aspose.slides/textframe/) برمی‌گرداند. تغییر این ویژگی ممکن است فقط برای این بخش‌های نمودار تأثیر داشته باشد: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ اثری برای رندر ندارد). مطالعه کنید **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | حاشیهٔ چپ (نقطه) را در یک [TextFrame](../../aspose.slides/textframe/) برمی‌گرداند. تغییر این ویژگی ممکن است فقط برای این بخش‌های نمودار تأثیر داشته باشد: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ اثری برای رندر ندارد). مطالعه کنید **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | حاشیهٔ راست (نقطه) را در یک [TextFrame](../../aspose.slides/textframe/) برمی‌گرداند. تغییر این ویژگی ممکن است فقط برای این بخش‌های نمودار تأثیر داشته باشد: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ اثری برای رندر ندارد). مطالعه کنید **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | حاشیهٔ بالا (نقطه) را در یک [TextFrame](../../aspose.slides/textframe/) برمی‌گرداند. تغییر این ویژگی ممکن است فقط برای این بخش‌های نمودار تأثیر داشته باشد: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ اثری برای رندر ندارد). مطالعه کنید **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | چرخش سفارشی که بر روی متن درون جعبه مرزی اعمال می‌شود را مشخص می‌کند. اگر مشخص نشود، چرخش شکل همراه استفاده می‌شود. اگر مشخص شود، مستقل از شکل اعمال می‌شود. یعنی شکل می‌تواند چرخش داشته باشد علاوه بر این که متن خود نیز چرخش داشته باشد. مقدار نهایی چرخش بصری متن که از ترکیب این ویژگی و نوع عمودی از پیش تعریف‌شده در ویژگی TextVerticalType به دست می‌آید. مطالعه کنید **float**. |
| virtual [Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | جهت‌گیری متن را تعیین می‌کند. مقدار نهایی چرخش بصری متن که از ترکیب این ویژگی و زاویه سفارشی در ویژگی RotationAngle به دست می‌آید. مطالعه کنید [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_WrapText](./get_wraptext/)() | True در صورتی که متن در حاشیه‌های [TextFrame](../../aspose.slides/textframe/) بسته شود. تغییر این ویژگی ممکن است فقط برای این بخش‌های نمودار تأثیر داشته باشد: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (پشتیبانی کامل در PowerPoint 2007/2013). مطالعه کنید [NullableBool](../../aspose.slides/nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نمونه‌ای از متد C# [Object.GetHashCode()](../../system/object/gethashcode/). هش‌گذاری اشیاء سفارشی را فعال می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. نمونه‌ای از فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوعی است که توسط targetType توصیف شده. نمونه‌ای از عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری توسط عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء دیده‌بان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نمونه‌ای از متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان شبیه‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها را با کپی فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها را با کپی فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار نوع شیء را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | خصوصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | خصوصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../../aspose.slides/textanchortype/)) | متن لنگر عمودی را در یک [TextFrame](../../aspose.slides/textframe/) تنظیم می‌کند. نویسید [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../../aspose.slides/textautofittype/)) | حالت خودانطباق متن را تنظیم می‌کند. تغییر این ویژگی ممکن است فقط برای این بخش‌های نمودار تأثیر داشته باشد: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ اثری برای رندر ندارد). نویسید [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../../aspose.slides/nullablebool/)) | اگر [NullableBool::True](../../aspose.slides/nullablebool/) متن باید به صورت افقی در جعبه وسط‌چین شود. نویسید [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | حاشیهٔ پایین (نقطه) را در یک [TextFrame](../../aspose.slides/textframe/) تنظیم می‌کند. تغییر این ویژگی ممکن است فقط برای این بخش‌های نمودار تأثیر داشته باشد: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ اثری برای رندر ندارد). نویسید **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | حاشیهٔ چپ (نقطه) را در یک [TextFrame](../../aspose.slides/textframe/) تنظیم می‌کند. تغییر این ویژگی ممکن است فقط برای این بخش‌های نمودار تأثیر داشته باشد: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ اثری برای رندر ندارد). نویسید **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | حاشیهٔ راست (نقطه) را در یک [TextFrame](../../aspose.slides/textframe/) تنظیم می‌کند. تغییر این ویژگی ممکن است فقط برای این بخش‌های نمودار تأثیر داشته باشد: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ اثری برای رندر ندارد). نویسید **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | حاشیهٔ بالا (نقطه) را در یک [TextFrame](../../aspose.slides/textframe/) تنظیم می‌کند. تغییر این ویژگی ممکن است فقط برای این بخش‌های نمودار تأثیر داشته باشد: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (پشتیبانی کامل در PowerPoint 2013؛ در PowerPoint 2007 هیچ اثری برای رندر ندارد). نویسید **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | چرخش سفارشی که بر روی متن درون جعبه مرزی اعمال می‌شود را مشخص می‌کند. اگر مشخص نشود، چرخش شکل همراه استفاده می‌شود. اگر مشخص شود، مستقل از شکل اعمال می‌شود. یعنی شکل می‌تواند چرخش داشته باشد علاوه بر این که متن خود نیز چرخش داشته باشد. مقدار نهایی چرخش بصری متن که از ترکیب این ویژگی و نوع عمودی از پیش تعریف‌شده در ویژگی TextVerticalType به دست می‌آید. نویسید **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/)) | جهت‌گیری متن را تعیین می‌کند. مقدار نهایی چرخش بصری متن که از ترکیب این ویژگی و زاویه سفارشی در ویژگی RotationAngle به دست می‌آید. نویسید [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../../aspose.slides/nullablebool/)) | True در صورتی که متن در حاشیه‌های [TextFrame](../../aspose.slides/textframe/) بسته شود. تغییر این ویژگی ممکن است فقط برای این بخش‌های نمودار تأثیر داشته باشد: [DataLabel](../datalabel/) و [DataLabelFormat](../datalabelformat/) (پشتیبانی کامل در PowerPoint 2007/2013). نویسید [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نمونه‌ای از متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | سازهٔ C# typeof([System.Object](../../system/object/)) را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای دستور C# lock() برای باز کردن قفل را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء دیده‌بان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را حذف می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## مراجع

* کلاس [Object](../../system/object/)
* فضای نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)