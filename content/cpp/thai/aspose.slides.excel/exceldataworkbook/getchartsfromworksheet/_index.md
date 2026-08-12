---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides สำหรับการอ้างอิง API C++
description: ดึงพจนานุกรมที่ประกอบด้วยดัชนีและชื่อของแผนภูมิทั้งหมดในแผ่นงานที่กำหนดของเวิร์กบุ๊ก Excel.
type: docs
weight: 40
url: /th/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) method

ดึงพจนานุกรมที่ประกอบด้วยดัชนีและชื่อของแผนภูมิทั้งหมดในแผ่นงานที่กำหนดของเวิร์กบุ๊ก [Excel](../../) workbook.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | ชื่อของแผ่นงานที่ต้องการค้นหาแผนภูมิ |

### ค่าที่คืน

พจนานุกรมที่คีย์คือดัชนีของแผนภูมิและค่าคือชื่อของแผนภูมิ

## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## ดูเพิ่มเติม

* ชนิดนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [IDictionary](../../../system.collections.generic/idictionary/)
* คลาส [String](../../../system/string/)
* คลาส [ExcelDataWorkbook](../)
* เนมสเปซ [Aspose::Slides::Excel](../../)
* ไลบรารี [Aspose.Slides](../../../)