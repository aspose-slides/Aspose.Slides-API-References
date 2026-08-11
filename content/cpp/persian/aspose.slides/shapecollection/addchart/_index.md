---
title: AddChart()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند و به انتهای مجموعه شکل‌ها اضافه می‌نماید.
type: docs
weight: 66
url: /fa/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) متد

یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند و به انتهای مجموعه شکل‌ها اضافه می‌نماید.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | نوع نمودار برای افزودن. |
| x | **float** | مختصات x نمودار جدید، بر حسب نقطه. |
| y | **float** | مختصات y نمودار جدید، بر حسب نقطه. |
| width | **float** | عرض نمودار، بر حسب نقطه. |
| height | **float** | ارتفاع نمودار، بر حسب نقطه. |

### مقدار بازگشت

[Charts::IChart](../../../aspose.slides.charts/ichart/) تازه ایجاد شده.

## توضیحات

مثال زیر نشان می‌دهد چگونه Chart را در PowerPoint [Presentation](../../presentation/) ایجاد کنید.

```cpp
// یک شی از کلاس Presentation که نمایانگر فایل PPTX است، ایجاد می‌کند
auto pres = System::MakeObject<Presentation>();
// به اسلاید اول دسترسی می‌یابد
auto slide = pres->get_Slides()->idx_get(0);
// نمودار را با داده‌های پیش‌فرض آن اضافه می‌کند
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// عنوان نمودار را تنظیم می‌کند
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// سری اول را برای نمایش مقادیر تنظیم می‌کند
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// شاخص شیت داده‌های نمودار را تنظیم می‌کند
int32_t defaultWorksheetIndex = 0;
// برگه کاری داده‌های نمودار را دریافت می‌کند
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// سری‌ها و دسته‌بندی‌های پیش‌فرض تولید شده را حذف می‌کند
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// سری‌های جدید را اضافه می‌کند
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// دسته‌بندی‌های جدید را اضافه می‌کند
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// سری اول نمودار را می‌گیرد
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// داده‌های سری را پر می‌کند
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// رنگ پرچم (پر) سری را تنظیم می‌کند
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// سری دوم نمودار را می‌گیرد
series = chart->get_ChartData()->get_Series()->idx_get(1);
// داده‌های سری را پر می‌کند
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// رنگ پرچم (پر) سری را تنظیم می‌کند
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// برچسب اول را برای نمایش نام دسته‌بندی تنظیم می‌کند
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// سری را برای نمایش مقدار برچسب سوم تنظیم می‌کند
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// فایل PPTX را روی دیسک ذخیره می‌کند
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) متد

یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند و به انتهای مجموعه شکل‌ها اضافه می‌نماید.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | نوع نمودار برای افزودن. |
| x | **float** | مختصات x نمودار جدید، بر حسب نقطه. |
| y | **float** | مختصات y نمودار جدید، بر حسب نقطه. |
| width | **float** | عرض نمودار، بر حسب نقطه. |
| height | **float** | ارتفاع نمودار، بر حسب نقطه. |
| initWithSample | **bool** | True برای اولیه‌سازی نمودار جدید با داده‌های نمونه سری و تنظیمات؛ false برای ایجاد نمودار بدون سری و فقط با تنظیمات حداقل، که ساختن آن را سریع‌تر می‌کند. |

### مقدار بازگشت

[Charts::IChart](../../../aspose.slides.charts/ichart/) تازه ایجاد شده.

## همچنین ببینید

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)