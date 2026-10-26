---
title: IChartData
second_title: Aspose.Slides برای مرجع API C++
description: داده‌های مورد استفاده برای رسم نمودار را نمایندگی می‌کند.
type: docs
weight: 651
url: /fa/aspose.slides.charts/ichartdata/
---
## IChartData کلاس

داده‌هایی را که برای رسم نمودار استفاده می‌شود، نمایندگی می‌کند.

```cpp
class IChartData : public virtual System::Object
```

## متدها

| متد | شرح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معانی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() | دسته‌های اصلی را دریافت می‌کند (یا هم دسته‌های اصلی و هم دسته‌های ثانویه را اگر [IChartData::set_UseSecondaryCategories](./set_usesecondarycategories/) برابر false باشد). فقط‌خواندنی [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) | دستهٔ اصلی را در اندیس مشخص شده برمی‌گرداند. اگر [get_UseSecondaryCategories](./get_usesecondarycategories/) برابر false باشد، از میان تمام دسته‌ها دریافت می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() | کارخانهٔ سلول‌ها را برای ایجاد سلول‌های استفاده‌شده در سری‌ها یا دسته‌های نمودار دریافت می‌کند. فقط‌خواندنی [IChartDataWorkbook](../ichartdataworkbook/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | سری را در اندیس مشخص شده برمی‌گرداند. |
| virtual [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() | منبع داده‌ای نمودار را نمایندگی می‌کند |
| virtual [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() | نوع دفتر کار جاسازی‌شده را دریافت می‌کند. اگر [IChartData::get_DataSourceType](./get_datasourcetype/) برابر [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/) باشد، [WorkbookType::NotDefined](../workbooktype/) برمی‌گرداند. فقط‌خواندنی [WorkbookType](../workbooktype/). |
| virtual [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() | مسیر دفتر کار خارجی را نمایندگی می‌کند اگر منبع داده خارجی باشد، در غیر این صورت null |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() | دسته‌های ثانویه را دریافت می‌کند اگر [IChartData::get_UseSecondaryCategories](./get_usesecondarycategories/) برابر true باشد. فقط‌خواندنی [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) | دستهٔ ثانویه را در اندیس مشخص شده برمی‌گرداند. اگر [get_UseSecondaryCategories](./get_usesecondarycategories/) برابر false باشد، [IChartData::get_SecondaryCategories](./get_secondarycategories/) برابر null است. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() | سری‌ها را دریافت می‌کند. فقط‌خواندنی [IChartSeriesCollection](../ichartseriescollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) | گروه سری‌ها را در اندیس مشخص شده برمی‌گرداند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() | گروه‌های سری‌ها را دریافت می‌کند. فقط‌خواندنی [IChartSeriesGroupCollection](../ichartseriesgroupcollection/). |
| virtual **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() | اگر برابر false باشد، [IChartData::get_SecondaryCategories](./get_secondarycategories/) null برمی‌گرداند و داده‌های موجود در [IChartData::get_Categories](./get_categories/) برای هر دو سری اصلی و ثانویه استفاده می‌شود. اگر برابر true باشد، داده‌های موجود در [IChartData::get_SecondaryCategories](./get_secondarycategories/) برای سری‌های ثانویه و داده‌های موجود در [IChartData::get_Categories](./get_categories/) برای سری‌های اصلی استفاده می‌شود. خواندن **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده‌ی شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). هش‌سازی اشیاء سفارشی را فعال می‌کند. |
| virtual [System::String](../../system/string/) [GetRange](./getrange/)() | محدوده دادهٔ نمودار را دریافت می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایان‌گر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری توسط دستور C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، تنها شیء جدیدی را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر تخصیص. در واقع هیچ‌چیزی را کپی نمی‌کند، تنها شیء جدیدی را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() | دفتر کار [Excel](../../aspose.slides.excel/) داخلی را به یک جریان در-حافظه می‌نویسد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه ارجاعی شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص شده کاهش می‌دهد. |
| virtual void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) | اگر برابر false باشد، [IChartData::get_SecondaryCategories](./get_secondarycategories/) null برمی‌گرداند و داده‌های موجود در [IChartData::get_Categories](./get_categories/) برای هر دو سری اصلی و ثانویه استفاده می‌شود. اگر برابر true باشد، داده‌های موجود در [IChartData::get_SecondaryCategories](./get_secondarycategories/) برای سری‌های ثانویه و داده‌های موجود در [IChartData::get_Categories](./get_categories/) برای سری‌های اصلی استفاده می‌شود. نوشتن **bool**. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) | دفتر کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. داده‌های [Chart](../chart/) از دفتر کار هدف به‌روز خواهند شد. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) | دفتر کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. |
| virtual void [SetRange](./setrange/)([System::String](../../system/string/)) | محدودهٔ دادهٔ نمودار را تنظیم می‌کند. سری‌ها و دسته‌ها بر اساس محدودهٔ دادهٔ جدید به‌روز خواهند شد. اگر تعداد سری‌ها در محدودهٔ داده بیشتر از تعداد سری‌ها در دادهٔ نمودار باشد، سری‌های اضافی با همان نوع سری آخر موجود در مجموعه فعلی به انتهای مجموعه افزوده می‌شوند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تعویض اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| virtual void [SwitchRowColumn](./switchrowcolumn/)() | داده‌ها را بر روی محور جابجا می‌کند. داده‌های ترسیم‌شده روی محور X به محور Y منتقل می‌شوند و برعکس. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). تبدیل اشیاء سفارشی به رشته را امکان‌پذیر می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازقفل‌گذاری توسط دستور C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| virtual void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) | دفتر کار [Excel](../../aspose.slides.excel/) داخلی را با مقدار مشخص شده توسط کاربر مقداردهی اولیه می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## مطالب مرتبط

* کلاس [Object](../../system/object/)
* فضای‌نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)