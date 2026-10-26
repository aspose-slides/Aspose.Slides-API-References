---
title: AddChartFromWorkbook()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ดึงแผนภูมิจากเวิร์กบุ๊ก Excel ที่ระบุและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่างที่กำหนดตามพิกัดที่ระบุ
type: docs
weight: 1
url: /th/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) เมธอด


ดึงแผนภูมิจากเวิร์คบุ๊ก [Excel](../../../aspose.slides.excel/) ที่ระบุและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่างที่ให้ไว้ที่พิกัดที่ระบุ

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | คอลเลกชันรูปร่างที่แผนภูมิจะถูกเพิ่มเข้าไป |
| x | **float** | พิกัด X สำหรับตำแหน่งของแผนภูมิ |
| y | **float** | พิกัด Y สำหรับตำแหน่งของแผนภูมิ |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | เวิร์คบุ๊ก [Excel](../../../aspose.slides.excel/) |
| worksheetName | [System::String](../../../system/string/) | ชื่อของแผ่นงานที่มีแผนภูมิอยู่ |
| chartIndex | **int32_t** | ดัชนีที่เริ่มจากศูนย์ของรูปร่างแผนภูมิที่จะใส่ ดัชนีนี้สามารถรับได้โดยใช้เมธอด [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../) |
| embedAllWorkbook | **bool** | หาก **true** เวิร์คบุ๊กทั้งหมดจะถูกฝังไว้ในแผนภูมิ; หาก **false** จะฝังเฉพาะข้อมูลแผนภูมิเท่านั้น |

### ค่าที่ส่งกลับ

แผนภูมิที่ถูกเพิ่มไปยังคอลเลกชันรูปร่าง
## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) เมธอด


ดึงแผนภูมิจากเวิร์คบุ๊ก [Excel](../../../aspose.slides.excel/) ที่ระบุและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่างที่ให้ไว้ที่พิกัดที่ระบุ

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | คอลเลกชันรูปร่างที่แผนภูมิจะถูกเพิ่มเข้าไป |
| x | **float** | พิกัด X สำหรับตำแหน่งของแผนภูมิ |
| y | **float** | พิกัด Y สำหรับตำแหน่งของแผนภูมิ |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | เวิร์คบุ๊ก [Excel](../../../aspose.slides.excel/) |
| worksheetName | [System::String](../../../system/string/) | ชื่อของแผ่นงานที่มีแผนภูมิอยู่ |
| chartName | [System::String](../../../system/string/) | ชื่อของแผนภูมิที่จะเพิ่ม |
| embedAllWorkbook | **bool** | หาก **true** เวิร์คบุ๊กทั้งหมดจะถูกฝังไว้ในแผนภูมิ; หาก **false** จะฝังเฉพาะข้อมูลแผนภูมิเท่านั้น |

### ค่าที่ส่งกลับ

แผนภูมิที่ถูกเพิ่มไปยังคอลเลกชันรูปร่าง
## หมายเหตุ



ตัวอย่าง: 
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

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String, bool) เมธอด


ดึงแผนภูมิจากเวิร์คบุ๊ก [Excel](../../../aspose.slides.excel/) ที่ระบุและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่างที่ให้ไว้ที่พิกัดที่ระบุ

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | คอลเลกชันรูปร่างที่แผนภูมิจะถูกเพิ่มเข้าไป |
| x | **float** | พิกัด X สำหรับตำแหน่งของแผนภูมิ |
| y | **float** | พิกัด Y สำหรับตำแหน่งของแผนภูมิ |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมที่มีข้อมูลเวิร์คบุ๊ก |
| worksheetName | [System::String](../../../system/string/) | ชื่อของแผ่นงานที่มีแผนภูมิอยู่ |
| chartName | [System::String](../../../system/string/) | ชื่อของแผนภูมิที่จะเพิ่ม |
| embedAllWorkbook | **bool** | หาก **true** เวิร์คบุ๊กทั้งหมดจะถูกฝังไว้ในแผนภูมิ; หาก **false** จะฝังเฉพาะข้อมูลแผนภูมิเท่านั้น |

### ค่าที่ส่งกลับ

แผนภูมิที่ถูกเพิ่มไปยังคอลเลกชันรูปร่าง
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) เมธอด


ดึงแผนภูมิจากเวิร์คบุ๊ก [Excel](../../../aspose.slides.excel/) ที่ระบุและเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปร่างที่ให้ไว้ที่พิกัดที่ระบุ

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | คอลเลกชันรูปร่างที่แผนภูมิจะถูกเพิ่มเข้าไป |
| x | **float** | พิกัด X สำหรับตำแหน่งของแผนภูมิ |
| y | **float** | พิกัด Y สำหรับตำแหน่งของแผนภูมิ |
| workbookPath | [System::String](../../../system/string/) | เส้นทางไฟล์ไปยังเวิร์คบุ๊กที่มีแผนภูมิ |
| worksheetName | [System::String](../../../system/string/) | ชื่อของแผ่นงานที่มีแผนภูมิอยู่ |
| chartName | [System::String](../../../system/string/) | ชื่อของแผนภูมิที่จะเพิ่ม |
| embedWorkbook | **bool** | หาก **true** เวิร์คบุ๊กจะถูกฝังในแผนภูมิ; หาก **false** แผนภูมิจะลิงก์ไปยังเวิร์คบุ๊กภายนอก |

### ค่าที่ส่งกลับ

แผนภูมิที่ถูกเพิ่มไปยังคอลเลกชันรูปร่าง
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IChart](../../../aspose.slides.charts/ichart/)
* คลาส [IShapeCollection](../../../aspose.slides/ishapecollection/)
* คลาส [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* คลาส [String](../../../system/string/)
* คลาส [ExcelWorkbookImporter](../)
* คลาส [Stream](../../../system.io/stream/)
* เนมสเปซ [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)