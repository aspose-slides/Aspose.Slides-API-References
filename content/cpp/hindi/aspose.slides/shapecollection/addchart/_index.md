---
title: AddChart()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स से प्रारंभ करता है, और इसे आकार संग्रह के अंत में जोड़ता है।
type: docs
weight: 66
url: /hi/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) विधि

एक नया चार्ट बनाता है, इसे नमूना सीरीज़ डेटा और सेटिंग्स से प्रारंभ करता है और इसे आकार संग्रह के अंत में जोड़ता है।

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | जोड़ने के लिए चार्ट का प्रकार। |
| x | **float** | नए चार्ट का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए चार्ट का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | चार्ट की चौड़ाई, पॉइंट्स में। |
| height | **float** | चार्ट की ऊँचाई, पॉइंट्स में। |

### रिटर्न वैल्यू

नया बनाया गया [Charts::IChart](../../../aspose.slides.charts/ichart/)।

## टिप्पणियाँ

निम्न उदाहरण दिखाता है कि PowerPoint [Presentation](../../presentation/) में Chart कैसे बनाएं। 
```cpp
// PPTX फ़ाइल का प्रतिनिधित्व करने वाले Presentation क्लास का उदाहरण बनाता है
auto pres = System::MakeObject<Presentation>();
// पहली स्लाइड तक पहुँचता है
auto slide = pres->get_Slides()->idx_get(0);
// डिफ़ॉल्ट डेटा के साथ एक चार्ट जोड़ता है
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// चार्ट शीर्षक सेट करता है
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// पहली श्रृंखला को मान दिखाने के लिए सेट करता है
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// चार्ट डेटा शीट के लिए इंडेक्स सेट करता है
int32_t defaultWorksheetIndex = 0;
// चार्ट डेटा वर्कशीट प्राप्त करता है
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// डिफ़ॉल्ट जेनरेट की गई श्रृंखला और श्रेणियों को हटाता है
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// नई श्रृंखला जोड़ता है
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// नई श्रेणियां जोड़ता है
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// पहली चार्ट श्रृंखला लेता है
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// श्रृंखला डेटा को भरता है
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// श्रृंखला के लिए भराव रंग सेट करता है
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// दूसरी चार्ट श्रृंखला लेता है
series = chart->get_ChartData()->get_Series()->idx_get(1);
// श्रृंखला डेटा को भरता है
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// श्रृंखला के लिए भराव रंग सेट करता है
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// पहले लेबल को श्रेणी नाम दिखाने के लिए सेट करता है
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// तीसरे लेबल के लिए मान दिखाने हेतु श्रृंखला सेट करता है
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// PPTX फ़ाइल को डिस्क पर सहेजता है
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) विधि

एक नया चार्ट बनाता है, इसे नमूना सीरीज़ डेटा और सेटिंग्स से प्रारंभ करता है और इसे आकार संग्रह के अंत में जोड़ता है।

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | जोड़ने के लिए चार्ट का प्रकार। |
| x | **float** | नए चार्ट का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए चार्ट का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | चार्ट की चौड़ाई, पॉइंट्स में। |
| height | **float** | चार्ट की ऊँचाई, पॉइंट्स में। |
| initWithSample | **bool** | true होने पर नया चार्ट नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ किया जाता है; false होने पर चार्ट बिना श्रृंखला के और केवल न्यूनतम सेटिंग्स के साथ बनाया जाता है, जिससे निर्माण तेज़ होता है। |

### रिटर्न वैल्यू

नया बनाया गया [Charts::IChart](../../../aspose.slides.charts/ichart/)।

## देखें

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)