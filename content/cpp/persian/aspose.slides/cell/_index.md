---
title: Cell
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر یک سلول از جدول.
type: docs
weight: 300
url: /fa/aspose.slides/cell/
---
## کلاس Cell

نمایانگر یک سلول از جدول.

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | تعیین می‌کند که جعبه متن داخل سلول مرکز شده است یا نه. خواند **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | شیء [CellFormat](../cellformat/) را که شامل ویژگی‌های قالب‌بندی برای این سلول است برمی‌گرداند. فقط‌خواندنی [ICellFormat](../icellformat/). |
| **int32_t** [get_ColSpan](./get_colspan/)() override | تعداد ستون‌های شبکه جدول والد را که توسط سلول فعلی پوشش داده می‌شود برمی‌گرداند. این ویژگی به سلول‌ها اجازه می‌دهد ظاهری مشابه ادغام داشته باشند، زیرا مرزهای عمودی سلول‌های دیگر جدول را می‌پوشانند. فقط‌خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | ستون اول سلول را دریافت می‌کند. فقط‌خواندنی [IColumn](../icolumn/). |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | شاخص اولین ستونی که توسط سلول پوشش داده می‌شود را برمی‌گرداند. فقط‌خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | سطر اول سلول را دریافت می‌کند. فقط‌خواندنی [IRow](../irow/). |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | شاخص اولین سطری که توسط سلول پوشش داده می‌شود را برمی‌گرداند. فقط‌خواندنی **int32_t**. |
| **double** [get_Height](./get_height/)() override | ارتفاع سلول را برمی‌گرداند. فقط‌خواندنی **double**. |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | در صورت ادغام سلول با هر سلول تنظیم‌شده true و در غیر این صورت false برمی‌گرداند. فقط‌خواندنی **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | حد زیرین در یک [TextFrame](../textframe/) را برمی‌گرداند. خواند **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | حد چپ در یک [TextFrame](../textframe/) را برمی‌گرداند. خواند **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | حد راست در یک [TextFrame](../textframe/) را برمی‌گرداند. خواند **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | حد بالا در یک [TextFrame](../textframe/) را برمی‌گرداند. خواند **double**. |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | حداقل ارتفاع یک سلول را برمی‌گرداند. این مجموع ارتفاع‌های حداقل تمام سطرهای تحت پوشش سلول است. فقط‌خواندنی **double**. |
| **double** [get_OffsetX](./get_offsetx/)() override | فاصله از سمت چپ جدول تا سمت چپ سلول را برمی‌گرداند. فقط‌خواندنی **double**. |
| **double** [get_OffsetY](./get_offsety/)() override | فاصله از سمت بالای جدول تا سمت بالای سلول را برمی‌گرداند. فقط‌خواندنی **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | ارائه والد سلول را برمی‌گرداند. فقط‌خواندنی [IPresentation](../ipresentation/). |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | تعداد سطرهایی که یک سلول ادغام‌شده پوشش می‌دهد را برمی‌گرداند. این برای ترکیب با ویژگی vMerge در سایر سلول‌ها به منظور مشخص کردن سلول آغازین ادغام افقی استفاده می‌شود. فقط‌خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | اسلاید والد سلول را برمی‌گرداند. فقط‌خواندنی [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | شیء والد [Table](../table/) برای یک سلول را برمی‌گرداند. فقط‌خواندنی [ITable](../itable/). |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | نوع لنگر متن را برمی‌گرداند. خواند [Slides::TextAnchorType](../textanchortype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | قاب متن یک سلول را برمی‌گرداند. فقط‌خواندنی [ITextFrame](../itextframe/). |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | نوع متن عمودی را برمی‌گرداند. خواند [Slides::TextVerticalType](../textverticaltype/). |
| **double** [get_Width](./get_width/)() override | عرض سلول را برمی‌گرداند. فقط‌خواندنی **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). هش کردن اشیاء سفارشی را فعال می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیانیه C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان شبیه‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی در زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی در زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به صورت مرجعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع اشتراکی را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | تعیین می‌کند که جعبه متن داخل سلول مرکز شده است یا نه. بنویس **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | حد زیرین در یک [TextFrame](../textframe/) را تنظیم می‌کند. بنویس **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | حد چپ در یک [TextFrame](../textframe/) را تنظیم می‌کند. بنویس **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | حد راست در یک [TextFrame](../textframe/) را تنظیم می‌کند. بنویس **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | حد بالا در یک [TextFrame](../textframe/) را تنظیم می‌کند. بنویس **double**. |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | نوع لنگر متن را تنظیم می‌کند. بنویس [Slides::TextAnchorType](../textanchortype/). |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | نوع متن عمودی را تنظیم می‌کند. بنویس [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع اشتراکی را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع اشتراکی را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | سلول را به دو سلول بر اساس شاخص ستون تقسیم می‌کند. |
| void [SplitByHeight](./splitbyheight/)(**double**) override | سلول را بر اساس ارتفاع تقسیم می‌کند. |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | سلول را به دو سلول بر اساس شاخص سطر تقسیم می‌کند. |
| void [SplitByWidth](./splitbywidth/)(**double**) override | سلول را بر اساس عرض تقسیم می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری بیانیه C# lock() را آزاد می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## موارد مرتبط

* کلاس [IDOMObject](../idomobject/)
* کلاس [ICell](../icell/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)