---
title: AddTable()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: สร้างตารางใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง
type: docs
weight: 469
url: /th/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) เมธอด

สร้างตารางใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| x | **float** | พิกัด x ของตารางในหน่วยจุด |
| y | **float** | พิกัด y ของตารางในหน่วยจุด |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | อาร์เรย์ของค่า double ที่แสดงความกว้างของคอลัมน์ของตารางในหน่วยจุด |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | อาร์เรย์ของค่า double ที่แสดงความสูงของแถวของตารางในหน่วยจุด |

### ค่าที่ส่งกลับ

ออบเจ็กต์ที่สร้างใหม่ [ITable](../../itable/).

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีการเพิ่มตารางใน PowerPoint [Presentation](../../presentation/).
```cpp
// สร้างอินสแตนซ์ของคลาส Presentation ที่แสดงไฟล์ PPTX
auto pres = System::MakeObject<Presentation>();
// เข้าถึงสไลด์แรก
auto slide = pres->get_Slides()->idx_get(0);
// กำหนดคอลัมน์พร้อมความกว้างและแถวพร้อมความสูง
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// เพิ่มรูปร่างตารางลงสไลด์
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// ตั้งค่ารูปแบบเส้นขอบสำหรับแต่ละเซลล์
for (int32_t row = 0; row < table->get_Rows()->get_Count(); row++)
{
    auto currentRow = table->get_Rows()->idx_get(row);
    for (int32_t col = 0; col < currentRow->get_Count(); col++)
    {
        auto cell = currentRow->idx_get(col);
        auto cellFormat = cell->get_CellFormat();
        cellFormat->get_BorderTop()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderTop()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderTop()->set_Width(5);
        cellFormat->get_BorderBottom()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderBottom()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderBottom()->set_Width(5);
        cellFormat->get_BorderLeft()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderLeft()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderLeft()->set_Width(5);
        cellFormat->get_BorderRight()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderRight()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderRight()->set_Width(5);
    }
}

// รวมเซลล์ที่ 1 และ 2 ของแถวที่ 1
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// เพิ่มข้อความลงในเซลล์ที่รวมกัน
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// บันทึกไฟล์ PPTX ลงดิสก์
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ITable](../../itable/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)