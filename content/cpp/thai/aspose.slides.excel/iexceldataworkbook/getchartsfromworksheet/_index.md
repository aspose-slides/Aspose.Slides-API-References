---
title: GetChartsFromWorksheet()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ดึงพจนานุกรมที่มีดัชนีและชื่อของแผนภูมิทั้งหมดในแผ่นงานที่ระบุของสมุดงาน Excel.
type: docs
weight: 27
url: /th/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) เมธอด


ดึงพจนานุกรมที่มีดัชนีและชื่อของแผนภูมิทั้งหมดในแผ่นงานที่ระบุของสมุดงาน [Excel](../../) workbook.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | ชื่อของแผ่นงานที่ใช้ค้นหาแผนภูมิ. |

### ค่าที่ส่งคืน

พจนานุกรมที่คีย์คือดัชนีแผนภูมิและค่าเป็นชื่อแผนภูมิ.
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IDictionary](../../../system.collections.generic/idictionary/)
* คลาส [String](../../../system/string/)
* คลาส [IExcelDataWorkbook](../)
* เนมสเปซ [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)