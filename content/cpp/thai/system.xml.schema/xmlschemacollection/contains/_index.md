---
title: Contains()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คืนค่าแสดงว่ามี targetNamespace ของ XmlSchema ที่ระบุอยู่ในคอลเลกชันหรือไม่.
type: docs
weight: 66
url: /th/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) เมธอด


คืนค่าแสดงว่ามี **targetNamespace** ของ [XmlSchema](../../xmlschema/) ที่ระบุอยู่ในคอลเลกชันหรือไม่.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```


### พารามิเตอร์

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | อ็อบเจกต์ [XmlSchema](../../xmlschema/) |

### ค่าที่คืน

**true** หากมีสคีมาในคอลเลกชันที่มี **targetNamespace** เดียวกัน; มิฉะนั้น **false**.

## XmlSchemaCollection::Contains(const String\&) เมธอด


คืนค่าแสดงว่ามีสคีมาที่มีเนมสเปซที่ระบุอยู่ในคอลเลกชันหรือไม่.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```


### พารามิเตอร์

| Parameter | Type | Description |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI ของเนมสเปซที่เชื่อมโยงกับสคีมา สำหรับ XML Schema โดยทั่วไปจะเป็น target namespace. |

### ค่าที่คืน

**true** หากมีสคีมาที่มีเนมสเปซที่ระบุอยู่ในคอลเลกชัน; มิฉะนั้น **false**.

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlSchema](../../xmlschema/)
* คลาส [XmlSchemaCollection](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Xml::Schema](../../)
* ไลบรารี [Aspose.Slides](../../../)