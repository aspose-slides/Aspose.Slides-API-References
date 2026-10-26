---
title: AddChartFromWorkbook
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: ดึงแผนภูมิจากไฟล์ Excel workbook ที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันของรูปร่างที่กำหนดโดยพิกัดที่ระบุ
type: docs
weight: 10
url: /th/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, int, bool) {#addchartfromworkbook}

ดึงแผนภูมิจากไฟล์ Excel workbook ที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของ shape collection ที่กำหนดโดยพิกัดที่ระบุ

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, int chartIndex, bool embedAllWorkbook)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | คอลเลกชันของรูปร่างที่แผนภูมิจะถูกเพิ่มเข้าไป |
| x | Single | พิกัด X สำหรับการวางตำแหน่งแผนภูมิ |
| y | Single | พิกัด Y สำหรับการวางตำแหน่งแผนภูมิ |
| workbook | IExcelDataWorkbook | ไฟล์ Excel workbook |
| worksheetName | String | ชื่อของ worksheet ที่มีแผนภูมิ |
| chartIndex | Int32 | ดัชนีฐานศูนย์ของรูปแผนภูมิที่ต้องแทรก ดัชนีนี้สามารถได้รับโดยใช้เมธอด [`GetChartsFromWorksheet`](../../../aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet) |
| embedAllWorkbook | Boolean | หาก `true` จะฝัง workbook ทั้งหมดไว้ในแผนภูมิ; หาก `false` จะฝังเฉพาะข้อมูลแผนภูมิเท่านั้น |

### ค่าที่ส่งกลับ

แผนภูมิที่ถูกเพิ่มเข้าไปใน shape collection

### ข้อยกเว้น

| exception | condition |
| --- | --- |
| ArgumentException | เกิดขึ้นเมื่อพารามิเตอร์ใด ๆ ที่จำเป็นเป็น null, ว่างเปล่า หรือเมื่อไม่พบแผนภูมิใน workbook |

### ตัวอย่าง

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, wb, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IChart](../../../aspose.slides.charts/ichart)
* อินเทอร์เฟซ [IShapeCollection](../../../aspose.slides/ishapecollection)
* อินเทอร์เฟซ [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* คลาส [ExcelWorkbookImporter](../../excelworkbookimporter)
* เนมสเปซ [Aspose.Slides.Import](../../excelworkbookimporter)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string, bool) {#addchartfromworkbook_1}

ดึงแผนภูมิจากไฟล์ Excel workbook ที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของ shape collection ที่กำหนดโดยพิกัดที่ระบุ

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | คอลเลกชันของรูปร่างที่แผนภูมิจะถูกเพิ่มเข้าไป |
| x | Single | พิกัด X สำหรับการวางตำแหน่งแผนภูมิ |
| y | Single | พิกัด Y สำหรับการวางตำแหน่งแผนภูมิ |
| workbook | IExcelDataWorkbook | ไฟล์ Excel workbook |
| worksheetName | String | ชื่อของ worksheet ที่มีแผนภูมิ |
| chartName | String | ชื่อของแผนภูมิที่จะถูกเพิ่ม |
| embedAllWorkbook | Boolean | หาก `true` จะฝัง workbook ทั้งหมดไว้ในแผนภูมิ; หาก `false` จะฝังเฉพาะข้อมูลแผนภูมิเท่านั้น |

### ค่าที่ส่งกลับ

แผนภูมิที่ถูกเพิ่มเข้าไปใน shape collection

### ข้อยกเว้น

| exception | condition |
| --- | --- |
| ArgumentException | เกิดขึ้นเมื่อพารามิเตอร์ใด ๆ ที่จำเป็นเป็น null, ว่างเปล่า หรือเมื่อไม่พบแผนภูมิใน workbook |

### ตัวอย่าง

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

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IChart](../../../aspose.slides.charts/ichart)
* อินเทอร์เฟซ [IShapeCollection](../../../aspose.slides/ishapecollection)
* อินเทอร์เฟซ [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* คลาส [ExcelWorkbookImporter](../../excelworkbookimporter)
* เนมสเปซ [Aspose.Slides.Import](../../excelworkbookimporter)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, Stream, string, string, bool) {#addchartfromworkbook_2}

ดึงแผนภูมิจากไฟล์ Excel workbook ที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของ shape collection ที่กำหนดโดยพิกัดที่ระบุ

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | คอลเลกชันของรูปร่างที่แผนภูมิจะถูกเพิ่มเข้าไป |
| x | Single | พิกัด X สำหรับการวางตำแหน่งแผนภูมิ |
| y | Single | พิกัด Y สำหรับการวางตำแหน่งแผนภูมิ |
| workbookStream | Stream | สตรีมที่มีข้อมูล workbook |
| worksheetName | String | ชื่อของ worksheet ที่มีแผนภูมิ |
| chartName | String | ชื่อของแผนภูมิที่จะถูกเพิ่ม |
| embedAllWorkbook | Boolean | หาก `true` จะฝัง workbook ทั้งหมดไว้ในแผนภูมิ; หาก `false` จะฝังเฉพาะข้อมูลแผนภูมิเท่านั้น |

### ค่าที่ส่งกลับ

แผนภูมิที่ถูกเพิ่มเข้าไปใน shape collection

### ข้อยกเว้น

| exception | condition |
| --- | --- |
| ArgumentException | เกิดขึ้นเมื่อพารามิเตอร์ใด ๆ ที่จำเป็นเป็น null, ว่างเปล่า หรือเมื่อไม่พบแผนภูมิใน workbook |
| InvalidOperationException | เกิดขึ้นเมื่อข้อมูลอินพุตอยู่ในรูปแบบที่ไม่รองรับ |

### ตัวอย่าง

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.LayoutSlides[0].Shapes, 10, 10, fStream, worksheetName, chartName, true);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IChart](../../../aspose.slides.charts/ichart)
* อินเทอร์เฟซ [IShapeCollection](../../../aspose.slides/ishapecollection)
* คลาส [ExcelWorkbookImporter](../../excelworkbookimporter)
* เนมสเปซ [Aspose.Slides.Import](../../excelworkbookimporter)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, string, string, string, bool) {#addchartfromworkbook_3}

ดึงแผนภูมิจากไฟล์ Excel workbook ที่ระบุและเพิ่มลงในตำแหน่งสุดท้ายของ shape collection ที่กำหนดโดยพิกัดที่ระบุ

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string chartName, bool embedWorkbook)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | คอลเลกชันของรูปร่างที่แผนภูมิจะถูกเพิ่มเข้าไป |
| x | Single | พิกัด X สำหรับการวางตำแหน่งแผนภูมิ |
| y | Single | พิกัด Y สำหรับการวางตำแหน่งแผนภูมิ |
| workbookPath | String | เส้นทางไฟล์ของ workbook ที่มีแผนภูมิ |
| worksheetName | String | ชื่อของ worksheet ที่มีแผนภูมิ |
| chartName | String | ชื่อของแผนภูมิที่จะถูกเพิ่ม |
| embedWorkbook | Boolean | หาก `true` จะฝัง workbook ไว้ในแผนภูมิ; หาก `false` แผนภูมิจะเชื่อมโยงไปยัง workbook ภายนอก |

### ค่าที่ส่งกลับ

แผนภูมิที่ถูกเพิ่มเข้าไปใน shape collection

### ข้อยกเว้น

| exception | condition |
| --- | --- |
| ArgumentException | เกิดขึ้นเมื่อพารามิเตอร์ใด ๆ ที่จำเป็นเป็น null, ว่างเปล่า หรือเมื่อไม่พบแผนภูมิใน workbook |
| IOException | เกิดขึ้นเมื่อเกิดข้อผิดพลาดการอ่าน/เขียนไฟล์ |
| InvalidOperationException | เกิดขึ้นเมื่อข้อมูลอินพุตอยู่ในรูปแบบที่ไม่รองรับ |

### ตัวอย่าง

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IChart](../../../aspose.slides.charts/ichart)
* อินเทอร์เฟซ [IShapeCollection](../../../aspose.slides/ishapecollection)
* คลาส [ExcelWorkbookImporter](../../excelworkbookimporter)
* เนมสเปซ [Aspose.Slides.Import](../../excelworkbookimporter)
* แอสเซมบลี [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->