---
title: GetEffective()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: รับคุณลักษณะการจัดรูปแบบแถวของตารางที่มีผลโดยพิจารณาการสืบทอดและสไตล์ตารางที่ใช้
type: docs
weight: 1
url: /th/aspose.slides/rowformat/geteffective/
---
## RowFormat::GetEffective() เมธอด

รับคุณลักษณะการจัดรูปแบบแถวของตารางที่มีผลโดยพิจารณาการสืบทอดและสไตล์ตารางที่ใช้

```cpp
System::SharedPtr<IRowFormatEffectiveData> Aspose::Slides::RowFormat::GetEffective() override
```

### ค่าที่คืน

A [IRowFormatEffectiveData](../../irowformateffectivedata/).
## หมายเหตุ

ตัวอย่างนี้แสดงการดึงรูปแบบการเติมที่มีผลสำหรับส่วนต่าง ๆ ของตรรกะตาราง โปรดทราบว่าการจัดรูปแบบเซลล์จะมีระดับความสำคัญสูงกว่าการจัดรูปแบบแถว, แถวสูงกว่าคอลัมน์, คอลัมน์สูงกว่าตารางทั้งหมด ดังนั้นในที่สุดคุณลักษณะ CellFormatEffectiveData จะถูกใช้เสมอสำหรับการวาดตาราง โค้ดต่อไปนี้เป็นเพียงตัวอย่างของ API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// การแสดงผลและการเปรียบเทียบ
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IRowFormatEffectiveData](../../irowformateffectivedata/)
* คลาส [RowFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)