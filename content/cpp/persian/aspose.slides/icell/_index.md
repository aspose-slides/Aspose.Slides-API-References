---
title: ICell
second_title: مرجع API Aspose.Slides برای C++
description: یک سلول در جدول را نشان می‌دهد.
type: docs
weight: 1639
url: /fa/aspose.slides/icell/
---
## ICell کلاس

Represents a cell in a table.

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیا را با معانی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیا با نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیا با نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | تعیین می‌کند که آیا جعبه متن در داخل سلول مرکز شده است یا نه. خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | شی [CellFormat](../cellformat/) را که شامل ویژگی‌های قالب‌بندی این سلول است برمی‌گرداند. فقط-خواندنی [ICellFormat](../icellformat/). |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | تعداد ستون‌های شبکه در جدول والد که باید توسط سلول جاری پوشانده شوند را برمی‌گرداند. این ویژگی به سلول‌ها اجازه می‌دهد ظاهر ادغام داشته باشند، زیرا مرزهای عمودی سلول‌های دیگر در جدول را پشت سر می‌گذارند. فقط-خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | دریافت اولین ستون سلول. فقط-خواندنی [IColumn](../icolumn/). |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | نمایه اولین ستونی که توسط سلول پوشیده می‌شود را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | دریافت اولین سطر سلول. فقط-خواندنی [IRow](../irow/). |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | نمایه اولین سطری که توسط سلول پوشیده می‌شود را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| virtual **double** [get_Height](./get_height/)() | ارتفاع سلول را برمی‌گرداند. فقط-خواندنی **double**. |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | اگر سلول با هر سلول تنظیم‌شده‌ای ادغام شده باشد true و در غیر این صورت false برمی‌گرداند. فقط-خواندنی **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | حاشیه پایین را در یک [TextFrame](../textframe/) برمی‌گرداند. خواندنی **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | حاشیه چپ را در یک [TextFrame](../textframe/) برمی‌گرداند. خواندنی **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | حاشیه راست را در یک [TextFrame](../textframe/) برمی‌گرداند. خواندنی **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | حاشیه بالا را در یک [TextFrame](../textframe/) برمی‌گرداند. خواندنی **double**. |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | حداقل ارتفاع یک سلول را برمی‌گرداند. این مجموع ارتفاع‌های حداقل تمام ردیف‌های پوشش‌داده شده توسط سلول است. فقط-خواندنی **double**. |
| virtual **double** [get_OffsetX](./get_offsetx/)() | فاصله از سمت چپ جدول تا سمت چپ سلول را برمی‌گرداند. فقط-خواندنی **double**. |
| virtual **double** [get_OffsetY](./get_offsety/)() | فاصله از بالای جدول تا بالای سلول را برمی‌گرداند. فقط-خواندنی **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | ارائه را برمی‌گرداند. فقط-خواندنی [IPresentation](../ipresentation/). |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | تعداد ردیف‌هایی که یک سلول ادغام‌شده پوشش می‌دهد را برمی‌گرداند. این به همراه ویژگی vMerge در سلول‌های دیگر برای تعیین سلول شروع ادغام افقی استفاده می‌شود. فقط-خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | اسلاید پایه را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | شی [Table](../table/) والد برای یک سلول را برمی‌گرداند. فقط-خواندنی [ITable](../itable/). |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | نوع لنگر متن را برمی‌گرداند. خواندنی [Slides::TextAnchorType](../textanchortype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | قاب متن سلول را برمی‌گرداند. فقط-خواندنی [ITextFrame](../itextframe/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | نوع متن عمودی را برمی‌گرداند. خواندنی [Slides::TextVerticalType](../textverticaltype/). |
| virtual **double** [get_Width](./get_width/)() | عرض سلول را برمی‌گرداند. فقط-خواندنی **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را می‌گیرد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). هش‌سازی اشیای سفارشی را فعال می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را می‌گیرد. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت زیرکلاس‌ها به‌صورت کپی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت زیرکلاس‌ها به‌صورت کپی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیا را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیا را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقابلهٔ مرجع یک شیء نوع مقدار با nullptr را انجام می‌دهد. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | تعیین می‌کند که آیا جعبه متن در داخل سلول مرکز شده است یا نه. نوشتنی **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | حاشیه پایین را در یک [TextFrame](../textframe/) تنظیم می‌کند. نوشتنی **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | حاشیه چپ را در یک [TextFrame](../textframe/) تنظیم می‌کند. نوشتنی **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | حاشیه راست را در یک [TextFrame](../textframe/) تنظیم می‌کند. نوشتنی **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | حاشیه بالا را در یک [TextFrame](../textframe/) تنظیم می‌کند. نوشتنی **double**. |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | نوع لنگر متن را تنظیم می‌کند. نوشتنی [Slides::TextAnchorType](../textanchortype/). |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | نوع متن عمودی را تنظیم می‌کند. نوشتنی [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را می‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | سلول را با استفاده از ایندکس ستون به دو سلول تقسیم می‌کند. |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | سلول را بر پایه ارتفاع تقسیم می‌کند. |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | سلول را با استفاده از ایندکس سطر به دو سلول تقسیم می‌کند. |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | سلول را بر پایه عرض تقسیم می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیای سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازقفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## مراجع

* کلاس [ISlideComponent](../islidecomponent/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)