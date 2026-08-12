---
title: Save()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: บันทึกเอกสาร XML ไปยังไฟล์ที่ระบุ หากไฟล์ที่ระบุมีอยู่แล้ว เมธอดนี้จะเขียนทับไฟล์นั้น
type: docs
weight: 534
url: /th/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) เมธอด

บันทึกเอกสาร XML ไปยังไฟล์ที่ระบุ หากไฟล์ที่ระบุมีอยู่แล้ว เมธอดนี้จะเขียนทับไฟล์นั้น

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | [String](../../../system/string/) | ตำแหน่งของไฟล์ที่คุณต้องการบันทึกเอกสาร |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) เมธอด

บันทึกเอกสาร XML ไปยังสตรีมที่ระบุ

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | สตรีมที่คุณต้องการบันทึก |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) เมธอด

บันทึกเอกสาร XML ไปยัง TextWriter ที่ระบุ

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | TextWriter ที่คุณต้องการบันทึก |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) เมธอด

บันทึกเอกสาร XML ไปยัง [XmlWriter](../../xmlwriter/) ที่ระบุ

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | [XmlWriter](../../xmlwriter/) ที่คุณต้องการบันทึก |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlWriter](../../xmlwriter/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)