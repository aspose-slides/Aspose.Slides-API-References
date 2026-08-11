---
title: TextFrameFormat
second_title: مرجع API Aspose.Slides برای C++
description: ویژگی‌های formatTextFrameFormatting مربوط به TextFrame را دربر می‌گیرد.
type: docs
weight: 5461
url: /fa/aspose.slides/textframeformat/
---
## TextFrameFormat کلاس

حاوی ویژگی‌های formatTextFrameFormatting [TextFrame](../textframe/) است.

```cpp
class TextFrameFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::ITextFrameFormat,
                        public Aspose::Slides::Charts::IChartTextBlockFormat
```

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | مقایسه با شیء مشخص شده. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقاط شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقاط شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() override | متن عمودی anchor را در یک [TextFrame](../textframe/) باز می‌گرداند. خواندن [TextAnchorType](../textanchortype/). |
| [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() override | حالت خودکار تنظیم متن را باز می‌گرداند. خواندن [TextAutofitType](../textautofittype/). |
| [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() override | اگر [NullableBool::True](../nullablebool/) باشد، متن باید به صورت افقی در جعبه مرکز شود. خواندن [NullableBool](../nullablebool/). |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | تعداد ستون‌ها در ناحیه متن را باز می‌گرداند. این مقدار باید عددی مثبت باشد. در غیر این صورت، مقدار به صفر تنظیم می‌شود. مقدار 0 به معنای مقدار نامشخص است. خواندن **int32_t**. |
| **double** [get_ColumnSpacing](./get_columnspacing/)() override | فاصله بین ستون‌های متن در ناحیه متن (به نقطه) را باز می‌گرداند. این فقط زمانی اعمال می‌شود که بیش از یک ستون وجود داشته باشد. این مقدار باید عددی مثبت باشد. در غیر این صورت، مقدار به صفر تنظیم می‌شود. خواندن **double**. |
| **bool** [get_KeepTextFlat](./get_keeptextflat/)() override | حالت حفظ متن صاف را حتی اگر اثر چرخش ۳-بعدی اعمال شده باشد، دریافت می‌کند. خواندن **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | حاشیه پایین (نقطه) در یک [TextFrame](../textframe/) را باز می‌گرداند. خواندن **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | حاشیه چپ (نقطه) در یک [TextFrame](../textframe/) را باز می‌گرداند. خواندن **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | حاشیه راست (نقطه) در یک [TextFrame](../textframe/) را باز می‌گرداند. خواندن **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | حاشیه بالا (نقطه) در یک [TextFrame](../textframe/) را باز می‌گرداند. خواندن **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate شیء را باز می‌گرداند. فقط خواندنی [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | والد [IPresentationComponent](../ipresentationcomponent/) را باز می‌گرداند. فقط خواندنی [IPresentationComponent](../ipresentationcomponent/). |
| **float** [get_RotationAngle](./get_rotationangle/)() override | چرخش سفارشی که بر روی متن داخل جعبه محدودیت اعمال می‌شود را مشخص می‌کند. اگر مشخص نشود، چرخش شکل همراه استفاده می‌شود. اگر مشخص شود، به‌صورت مستقل از شکل اعمال می‌شود. یعنی شکل می‌تواند چرخشی داشته باشد به علاوهٔ چرخش متن خود. مقدار نهایی چرخش بصری متن که از این ویژگی و نوع عمودی از پیش تعریف‌شده در ویژگی TextVerticalType جمع‌بندی می‌شود. خواندن **float**. |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | جهت متن را تعیین می‌کند. مقدار نهایی چرخش بصری متن که از این ویژگی و زاویه سفارشی در ویژگی RotationAngle جمع‌بندی می‌شود. خواندن [Slides::TextVerticalType](../textverticaltype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | شیء [ThreeDFormat](../threedformat/) را که خواص اثر ۳-بعدی برای متن را نشان می‌دهد، باز می‌گرداند. فقط خواندنی [IThreeDFormat](../ithreedformat/). |
| [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() override | شکل پیچش متن را دریافت می‌کند. خواندن [TextShapeType](../textshapetype/). |
| [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() override | **True** اگر متن در حاشیه‌های [TextFrame](../textframe/) پیچیده شود. خواندن [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() override | داده‌های فرمت‌بندی فریم متن مؤثر را که وراثت بر آن اعمال شده است، دریافت می‌کند. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | کد هش را باز می‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء نگهدارنده [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | متد مشابه C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیز را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ چیز را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) override | متن عمودی anchor را در یک [TextFrame](../textframe/) تنظیم می‌کند. نوشتن [TextAnchorType](../textanchortype/). |
| void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) override | حالت خودکار تنظیم متن را تنظیم می‌کند. نوشتن [TextAutofitType](../textautofittype/). |
| void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) override | اگر [NullableBool::True](../nullablebool/) باشد، متن باید به صورت افقی در جعبه مرکز شود. نوشتن [NullableBool](../nullablebool/). |
| void [set_ColumnCount](./set_columncount/)(**int32_t**) override | تعداد ستون‌ها در ناحیه متن را تنظیم می‌کند. این مقدار باید عددی مثبت باشد. در غیر این صورت، مقدار به صفر تنظیم می‌شود. مقدار 0 به معنای مقدار نامشخص است. نوشتن **int32_t**. |
| void [set_ColumnSpacing](./set_columnspacing/)(**double**) override | فاصله بین ستون‌های متن در ناحیه متن (به نقطه) را تنظیم می‌کند. این فقط زمانی اعمال می‌شود که بیش از یک ستون وجود داشته باشد. این مقدار باید عددی مثبت باشد. در غیر این صورت، مقدار به صفر تنظیم می‌شود. نوشتن **double**. |
| void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) override | حفظ متن صاف را حتی اگر اثر چرخش ۳-بعدی اعمال شده باشد، تنظیم می‌کند. نوشتن **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | حاشیه پایین (نقطه) را در یک [TextFrame](../textframe/) تنظیم می‌کند. نوشتن **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | حاشیه چپ (نقطه) را در یک [TextFrame](../textframe/) تنظیم می‌کند. نوشتن **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | حاشیه راست (نقطه) را در یک [TextFrame](../textframe/) تنظیم می‌کند. نوشتن **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | حاشیه بالا (نقطه) را در یک [TextFrame](../textframe/) تنظیم می‌کند. نوشتن **double**. |
| void [set_RotationAngle](./set_rotationangle/)(**float**) override | چرخش سفارشی که بر روی متن داخل جعبه محدودیت اعمال می‌شود را مشخص می‌کند. اگر مشخص نشود، چرخش شکل همراه استفاده می‌شود. اگر مشخص شود، به‌صورت مستقل از شکل اعمال می‌شود. یعنی شکل می‌تواند چرخشی داشته باشد به علاوهٔ چرخش متن خود. مقدار نهایی چرخش بصری متن که از این ویژگی و نوع عمودی از پیش تعریف‌شده در ویژگی TextVerticalType جمع‌بندی می‌شود. نوشتن **float**. |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | جهت متن را تعیین می‌کند. مقدار نهایی چرخش بصری متن که از این ویژگی و زاویه سفارشی در ویژگی RotationAngle جمع‌بندی می‌شود. نوشتن [Slides::TextVerticalType](../textverticaltype/). |
| void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) override | شکل پیچش متن را تنظیم می‌کند. نوشتن [TextShapeType](../textshapetype/). |
| void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) override | **True** اگر متن در حاشیه‌های [TextFrame](../textframe/) پیچیده شود. نوشتن [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تعویض اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و باز می‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [TextFrameFormat](./textframeformat/)() | نمونه جدیدی از کلاس [TextFrameFormat](./) را مقداردهی اولیه می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | متد مشابه C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساخت typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری بیان lock() در C# را باز می‌کند. مستقیماً صدا بزنید یا از شیء نگهدارنده [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## موارد مرتبط

* کلاس [PVIObject](../pviobject/)
* کلاس [ITextFrameFormat](../itextframeformat/)
* کلاس [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)