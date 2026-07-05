---
title: Name
second_title: Aspose.Sildes .NET के लिए API संदर्भ
description: चार्ट डेटा सेल का नाम प्राप्त करता है।
type: docs
weight: 20
url: /hi/aspose.slides.excel/exceldatacell/name/
---
## ExcelDataCell.Name गुण

चार्ट डेटा सेल का नाम प्राप्त करता है।

```csharp
public string Name { get; }
```

### उदाहरण

उदाहरण:

```csharp
[C#]
ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
IExcelDataCell cell = wb.GetCell(1, 1, 1);
Console.WriteLine(cell.Name); //आउटपुट: "B2"
```

### संबंधित देखें

* क्लास [ExcelDataCell](../../exceldatacell)
* नामस्थान [Aspose.Slides.Excel](../../exceldatacell)
* असेंबली [Aspose.Slides](../../../)

<!-- संशोधित न करें: xmldocmd द्वारा Aspose.Slides.dll के लिए उत्पन्न किया गया -->