---
title: AddTableFromWorkbook
second_title: Aspose.Sildes .NET के लिए API संदर्भ
description: निर्दिष्ट Excel वर्कबुक से एक टेबल प्राप्त करता है और निर्दिष्ट निर्देशांक पर दी गई शैप कलेक्शन के अंत में इसे जोड़ता है।
type: docs
weight: 20
url: /hi/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## AddTableFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string) {#addtablefromworkbook}

निर्दिष्ट Excel वर्कबुक से एक टेबल प्राप्त करता है और निर्दिष्ट निर्देशांक पर दी गई शैप कलेक्शन के अंत में इसे जोड़ता है।

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string cellRange)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | टेबल को जोड़ने के लिये शैप कलेक्शन। |
| x | Single | टेबल की स्थिति के लिये X निर्देशांक। |
| y | Single | टेबल की स्थिति के लिये Y निर्देशांक। |
| workbook | IExcelDataWorkbook | Excel वर्कबुक। |
| worksheetName | String | टेबल सम्मिलित करने वाले वर्कशीट का नाम। |
| cellRange | String | टेबल को परिभाषित करने वाली सेल रेंज (उदाहरण के लिये, "A1:D10")। |

### रिटर्न मान

शैप कलेक्शन में जोड़ी गई टेबल।

### अपवाद

| exception | condition |
| --- | --- |
| ArgumentException | जब कोई आवश्यक पैरामीटर null या खाली हो, या निर्दिष्ट वर्कशीट या सेल रेंज अमान्य हो तो थ्रो किया जाता है। |
| InvalidOperationException | जब इनपुट डेटा असमर्थित प्रारूप में हो तो थ्रो किया जाता है। |

### उदाहरण

```csharp
[C#]
IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbook, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### देखें

* इंटरफ़ेस [ITable](../../../aspose.slides/itable)
* इंटरफ़ेस [IShapeCollection](../../../aspose.slides/ishapecollection)
* इंटरफ़ेस [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* क्लास [ExcelWorkbookImporter](../../excelworkbookimporter)
* नेमस्पेस [Aspose.Slides.Import](../../excelworkbookimporter)
* असेंबली [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, string, string, string) {#addtablefromworkbook_2}

निर्दिष्ट Excel वर्कबुक फ़ाइल से एक टेबल प्राप्त करता है और निर्दिष्ट निर्देशांक पर दी गई शैप कलेक्शन के अंत में इसे जोड़ता है।

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string cellRange)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | टेबल को जोड़ने के लिये शैप कलेक्शन। |
| x | Single | टेबल की स्थिति के लिये X निर्देशांक। |
| y | Single | टेबल की स्थिति के लिये Y निर्देशांक। |
| workbookPath | String | Excel वर्कबुक फ़ाइल का पथ। |
| worksheetName | String | टेबल सम्मिलित करने वाले वर्कशीट का नाम। |
| cellRange | String | टेबल को परिभाषित करने वाली सेल रेंज (उदाहरण के लिये, "A1:D10")। |

### रिटर्न मान

शैप कलेक्शन में जोड़ी गई टेबल।

### अपवाद

| exception | condition |
| --- | --- |
| ArgumentException | जब कोई आवश्यक पैरामीटर null या खाली हो, या निर्दिष्ट वर्कशीट या सेल रेंज अमान्य हो तो थ्रो किया जाता है। |
| IOException | जब वर्कबुक फ़ाइल तक पहुंचते समय कोई I/O त्रुटि होती है तो थ्रो किया जाता है। |
| InvalidOperationException | जब इनपुट डेटा असमर्थित प्रारूप में हो तो थ्रो किया जाता है। |

### उदाहरण

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### देखें

* इंटरफ़ेस [ITable](../../../aspose.slides/itable)
* इंटरफ़ेस [IShapeCollection](../../../aspose.slides/ishapecollection)
* क्लास [ExcelWorkbookImporter](../../excelworkbookimporter)
* नेमस्पेस [Aspose.Slides.Import](../../excelworkbookimporter)
* असेंबली [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, Stream, string, string) {#addtablefromworkbook_1}

निर्दिष्ट Excel वर्कबुक फ़ाइल से एक टेबल प्राप्त करता है और निर्दिष्ट निर्देशांक पर दी गई शैप कलेक्शन के अंत में इसे जोड़ता है।

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string cellRange)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | टेबल को जोड़ने के लिये शैप कलेक्शन। |
| x | Single | टेबल की स्थिति के लिये X निर्देशांक। |
| y | Single | टेबल की स्थिति के लिये Y निर्देशांक। |
| workbookStream | Stream | वर्कबुक डेटा वाला स्ट्रीम। |
| worksheetName | String | टेबल सम्मिलित करने वाले वर्कशीट का नाम। |
| cellRange | String | टेबल को परिभाषित करने वाली सेल रेंज (उदाहरण के लिये, "A1:D10")। |

### रिटर्न मान

शैप कलेक्शन में जोड़ी गई टेबल।

### अपवाद

| exception | condition |
| --- | --- |
| ArgumentException | जब कोई आवश्यक पैरामीटर null या खाली हो, या निर्दिष्ट वर्कशीट या सेल रेंज अमान्य हो तो थ्रो किया जाता है। |
| InvalidOperationException | जब इनपुट डेटा असमर्थित प्रारूप में हो तो थ्रो किया जाता है। |

### उदाहरण

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, fStream, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### देखें

* इंटरफ़ेस [ITable](../../../aspose.slides/itable)
* इंटरफ़ेस [IShapeCollection](../../../aspose.slides/ishapecollection)
* क्लास [ExcelWorkbookImporter](../../excelworkbookimporter)
* नेमस्पेस [Aspose.Slides.Import](../../excelworkbookimporter)
* असेंबली [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->