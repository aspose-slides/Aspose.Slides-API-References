---
title: AddTableFromWorkbook()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट Excel वर्कबुक से एक टेबल प्राप्त करता है और निर्दिष्ट निर्देशांकों पर दिए गए शेप संग्रह के अंत में इसे जोड़ता है।
type: docs
weight: 14
url: /hi/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) विधि


निर्दिष्ट [Excel](../../../aspose.slides.excel/) वर्कबुक से एक टेबल प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप संग्रह के अंत में इसे जोड़ता है।

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | वह शेप संग्रह जिसमें टेबल जोड़ी जाएगी। |
| x | **float** | टेबल को स्थित करने के लिये X निर्देशांक। |
| y | **float** | टेबल को स्थित करने के लिये Y निर्देशांक। |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/) वर्कबुक। |
| worksheetName | [System::String](../../../system/string/) | टेबल शामिल करने वाले वर्कशीट का नाम। |
| cellRange | [System::String](../../../system/string/) | टेबल को परिभाषित करने वाली सेल रेंज (उदाहरण के लिए, "A1:D10")। |

### रिटर्न मान

शेप संग्रह में जोड़ी गई टेबल।

## टिप्पणियां




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) विधि


निर्दिष्ट [Excel](../../../aspose.slides.excel/) वर्कबुक फ़ाइल से एक टेबल प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप संग्रह के अंत में इसे जोड़ता है।

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | वह शेप संग्रह जिसमें टेबल जोड़ी जाएगी। |
| x | **float** | टेबल को स्थित करने के लिये X निर्देशांक। |
| y | **float** | टेबल को स्थित करने के लिये Y निर्देशांक। |
| workbookPath | [System::String](../../../system/string/) | [Excel](../../../aspose.slides.excel/) वर्कबुक फ़ाइल का पथ। |
| worksheetName | [System::String](../../../system/string/) | टेबल शामिल करने वाले वर्कशीट का नाम। |
| cellRange | [System::String](../../../system/string/) | टेबल को परिभाषित करने वाली सेल रेंज (उदाहरण के लिए, "A1:D10")। |

### रिटर्न मान

शेप संग्रह में जोड़ी गई टेबल।

## टिप्पणियां




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) विधि


निर्दिष्ट [Excel](../../../aspose.slides.excel/) वर्कबुक फ़ाइल से एक टेबल प्राप्त करता है और निर्दिष्ट निर्देशांक पर दिए गए शेप संग्रह के अंत में इसे जोड़ता है।

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | वह शेप संग्रह जिसमें टेबल जोड़ी जाएगी। |
| x | **float** | टेबल को स्थित करने के लिये X निर्देशांक। |
| y | **float** | टेबल को स्थित करने के लिये Y निर्देशांक। |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | वर्कबुक डेटा शामिल करने वाला स्ट्रीम। |
| worksheetName | [System::String](../../../system/string/) | टेबल शामिल करने वाले वर्कशीट का नाम। |
| cellRange | [System::String](../../../system/string/) | टेबल को परिभाषित करने वाली सेल रेंज (उदाहरण के लिए, "A1:D10")। |

### रिटर्न मान

शेप संग्रह में जोड़ी गई टेबल।

## टिप्पणियां




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## संबंधित

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [ITable](../../../aspose.slides/itable/)
* क्लास [IShapeCollection](../../../aspose.slides/ishapecollection/)
* क्लास [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* क्लास [String](../../../system/string/)
* क्लास [ExcelWorkbookImporter](../)
* क्लास [Stream](../../../system.io/stream/)
* नेमस्पेस [Aspose::Slides::Import](../../)
* लाइब्रेरी [Aspose.Slides](../../../)