---
title: GetEffective()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ดึงคุณสมบัติการจัดรูปแบบตารางที่มีประสิทธิภาพพร้อมการสืบทอดและสไตล์ตารางที่ใช้
type: docs
weight: 40
url: /th/aspose.slides/tableformat/geteffective/
---
## TableFormat::GetEffective() เมธอด

ดึงคุณสมบัติการจัดรูปแบบตารางที่มีประสิทธิภาพพร้อมการสืบทอดและสไตล์ตารางที่ใช้.

```cpp
System::SharedPtr<ITableFormatEffectiveData> Aspose::Slides::TableFormat::GetEffective() override
```

### ค่าที่ส่งคืน

A [ITableFormatEffectiveData](../../itableformateffectivedata/).
## หมายเหตุ



ตัวอย่างนี้แสดงการดึงรูปแบบการเติมที่มีประสิทธิภาพสำหรับส่วนต่าง ๆ ของตรรกะตาราง โปรดทราบว่าการจัดรูปแบบเซลล์มีลำดับความสำคัญสูงกว่าการจัดรูปแบบแถว แถวมีลำดับความสำคัญสูงกว่าคอลัมน์ และคอลัมน์มีลำดับความสำคัญสูงกว่าตารางทั้งหมด ดังนั้นคุณสมบัติ CellFormatEffectiveData จะถูกใช้เสมอเพื่อวาดตาราง โค้ดต่อไปนี้เป็นเพียงตัวอย่างของ API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ITableFormatEffectiveData](../../itableformateffectivedata/)
* คลาส [TableFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)