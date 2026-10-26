---
title: AddChart()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ مخططًا جديدًا، يهيئه ببيانات السلاسل النموذجية والإعدادات، ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 66
url: /ar/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) method

ينشئ مخططًا جديدًا، يهيئه ببيانات السلاسل النموذجية والإعدادات، ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | نوع المخطط المراد إضافته. |
| x | **float** | الإحداثي السيني للمخطط الجديد، بالنقاط. |
| y | **float** | الإحداثي الصادي للمخطط الجديد، بالنقاط. |
| width | **float** | عرض المخطط، بالنقاط. |
| height | **float** | ارتفاع المخطط، بالنقاط. |

### قيمة الإرجاع

[Charts::IChart](../../../aspose.slides.charts/ichart/) الذي تم إنشاؤه حديثًا.

## ملاحظات

المثال التالي يوضح كيفية إنشاء مخطط في PowerPoint [Presentation](../../presentation/).
```cpp
// يقوم بإنشاء كائن من الفئة Presentation التي تمثل ملف PPTX
auto pres = System::MakeObject<Presentation>();
// الوصول إلى الشريحة الأولى
auto slide = pres->get_Slides()->idx_get(0);
// يضيف مخططًا ببياناته الافتراضية
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// يضبط عنوان المخطط
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// يضبط السلسلة الأولى لإظهار القيم
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// يضبط الفهرس لورقة بيانات المخطط
int32_t defaultWorksheetIndex = 0;
// يحصل على ورقة عمل بيانات المخطط
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// يحذف السلاسل والفئات المولدة افتراضيًا
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// يضيف سلاسل جديدة
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// يضيف فئات جديدة
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// يأخذ السلسلة الأولى للمخطط
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// يملأ بيانات السلسلة
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// يضبط لون التعبئة للسلسلة
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// يأخذ السلسلة الثانية للمخطط
series = chart->get_ChartData()->get_Series()->idx_get(1);
// يملأ بيانات السلسلة
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// يضبط لون التعبئة للسلسلة
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// يضبط التسمية الأولى لإظهار اسم الفئة
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// يضبط السلسلة لإظهار القيمة للتسمية الثالثة
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// يحفظ ملف PPTX إلى القرص
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) method

ينشئ مخططًا جديدًا، يهيئه ببيانات السلاسل النموذجية والإعدادات، ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | نوع المخطط المراد إضافته. |
| x | **float** | الإحداثي السيني للمخطط الجديد، بالنقاط. |
| y | **float** | الإحداثي الصادي للمخطط الجديد، بالنقاط. |
| width | **float** | عرض المخطط، بالنقاط. |
| height | **float** | ارتفاع المخطط، بالنقاط. |
| initWithSample | **bool** | True لتهيئة المخطط الجديد ببيانات السلاسل النموذجية والإعدادات؛ false لإنشاء المخطط بدون سلاسل ومع إعدادات دنيا فقط، مما يجعل الإنشاء أسرع. |

### قيمة الإرجاع

[Charts::IChart](../../../aspose.slides.charts/ichart/) الذي تم إنشاؤه حديثًا.

## انظر أيضًا

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)