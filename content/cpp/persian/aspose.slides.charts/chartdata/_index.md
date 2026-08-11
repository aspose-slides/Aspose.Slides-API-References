---
title: ChartData
second_title: مرجع API Aspose.Slides برای C++
description: داده‌هایی را که برای رسم نمودار استفاده می‌شود، نمایندگی می‌کند.
type: docs
weight: 118
url: /fa/aspose.slides.charts/chartdata/
---
## ChartData کلاس

داده‌هایی را که برای رسم نمودار استفاده می‌شود، نمایندگی می‌کند.

```cpp
class ChartData : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                  public Aspose::Slides::Charts::IChartData
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقدار، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقدار، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() override | دسته‌بندی‌های اصلی را دریافت می‌کند (یا هر دو دسته‌بندی اصلی و ثانویه اگر [ChartData::set_UseSecondaryCategories](./set_usesecondarycategories/) روی false تنظیم شده باشد). فقط-خواندنی [IChartCategoryCollection](../ichartcategorycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) override | دسته‌بندی اصلی را در ایندکس مشخص شده برمی‌گرداند. اگر [get_UseSecondaryCategories](./get_usesecondarycategories/) روی false باشد، در میان همه دسته‌بندی‌ها دریافت می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() override | فاکتور سلول‌ها را برای ایجاد سلول‌های مورد استفاده در سری‌های نمودار یا دسته‌بندی‌ها دریافت می‌کند. فقط-خواندنی [IChartDataWorkbook](../ichartdataworkbook/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | سری موجود در ایندکس مشخص شده را برمی‌گرداند. |
| [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() override | مسیر کتاب‌کار خارجی را اگر منبع داده خارجی باشد، در غیر این صورت null نشان می‌دهد |
| [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() override | نوع کتاب‌کار توکار را دریافت می‌کند. اگر [ChartData::get_DataSourceType](./get_datasourcetype/) برابر [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/) باشد، [WorkbookType::NotDefined](../workbooktype/) را برمی‌گرداند. فقط-خواندنی [WorkbookType](../workbooktype/). |
| [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() override | منبع داده نمودار را نشان می‌دهد |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() override | دسته‌بندی‌های ثانویه را اگر [ChartData::get_UseSecondaryCategories](./get_usesecondarycategories/) true باشد دریافت می‌کند. فقط-خواندنی [IChartCategoryCollection](../ichartcategorycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) override | دسته‌بندی ثانویه را در ایندکس مشخص شده برمی‌گرداند. اگر [get_UseSecondaryCategories](./get_usesecondarycategories/) false باشد، [ChartData::get_SecondaryCategories](./get_secondarycategories/) null خواهد بود. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() override | سری‌ها را دریافت می‌کند. فقط-خواندنی [IChartSeriesCollection](../ichartseriescollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) override | گروه سری‌ها را در ایندکس مشخص شده برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() override | گروه‌های سری‌ها را دریافت می‌کند. فقط-خواندنی [IChartSeriesGroupCollection](../ichartseriesgroupcollection/). |
| **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() override | اگر روی false تنظیم شود، [ChartData::get_SecondaryCategories](./get_secondarycategories/) null برمی‌گرداند و داده در [ChartData::get_Categories](./get_categories/) برای هر دو سری اصلی و ثانویه استفاده می‌شود. اگر روی true تنظیم شود، داده در [ChartData::get_SecondaryCategories](./get_secondarycategories/) برای سری‌های ثانویه و داده در [ChartData::get_Categories](./get_categories/) برای سری‌های اصلی استفاده می‌شود. خواند **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظیر روش [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| [System::String](../../system/string/) [GetRange](./getrange/)() override | محدوده داده‌های نمودار را دریافت می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است یا نه. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با دستور lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظیر روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت زیرکلاس‌های کپی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت زیرکلاس‌های کپی را فراهم می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() override | کتاب‌کار [Excel](../../aspose.slides.excel/) داخلی را در یک جریان در-حافظه می‌نویسد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به میزان مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) override | اگر روی false تنظیم شود، [ChartData::get_SecondaryCategories](./get_secondarycategories/) null برمی‌گرداند و داده در [ChartData::get_Categories](./get_categories/) برای هر دو سری اصلی و ثانویه استفاده می‌شود. اگر روی true تنظیم شود، داده در [ChartData::get_SecondaryCategories](./get_secondarycategories/) برای سری‌های ثانویه و داده در [ChartData::get_Categories](./get_categories/) برای سری‌های اصلی استفاده می‌شود. نوشت **bool**. |
| void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) override | کتاب‌کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. داده‌های [Chart](../chart/) از کتاب‌کار هدف به‌روزرسانی خواهد شد. |
| void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) override | کتاب‌کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. |
| void [SetRange](./setrange/)([System::String](../../system/string/)) override | محدوده داده‌های نمودار را تنظیم می‌کند. سری‌ها و دسته‌بندی‌ها بر اساس محدوده داده جدید به‌روز می‌شوند. اگر تعداد سری‌ها در محدوده داده بیشتر از تعداد سری‌ها در داده‌های نمودار باشد، سری‌های اضافی با همان نوع سری آخر در مجموعه جاری به انتهای مجموعه اضافه می‌شوند. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. اجازه می‌دهد تا اشاره‌گرها در کانتینرها به حالت ضعیف تغییر کنند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [SwitchRowColumn](./switchrowcolumn/)() override | داده‌ها را در طول محور جابجا می‌کند. داده‌هایی که بر محور X نمودار کشیده می‌شوند به محور Y منتقل می‌شوند و بالعکس. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظیر روش [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری با دستور lock() در C# را آزاد می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) override | کتاب‌کار [Excel](../../aspose.slides.excel/) داخلی را با مقدار مشخص‌شده توسط کاربر مقداردهی اولیه می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## موارد مرتبط

* کلاس [DomObject](../../aspose.slides/domobject/)
* کلاس [IChartData](../ichartdata/)
* فضای نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)