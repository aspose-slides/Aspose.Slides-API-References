---
title: AddChartFromWorkbook()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट Excel वर्कबुक से एक चार्ट प्राप्त करता है और निर्दिष्ट निर्देशांकों पर दिए गए शेप संग्रह के अंत में इसे जोड़ता है।
type: docs
weight: 1
url: /hi/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) मेथड


निर्दिष्ट [Excel](../../../aspose.slides.excel/) वर्कबुक से चार्ट प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप कलेक्शन के अंत में जोड़ता है।

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```


### पैरामीटर

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | वह शेप कलेक्शन जिसमें चार्ट जोड़ा जाएगा। |
| x | **float** | चार्ट की स्थिति के लिए X निर्देशांक। |
| y | **float** | चार्ट की स्थिति के लिए Y निर्देशांक। |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/) वर्कबुक। |
| worksheetName | [System::String](../../../system/string/) | वह वर्कशीट का नाम जिसमें चार्ट है। |
| chartIndex | **int32_t** | चार्ट शेप का शून्य-आधारित इंडेक्स जिसे डालना है। यह इंडेक्स [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../) मेथड का उपयोग करके प्राप्त किया जा सकता है। |
| embedAllWorkbook | **bool** | यदि **true** है, तो संपूर्ण वर्कबुक चार्ट में एम्बेड हो जाएगा; यदि **false** है, तो केवल चार्ट डेटा एम्बेड होगा। |

### वापसी मान

शेप कलेक्शन में जोड़ा गया चार्ट।
## टिप्पणी



उदाहरण: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) मेथड


निर्दिष्ट [Excel](../../../aspose.slides.excel/) वर्कबुक से चार्ट प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप कलेक्शन के अंत में जोड़ता है।

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### पैरामीटर

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | वह शेप कलेक्शन जिसमें चार्ट जोड़ा जाएगा। |
| x | **float** | चार्ट की स्थिति के लिए X निर्देशांक। |
| y | **float** | चार्ट की स्थिति के लिए Y निर्देशांक। |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/) वर्कबुक। |
| worksheetName | [System::String](../../../system/string/) | वह वर्कशीट का नाम जिसमें चार्ट है। |
| chartName | [System::String](../../../system/string/) | जोड़ा जाने वाले चार्ट का नाम। |
| embedAllWorkbook | **bool** | यदि **true** है, तो संपूर्ण वर्कबुक चार्ट में एम्बेड हो जाएगा; यदि **false** है, तो केवल चार्ट डेटा एम्बेड होगा। |

### वापसी मान

शेप कलेक्शन में जोड़ा गया चार्ट।
## टिप्पणी



उदाहरण: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();

System::String worksheetName = u"worksheet name";
auto worksheetCharts = wb->GetChartsFromWorksheet(worksheetName);
for (auto&& chart : worksheetCharts)
{
    System::SharedPtr<ISlide> slide = pres->get_Slides()->AddEmptySlide(pres->get_LayoutSlides()->idx_get(0));
    ExcelWorkbookImporter::AddChartFromWorkbook(slide->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chart.get_Key(), false);
}
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String, bool) मेथड


निर्दिष्ट [Excel](../../../aspose.slides.excel/) वर्कबुक से चार्ट प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप कलेक्शन के अंत में जोड़ता है।

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### पैरामीटर

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | वह शेप कलेक्शन जिसमें चार्ट जोड़ा जाएगा। |
| x | **float** | चार्ट की स्थिति के लिए X निर्देशांक। |
| y | **float** | चार्ट की स्थिति के लिए Y निर्देशांक। |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | वर्कबुक डेटा वाले स्ट्रीम। |
| worksheetName | [System::String](../../../system/string/) | वह वर्कशीट का नाम जिसमें चार्ट है। |
| chartName | [System::String](../../../system/string/) | जोड़ा जाने वाले चार्ट का नाम। |
| embedAllWorkbook | **bool** | यदि **true** है, तो संपूर्ण वर्कबुक चार्ट में एम्बेड हो जाएगा; यदि **false** है, तो केवल चार्ट डेटा एम्बेड होगा। |

### वापसी मान

शेप कलेक्शन में जोड़ा गया चार्ट।
## टिप्पणी



उदाहरण: 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) मेथड


निर्दिष्ट [Excel](../../../aspose.slides.excel/) वर्कबुक से चार्ट प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप कलेक्शन के अंत में जोड़ता है।

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```


### पैरामीटर

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | वह शेप कलेक्शन जिसमें चार्ट जोड़ा जाएगा। |
| x | **float** | चार्ट की स्थिति के लिए X निर्देशांक। |
| y | **float** | चार्ट की स्थिति के लिए Y निर्देशांक। |
| workbookPath | [System::String](../../../system/string/) | चार्ट वाले वर्कबुक का फ़ाइल पथ। |
| worksheetName | [System::String](../../../system/string/) | वह वर्कशीट का नाम जिसमें चार्ट है। |
| chartName | [System::String](../../../system/string/) | जोड़ा जाने वाले चार्ट का नाम। |
| embedWorkbook | **bool** | यदि **true** है, तो वर्कबुक चार्ट में एम्बेड होगा; यदि **false** है, तो चार्ट बाहरी वर्कबुक के साथ लिंक करेगा। |

### वापसी मान

शेप कलेक्शन में जोड़ा गया चार्ट।
## टिप्पणी



उदाहरण: 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Class [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Class [String](../../../system/string/)
* Class [ExcelWorkbookImporter](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)