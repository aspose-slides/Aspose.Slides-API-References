---
title: AddTableFromWorkbook()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ดึงตารางจากเวิร์กบุ๊ก Excel ที่ระบุและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปร่างที่กำหนดตามพิกัดที่ระบุไว้
type: docs
weight: 14
url: /th/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) เมธอด

ดึงตารางจากเวิร์กบุ๊ก [Excel](../../../aspose.slides.excel/) ที่ระบุและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปร่างที่ให้ไว้ที่พิกัดที่ระบุ

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | คอลเลกชันรูปร่างที่ตารางจะถูกเพิ่มเข้าไป |
| x | **float** | พิกัด X สำหรับการวางตำแหน่งตาราง |
| y | **float** | พิกัด Y สำหรับการวางตำแหน่งตาราง |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | เวิร์กบุ๊ก [Excel](../../../aspose.slides.excel/) |
| worksheetName | [System::String](../../../system/string/) | ชื่อของแผ่นงานที่มีตาราง |
| cellRange | [System::String](../../../system/string/) | ช่วงเซลล์ที่กำหนดตาราง (เช่น "A1:D10") |

### ค่าที่คืน

ตารางที่ถูกเพิ่มเข้าไปในคอลเลกชันรูปร่าง.

## หมายเหตุ




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) เมธอด

ดึงตารางจากไฟล์เวิร์กบุ๊ก [Excel](../../../aspose.slides.excel/) ที่ระบุและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปร่างที่ให้ไว้ที่พิกัดที่ระบุ

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | คอลเลกชันรูปร่างที่ตารางจะถูกเพิ่มเข้าไป |
| x | **float** | พิกัด X สำหรับการวางตำแหน่งตาราง |
| y | **float** | พิกัด Y สำหรับการวางตำแหน่งตาราง |
| workbookPath | [System::String](../../../system/string/) | พาธไปยังไฟล์เวิร์กบุ๊ก [Excel](../../../aspose.slides.excel/) |
| worksheetName | [System::String](../../../system/string/) | ชื่อของแผ่นงานที่มีตาราง |
| cellRange | [System::String](../../../system/string/) | ช่วงเซลล์ที่กำหนดตาราง (เช่น "A1:D10") |

### ค่าที่คืน

ตารางที่ถูกเพิ่มเข้าไปในคอลเลกชันรูปร่าง.

## หมายเหตุ




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) เมธอด

ดึงตารางจากไฟล์เวิร์กบุ๊ก [Excel](../../../aspose.slides.excel/) ที่ระบุและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปร่างที่ให้ไว้ที่พิกัดที่ระบุ

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | คอลเลกชันรูปร่างที่ตารางจะถูกเพิ่มเข้าไป |
| x | **float** | พิกัด X สำหรับการวางตำแหน่งตาราง |
| y | **float** | พิกัด Y สำหรับการวางตำแหน่งตาราง |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมที่มีข้อมูลของเวิร์กบุ๊ก |
| worksheetName | [System::String](../../../system/string/) | ชื่อของแผ่นงานที่มีตาราง |
| cellRange | [System::String](../../../system/string/) | ช่วงเซลล์ที่กำหนดตาราง (เช่น "A1:D10") |

### ค่าที่คืน

ตารางที่ถูกเพิ่มเข้าไปในคอลเลกชันรูปร่าง.

## หมายเหตุ




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* ประเภทกำหนดชื่อ [SharedPtr](../../../system/sharedptr/)
* คลาส [ITable](../../../aspose.slides/itable/)
* คลาส [IShapeCollection](../../../aspose.slides/ishapecollection/)
* คลาส [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* คลาส [String](../../../system/string/)
* คลาส [ExcelWorkbookImporter](../)
* คลาส [Stream](../../../system.io/stream/)
* เนมส페ซ [Aspose::Slides::Import](../../)
* ไลบรารี [Aspose.Slides](../../../)