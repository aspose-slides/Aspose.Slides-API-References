---
title: IsDerivedFrom()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คืนค่าเพื่อบ่งชี้ว่าประเภทสคีมาที่สืบทอดที่ระบุเป็นประเภทสคีมาฐานที่ระบุหรือไม่.
type: docs
weight: 209
url: /th/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) เมธอด


คืนค่าเพื่อบ่งชี้ว่าประเภทสคีมาที่กำหนดเป็นประเภทสคีมาที่สืบทอดมาจากประเภทสคีมาพื้นฐานที่กำหนด

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | ประเภทที่สืบทอด [XmlSchemaType](../) เพื่อทดสอบ |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | ประเภทฐาน [XmlSchemaType](../) เพื่อทดสอบประเภทที่สืบทอด [XmlSchemaType](../) |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | ค่าหนึ่งของ XmlSchemaDerivationMethod ที่แสดงถึงวิธีการสืบทอดประเภทที่ต้องละเว้นจากการทดสอบ |

### ค่าที่คืนค่า

**true** หากประเภทที่สืบทอดมาจากประเภทฐาน; มิฉะนั้น **false**.

## ดูเพิ่มเติม

* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaType](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)