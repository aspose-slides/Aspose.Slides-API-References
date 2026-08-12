---
title: Compile()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ทำการคอมไพล์ XML SchemaObject Model (SOM) เป็นข้อมูลสคีมาสำหรับการตรวจสอบความถูกต้อง ใช้เพื่อตรวจสอบโครงสร้างไวยากรณ์และความหมายของ SOM ที่สร้างโดยโปรแกรม การตรวจสอบความถูกต้องเชิงความหมายจะดำเนินการระหว่างการคอมไพล์
type: docs
weight: 352
url: /th/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) เมธอด

ทำการคอมไพล์ XML [Schema](../../)[Object](../../../system/object/) Model (SOM) เป็นข้อมูลสคีมาสำหรับการตรวจสอบความถูกต้อง ใช้ในการตรวจสอบโครงสร้างไวยากรณ์และความหมายของ SOM ที่สร้างโดยโปรแกรม การตรวจสอบความถูกต้องเชิงความหมายจะดำเนินการระหว่างการคอมไพล์

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | ตัวจัดการเหตุการณ์การตรวจสอบที่รับข้อมูลเกี่ยวกับข้อผิดพลาดการตรวจสอบ XML [Schema](../../) |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) เมธอด

ทำการคอมไพล์ XML [Schema](../../)[Object](../../../system/object/) Model (SOM) เป็นข้อมูลสคีมาสำหรับการตรวจสอบความถูกต้อง ใช้ในการตรวจสอบโครงสร้างไวยากรณ์และความหมายของ SOM ที่สร้างโดยโปรแกรม การตรวจสอบความถูกต้องเชิงความหมายจะดำเนินการระหว่างการคอมไพล์

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | ตัวจัดการเหตุการณ์การตรวจสอบที่รับข้อมูลเกี่ยวกับข้อผิดพลาดการตรวจสอบ XML [Schema](../../) |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้เพื่อแก้ไขเนมสเปซที่อ้างอิงในองค์ประกอบ **include** และ **import** |

## ดูเพิ่มเติม

* ประเภทนิยาม [ValidationEventHandler](../../validationeventhandler/)
* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlSchema](../)
* คลาส [XmlResolver](../../../system.xml/xmlresolver/)
* เนมสเปซ [System::Xml::Schema](../../)
* ไลบรารี [Aspose.Slides](../../../)