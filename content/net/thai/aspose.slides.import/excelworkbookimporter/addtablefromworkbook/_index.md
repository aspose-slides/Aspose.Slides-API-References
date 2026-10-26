---
title: AddTableFromWorkbook
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: ดึงตารางจาก Excel workbook ที่ระบุและเพิ่มลงที่ส่วนท้ายของ shape collection ที่กำหนดตามพิกัดที่ระบุ
type: docs
weight: 20
url: /th/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## AddTableFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string) {#addtablefromworkbook}

ดึงตารางจาก Excel workbook ที่ระบุและเพิ่มลงที่ส่วนท้ายของ shape collection ที่กำหนดตามพิกัดที่ระบุ

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string cellRange)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapes | IShapeCollection | คอลเลกชันของ shape ที่จะเพิ่มตารางเข้าไป |
| x | Single | พิกัด X สำหรับกำหนดตำแหน่งของตาราง |
| y | Single | พิกัด Y สำหรับกำหนดตำแหน่งของตาราง |
| workbook | IExcelDataWorkbook | ไฟล์ Excel workbook |
| worksheetName | String | ชื่อของ worksheet ที่บรรจุตาราง |
| cellRange | String | ช่วงเซลที่กำหนดตาราง (เช่น "A1:D10") |

### ค่าที่ส่งกลับ

ตารางที่ถูกเพิ่มลงใน shape collection

### ข้อยกเว้น

| ข้อยกเว้น | เงื่อนไข |
| --- | --- |
| ArgumentException | เกิดขึ้นเมื่อพารามิเตอร์ที่จำเป็นใด ๆ เป็น null หรือว่างเปล่า หรือเมื่อ worksheet หรือช่วงเซลที่ระบุไม่ถูกต้อง |
| InvalidOperationException | เกิดขึ้นเมื่อข้อมูลอินพุตอยู่ในรูปแบบที่ไม่รองรับ |

### ตัวอย่าง

```csharp
[C#]
IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbook, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [ITable](../../../aspose.slides/itable)
* อินเทอร์เฟซ [IShapeCollection](../../../aspose.slides/ishapecollection)
* อินเทอร์เฟซ [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* คลาส [ExcelWorkbookImporter](../../excelworkbookimporter)
* เนมสเปซ [Aspose.Slides.Import](../../excelworkbookimporter)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, string, string, string) {#addtablefromworkbook_2}

ดึงตารางจากไฟล์ Excel workbook ที่ระบุและเพิ่มลงในส่วนท้ายของ shape collection ที่กำหนดตามพิกัดที่ระบุ

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string cellRange)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapes | IShapeCollection | คอลเลกชันของ shape ที่จะเพิ่มตารางเข้าไป |
| x | Single | พิกัด X สำหรับกำหนดตำแหน่งของตาราง |
| y | Single | พิกัด Y สำหรับกำหนดตำแหน่งของตาราง |
| workbookPath | String | พาธไปยังไฟล์ Excel workbook |
| worksheetName | String | ชื่อของ worksheet ที่บรรจุตาราง |
| cellRange | String | ช่วงเซลที่กำหนดตาราง (เช่น "A1:D10") |

### ค่าที่ส่งกลับ

ตารางที่ถูกเพิ่มลงใน shape collection

### ข้อยกเว้น

| ข้อยกเว้น | เงื่อนไข |
| --- | --- |
| ArgumentException | เกิดขึ้นเมื่อพารามิเตอร์ที่จำเป็นใด ๆ เป็น null หรือว่างเปล่า หรือเมื่อ worksheet หรือช่วงเซลที่ระบุไม่ถูกต้อง |
| IOException | เกิดขึ้นเมื่อเกิดข้อผิดพลาด I/O ในขณะเข้าถึงไฟล์ workbook |
| InvalidOperationException | เกิดขึ้นเมื่อข้อมูลอินพุตอยู่ในรูปแบบที่ไม่รองรับ |

### ตัวอย่าง

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [ITable](../../../aspose.slides/itable)
* อินเทอร์เฟซ [IShapeCollection](../../../aspose.slides/ishapecollection)
* คลาส [ExcelWorkbookImporter](../../excelworkbookimporter)
* เนมสเปซ [Aspose.Slides.Import](../../excelworkbookimporter)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, Stream, string, string) {#addtablefromworkbook_1}

ดึงตารางจากไฟล์ Excel workbook ที่ระบุและเพิ่มลงในส่วนท้ายของ shape collection ที่กำหนดตามพิกัดที่ระบุ

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string cellRange)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapes | IShapeCollection | คอลเลกชันของ shape ที่จะเพิ่มตารางเข้าไป |
| x | Single | พิกัด X สำหรับกำหนดตำแหน่งของตาราง |
| y | Single | พิกัด Y สำหรับกำหนดตำแหน่งของตาราง |
| workbookStream | Stream | สตรีมที่บรรจุข้อมูล workbook |
| worksheetName | String | ชื่อของ worksheet ที่บรรจุตาราง |
| cellRange | String | ช่วงเซลที่กำหนดตาราง (เช่น "A1:D10") |

### ค่าที่ส่งกลับ

ตารางที่ถูกเพิ่มลงใน shape collection

### ข้อยกเว้น

| ข้อยกเว้น | เงื่อนไข |
| --- | --- |
| ArgumentException | เกิดขึ้นเมื่อพารามิเตอร์ที่จำเป็นใด ๆ เป็น null หรือว่างเปล่า หรือเมื่อ worksheet หรือช่วงเซลที่ระบุไม่ถูกต้อง |
| InvalidOperationException | เกิดขึ้นเมื่อข้อมูลอินพุตอยู่ในรูปแบบที่ไม่รองรับ |

### ตัวอย่าง

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, fStream, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [ITable](../../../aspose.slides/itable)
* อินเทอร์เฟซ [IShapeCollection](../../../aspose.slides/ishapecollection)
* คลาส [ExcelWorkbookImporter](../../excelworkbookimporter)
* เนมสเปซ [Aspose.Slides.Import](../../excelworkbookimporter)
* แอสเซมบลี [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->