---
title: GetEffective()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รับคุณสมบัติการจัดรูปแบบเซลล์ตารางที่มีผลโดยคำนึงถึงการสืบทอดและสไตล์ของตารางที่นำไปใช้
type: docs
weight: 118
url: /th/aspose.slides/cellformat/geteffective/
---
## CellFormat::GetEffective() เมธอด


รับคุณสมบัติการจัดรูปแบบเซลล์ตารางที่มีผลโดยคำนึงถึงการสืบทอดและสไตล์ของตารางที่นำไปใช้

```cpp
System::SharedPtr<ICellFormatEffectiveData> Aspose::Slides::CellFormat::GetEffective() override
```


### ค่าที่คืน

อ็อบเจ็กต์ [ICellFormatEffectiveData](../../icellformateffectivedata/).
## หมายเหตุ



ตัวอย่างนี้แสดงการรับรูปแบบการเติมที่มีผลสำหรับส่วนต่าง ๆ ของตรรกะตาราง โปรดทราบว่าการจัดรูปแบบเซลล์จะมีลำดับความสำคัญสูงกว่าการจัดรูปแบบแถว แถวมีลำดับความสำคัญสูงกว่าคอลัมน์ คอลัมน์มีลำดับความสำคัญสูงกว่าทั้งหมดของตาราง ดังนั้นท้ายที่สุดคุณสมบัติ CellFormatEffectiveData จะถูกใช้เพื่อวาดตาราง โค้ดต่อไปนี้เป็นเพียงตัวอย่างของ API 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// ผลลัพธ์และการเปรียบเทียบ
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ICellFormatEffectiveData](../../icellformateffectivedata/)
* คลาส [CellFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)