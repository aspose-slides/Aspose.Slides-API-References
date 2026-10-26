---
title: ITextFrameFormat
second_title: Aspose.Slides برای مرجع API C++
description: حاوی ویژگی‌های قالب‌بندی TextFrame است.
type: docs
weight: 4083
url: /fa/aspose.slides/itextframeformat/
---
## ITextFrameFormat کلاس

حاوی ویژگی‌های قالب‌بندی [TextFrame](../textframe/) است.

```cpp
class ITextFrameFormat : public virtual System::Object
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معانی [Object.Equals](../../system/object/equals/) زبان C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه‌ی نقطه شناور شبیه‌سازی شده به سبک C# را که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نباشد، شبیه‌سازی می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه‌ی نقطه شناور شبیه‌سازی شده به سبک C# را که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نباشد، شبیه‌سازی می‌کند. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | متن لنگر عمودی را در یک [TextFrame](../textframe/) برمی‌گرداند. برای جزئیات [TextAnchorType](../textanchortype/) را بخوانید. |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | حالت خودتنظیم متن را برمی‌گرداند. برای جزئیات [TextAutofitType](../textautofittype/) را بخوانید. |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | اگر [NullableBool::True](../nullablebool/) باشد، متن باید افقی در جعبه مرکزچین شود. برای جزئیات [NullableBool](../nullablebool/) را بخوانید. |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | تعداد ستون‌های ناحیهٔ متن را برمی‌گرداند. این مقدار باید عددی مثبت باشد؛ در غیر این صورت مقدار به صفر تنظیم می‌شود. مقدار ۰ به معنای مقدار تعریف‌نشده است. برای جزئیات **int32_t** را بخوانید. |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | فاصله بین ستون‌های متن در ناحیهٔ متن (به نقطه) را برمی‌گرداند. این تنها زمانی کاربرد دارد که بیش از یک ستون موجود باشد. این مقدار باید عددی مثبت باشد؛ در غیر این صورت به صفر تنظیم می‌شود. برای جزئیات **double** را بخوانید. |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | متن را به‌طور کامل از صحنهٔ 3-بعدی نگه می‌دارد یا تنظیم می‌کند. برای جزئیات **bool** را بخوانید. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | حاشیهٔ پایین (به نقطه) را در یک [TextFrame](../textframe/) برمی‌گرداند. برای جزئیات **double** را بخوانید. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | حاشیهٔ چپ (به نقطه) را در یک [TextFrame](../textframe/) برمی‌گرداند. برای جزئیات **double** را بخوانید. |
| virtual **double** [get_MarginRight](./get_marginright/)() | حاشیهٔ راست (به نقطه) را در یک [TextFrame](../textframe/) برمی‌گرداند. برای جزئیات **double** را بخوانید. |
| virtual **double** [get_MarginTop](./get_margintop/)() | حاشیهٔ بالا (به نقطه) را در یک [TextFrame](../textframe/) برمی‌گرداند. برای جزئیات **double** را بخوانید. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | چرخش سفارشی متن داخل جعبهٔ محدوده را مشخص می‌کند. اگر مشخص نشود، چرخش شکل پیوست استفاده می‌شود. اگر مشخص شود، این چرخش به‌طور مستقل از شکل اعمال می‌شود؛ به این معنی که شکل می‌تواند چرخش داشته باشد در حالی که متن خود دارای چرخش جداگانه‌ای باشد. مقدار نهایی چرخش دیداری متن که از این ویژگی و نوع عمودی پیش‌فرض در ویژگی TextVerticalType ترکیب می‌شود. برای جزئیات **float** را بخوانید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | سبک متن را برمی‌گرداند. فقط-خواندنی [ITextStyle](../itextstyle/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | جهت متن را تعیین می‌کند. مقدار نهایی چرخش دیداری متن که از این ویژگی و زاویهٔ سفارشی در ویژگی RotationAngle ترکیب می‌شود. برای جزئیات [Slides::TextVerticalType](../textverticaltype/) را بخوانید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | شیء [ThreeDFormat](../threedformat/) را که خصوصیات اثر ۳بعدی برای متن را نشان می‌دهد، برمی‌گرداند. فقط-خواندنی [IThreeDFormat](../ithreedformat/). |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | شکل بسته‌شدن متن را دریافت می‌کند. برای جزئیات [TextShapeType](../textshapetype/) را بخوانید. |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | **True** اگر متن در حاشیه‌های [TextFrame](../textframe/) بسته شود. برای جزئیات [NullableBool](../nullablebool/) را بخوانید. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | داده‌های قالب‌بندی مؤثر فریم متن را با اعمال ارث‌بری دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء مراقبت [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کپی‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند؛ فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند؛ فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء ارزش‌گونه را با nullptr به‌عنوان مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع‌های مشترک را با مقدار مشخص کاهش می‌دهد. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | متن لنگر عمودی را در یک [TextFrame](../textframe/) تنظیم می‌کند. برای نوشتن [TextAnchorType](../textanchortype/) را ببینید. |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | حالت خودتنظیم متن را تنظیم می‌کند. برای نوشتن [TextAutofitType](../textautofittype/) را ببینید. |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | اگر [NullableBool::True](../nullablebool/) باشد، متن باید افقی در جعبه مرکزچین شود. برای نوشتن [NullableBool](../nullablebool/) را ببینید. |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | تعداد ستون‌های ناحیه متن را تنظیم می‌کند. این مقدار باید عددی مثبت باشد؛ در غیر این صورت به صفر تنظیم می‌شود. مقدار ۰ به معنای مقدار تعریف‌نشده است. برای نوشتن **int32_t** را استفاده کنید. |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | فاصله بین ستون‌های متن در ناحیهٔ متن (به نقطه) را تنظیم می‌کند. این فقط زمانی اعمال می‌شود که بیش از یک ستون وجود داشته باشد. این مقدار باید عددی مثبت باشد؛ در غیر این صورت به صفر تنظیم می‌شود. برای نوشتن **double** را استفاده کنید. |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | متن را به‌طور کامل از صحنهٔ 3-بعدی نگه می‌دارد یا تنظیم می‌کند. برای نوشتن **bool** را استفاده کنید. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | حاشیهٔ پایین (به نقطه) را در یک [TextFrame](../textframe/) تنظیم می‌کند. برای نوشتن **double** را استفاده کنید. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | حاشیهٔ چپ (به نقطه) را در یک [TextFrame](../textframe/) تنظیم می‌کند. برای نوشتن **double** را استفاده کنید. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | حاشیهٔ راست (به نقطه) را در یک [TextFrame](../textframe/) تنظیم می‌کند. برای نوشتن **double** را استفاده کنید. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | حاشیهٔ بالا (به نقطه) را در یک [TextFrame](../textframe/) تنظیم می‌کند. برای نوشتن **double** را استفاده کنید. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | چرخش سفارشی متن داخل جعبهٔ محدوده را مشخص می‌کند. اگر مشخص نشود، چرخش شکل پیوست استفاده می‌شود. اگر مشخص شود، این چرخش به‌طور مستقل از شکل اعمال می‌شود؛ به این معنی که شکل می‌تواند چرخش داشته باشد در حالی که متن خود دارای چرخش جداگانه‌ای باشد. مقدار نهایی چرخش دیداری متن که از این ویژگی و نوع عمودی پیش‌فرض در ویژگی TextVerticalType ترکیب می‌شود. برای نوشتن **float** را استفاده کنید. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | جهت متن را تعیین می‌کند. برای نوشتن [Slides::TextVerticalType](../textverticaltype/) را ببینید. |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | شکل بسته‌شدن متن را تنظیم می‌کند. برای نوشتن [TextShapeType](../textshapetype/) را ببینید. |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | **True** اگر متن در حاشیه‌های [TextFrame](../textframe/) بسته شود. برای نوشتن [NullableBool](../nullablebool/) را ببینید. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگوی قالب را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داخلی را آزاد می‌سازد. |

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)