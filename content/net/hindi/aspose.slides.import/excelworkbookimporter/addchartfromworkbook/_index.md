---
title: AddChartFromWorkbook
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: निर्दिष्ट Excel वर्कबुक से एक चार्ट प्राप्त करता है और दिए गए shape संग्रह के अंत में निर्दिष्ट निर्देशांकों पर जोड़ता है।
type: docs
weight: 10
url: /hi/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, int, bool) {#addchartfromworkbook}

निर्दिष्ट Excel वर्कबुक से एक चार्ट प्राप्त करता है और दिए गए shape संग्रह के अंत में निर्दिष्ट निर्देशांकों पर जोड़ता है।

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, int chartIndex, bool embedAllWorkbook)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapes | IShapeCollection | चार्ट को जोड़ने के लिए shape संग्रह। |
| x | Single | चार्ट को स्थित करने के लिए X निर्देशांक। |
| y | Single | चार्ट को स्थित करने के लिए Y निर्देशांक। |
| workbook | IExcelDataWorkbook | Excel वर्कबुक। |
| worksheetName | String | चार्ट युक्त वर्कशीट का नाम। |
| chartIndex | Int32 | डालने वाले चार्ट शेप का शून्य-आधारित सूचकांक। यह सूचकांक [`GetChartsFromWorksheet`](../../../aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet) मेथड का उपयोग करके प्राप्त किया जा सकता है। |
| embedAllWorkbook | Boolean | `true` होने पर, संपूर्ण वर्कबुक चार्ट में एम्बेड होगा; `false` होने पर केवल चार्ट डेटा एम्बेड होगा। |

### रिटर्न मान

शेप संग्रह में जोड़ा गया चार्ट।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentException | जब कोई आवश्यक पैरामीटर null या खाली हो, या वर्कबुक में चार्ट न मिले, तब फेंका जाता है। |

### उदाहरण

Example:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, wb, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### देखें

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* interface [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string, bool) {#addchartfromworkbook_1}

निर्दिष्ट Excel वर्कबुक से एक चार्ट प्राप्त करता है और दिए गए shape संग्रह के अंत में निर्दिष्ट निर्देशांकों पर जोड़ता है।

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string chartName, bool embedAllWorkbook)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapes | IShapeCollection | चार्ट को जोड़ने के लिए shape संग्रह। |
| x | Single | चार्ट को स्थित करने के लिए X निर्देशांक। |
| y | Single | चार्ट को स्थित करने के लिए Y निर्देशांक। |
| workbook | IExcelDataWorkbook | Excel वर्कबुक। |
| worksheetName | String | चार्ट युक्त वर्कशीट का नाम। |
| chartName | String | जोड़े जाने वाले चार्ट का नाम। |
| embedAllWorkbook | Boolean | `true` होने पर, संपूर्ण वर्कबुक चार्ट में एम्बेड होगा; `false` होने पर केवल चार्ट डेटा एम्बेड होगा। |

### रिटर्न मान

शेप संग्रह में जोड़ा गया चार्ट।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentException | जब कोई आवश्यक पैरामीटर null या खाली हो, या वर्कबुक में चार्ट न मिले, तब फेंका जाता है। |

### उदाहरण

Example:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    string worksheetName = "worksheet name";
    var worksheetCharts = wb.GetChartsFromWorksheet(worksheetName);
    foreach (var chart in worksheetCharts)
    {
        ISlide slide = pres.Slides.AddEmptySlide(pres.LayoutSlides[0]);
        ExcelWorkbookImporter.AddChartFromWorkbook(slide.Shapes, 10, 10, wb, worksheetName, chart.Key, false);
    }
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### देखें

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* interface [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, Stream, string, string, bool) {#addchartfromworkbook_2}

निर्दिष्ट Excel वर्कबुक से एक चार्ट प्राप्त करता है और दिए गए shape संग्रह के अंत में निर्दिष्ट निर्देशांकों पर जोड़ता है।

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string chartName, bool embedAllWorkbook)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapes | IShapeCollection | चार्ट को जोड़ने के लिए shape संग्रह। |
| x | Single | चार्ट को स्थित करने के लिए X निर्देशांक। |
| y | Single | चार्ट को स्थित करने के लिए Y निर्देशांक। |
| workbookStream | Stream | वर्कबुक डेटा वाला स्ट्रीम। |
| worksheetName | String | चार्ट युक्त वर्कशीट का नाम। |
| chartName | String | जोड़े जाने वाले चार्ट का नाम। |
| embedAllWorkbook | Boolean | `true` होने पर, संपूर्ण वर्कबुक चार्ट में एम्बेड होगा; `false` होने पर केवल चार्ट डेटा एम्बेड होगा। |

### रिटर्न मान

शेप संग्रह में जोड़ा गया चार्ट।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentException | जब कोई आवश्यक पैरामीटर null या खाली हो, या वर्कबुक में चार्ट न मिले, तब फेंका जाता है। |
| InvalidOperationException | जब इनपुट डेटा असमर्थित प्रारूप में हो, तब फेंका जाता है। |

### उदाहरण

Example:

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.LayoutSlides[0].Shapes, 10, 10, fStream, worksheetName, chartName, true);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### देखें

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, string, string, string, bool) {#addchartfromworkbook_3}

निर्दिष्ट Excel वर्कबुक से एक चार्ट प्राप्त करता है और दिए गए shape संग्रह के अंत में निर्दिष्ट निर्देशांकों पर जोड़ता है।

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string chartName, bool embedWorkbook)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapes | IShapeCollection | चार्ट को जोड़ने के लिए shape संग्रह। |
| x | Single | चार्ट को स्थित करने के लिए X निर्देशांक। |
| y | Single | चार्ट को स्थित करने के लिए Y निर्देशांक। |
| workbookPath | String | चार्ट युक्त वर्कबुक का फ़ाइल पथ। |
| worksheetName | String | चार्ट युक्त वर्कशीट का नाम। |
| chartName | String | जोड़े जाने वाले चार्ट का नाम। |
| embedWorkbook | Boolean | `true` होने पर, वर्कबुक चार्ट में एम्बेड होगा; `false` होने पर चार्ट बाहरी वर्कबुक से लिंक करेगा। |

### रिटर्न मान

शेप संग्रह में जोड़ा गया चार्ट।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentException | जब कोई आवश्यक पैरामीटर null या खाली हो, या वर्कबुक में चार्ट न मिले, तब फेंका जाता है। |
| IOException | फ़ाइल तक पहुँचते समय I/O त्रुटि होने पर फेंका जाता है। |
| InvalidOperationException | जब इनपुट डेटा असमर्थित प्रारूप में हो, तब फेंका जाता है। |

### उदाहरण

Example:

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### देखें

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->