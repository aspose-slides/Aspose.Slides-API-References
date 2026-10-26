---
title: GetCell()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เรียกคืนเซลจากเวิร์กชีตที่ระบุโดยใช้ดัชนีและพิกัดของเซล
type: docs
weight: 14
url: /th/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) method


เรียกคืนเซลจากเวิร์กชีตที่ระบุโดยใช้ดัชนีและพิกัดของเซล

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| worksheetIndex | **int32_t** | ดัชนีของเวิร์กชีตโดยเริ่มจากศูนย์. |
| row | **int32_t** | ดัชนีแถวของเซลโดยเริ่มจากศูนย์. |
| column | **int32_t** | ดัชนีคอลัมน์ของเซลโดยเริ่มจากศูนย์. |

### ค่า ส่งกลับ

เซลที่ตำแหน่งที่ระบุ.

## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) method


เรียกคืนเซลจากเวิร์กชีตที่ระบุโดยใช้ชื่อและพิกัดของเซล

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | ชื่อของเวิร์กชีต. |
| row | **int32_t** | ดัชนีแถวของเซลโดยเริ่มจากศูนย์. |
| column | **int32_t** | ดัชนีคอลัมน์ของเซลโดยเริ่มจากศูนย์. |

### ค่า ส่งกลับ

เซลที่ตำแหน่งที่ระบุ.

## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) method


เรียกคืนเซลจากเวิร์กชีตที่ระบุโดยใช้ดัชนีและชื่อเซลรูปแบบ Excel (เช่น "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| worksheetIndex | **int32_t** | ดัชนีของเวิร์กชีตโดยเริ่มจากศูนย์. |
| cellName | [System::String](../../../system/string/) | อ้างอิงเซลรูปแบบ Excel (เช่น "A1", "C5"). |

### ค่า ส่งกลับ

เซลที่ตำแหน่งที่ระบุ.

## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, System::String) method


เรียกคืนเซลจากเวิร์กชีตที่ระบุโดยใช้ชื่อเซลรูปแบบ Excel (เช่น "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | ชื่อของเวิร์กชีต. |
| cellName | [System::String](../../../system/string/) | อ้างอิงเซลรูปแบบ Excel (เช่น "A1", "C5"). |

### ค่า ส่งกลับ

เซลที่ตำแหน่งที่ระบุ.

## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IExcelDataCell](../../iexceldatacell/)
* คลาส [IExcelDataWorkbook](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::Excel](../../)
* ไลบรารี [Aspose.Slides](../../../)