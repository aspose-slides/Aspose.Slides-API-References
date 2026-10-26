---
title: GetEffective()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับคุณสมบัติการจัดรูปแบบคอลัมน์ของตารางที่มีผลเที่ยงพร้อมการสืบทอดและการใช้สไตล์ของตาราง
type: docs
weight: 1
url: /th/aspose.slides/columnformat/geteffective/
---
## ColumnFormat::GetEffective() เมธอด

รับคุณสมบัติการจัดรูปแบบคอลัมน์ของตารางที่มีผลเที่ยงพร้อมการสืบทอดและการใช้สไตล์ของตาราง

```cpp
System::SharedPtr<IColumnFormatEffectiveData> Aspose::Slides::ColumnFormat::GetEffective() override
```

### ค่าที่ส่งคืน

หนึ่ง [IColumnFormatEffectiveData](../../icolumnformateffectivedata/).

## หมายเหตุ

ตัวอย่างนี้แสดงการรับรูปแบบการเติมที่มีผลสำหรับส่วนต่าง ๆ ของตรรกะตาราง โปรดทราบว่าการจัดรูปแบบเซลล์มีลำดับความสำคัญสูงกว่าการจัดรูปแบบแถว แถวมีลำดับความสำคัญสูงกว่าคอลัมน์ คอลัมน์มีลำดับความสำคัญสูงกว่าตารางทั้งหมด ดังนั้นในที่สุดคุณสมบัติ CellFormatEffectiveData จะถูกใช้เสมอเพื่อวาดตาราง โค้ดต่อไปนี้เป็นเพียงตัวอย่างของ API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// แสดงผลและการเปรียบเทียบ
```

## ดูเพิ่มเติม

* การกำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)
* คลาส [ColumnFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)