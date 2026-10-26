---
title: GetCell()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ดึงเซลล์จากแผ่นงานที่ระบุโดยใช้ดัชนีและพิกัดเซลล์ของมัน.
type: docs
weight: 27
url: /th/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) method

ดึงเซลล์จากแผ่นงานที่ระบุโดยใช้ดัชนีและพิกัดเซลล์.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | ดัชนีของแผ่นงานที่เริ่มต้นจากศูนย์. |
| row | **int32_t** | ดัชนีแถวของเซลล์ที่เริ่มต้นจากศูนย์. |
| column | **int32_t** | ดัชนีคอลัมน์ของเซลล์ที่เริ่มต้นจากศูนย์. |

### ค่าที่ส่งกลับ

เซลล์ที่ตำแหน่งที่ระบุ.

## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) method

ดึงเซลล์จากแผ่นงานที่ระบุโดยใช้ชื่อและพิกัดเซลล์.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | ชื่อของแผ่นงาน. |
| row | **int32_t** | ดัชนีแถวของเซลล์ที่เริ่มต้นจากศูนย์. |
| column | **int32_t** | ดัชนีคอลัมน์ของเซลล์ที่เริ่มต้นจากศูนย์. |

### ค่าที่ส่งกลับ

เซลล์ที่ตำแหน่งที่ระบุ.

## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(int32_t, System::String) method

ดึงเซลล์จากแผ่นงานที่ระบุโดยใช้ดัชนีและชื่อเซลล์แบบ Excel (เช่น "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | ดัชนีของแผ่นงานที่เริ่มต้นจากศูนย์. |
| cellName | [System::String](../../../system/string/) | อ้างอิงเซลล์แบบ Excel (เช่น "A1", "C5"). |

### ค่าที่ส่งกลับ

เซลล์ที่ตำแหน่งที่ระบุ.

## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) method

ดึงเซลล์จากแผ่นงานที่ระบุโดยใช้ชื่อเซลล์แบบ Excel (เช่น "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | ชื่อของแผ่นงาน. |
| cellName | [System::String](../../../system/string/) | อ้างอิงเซลล์แบบ Excel (เช่น "A1", "C5"). |

### ค่าที่ส่งกลับ

เซลล์ที่ตำแหน่งที่ระบุ.

## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IExcelDataCell](../../iexceldatacell/)
* Class [ExcelDataWorkbook](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)