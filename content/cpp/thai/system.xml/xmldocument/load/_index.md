---
title: Load()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: โหลดเอกสาร XML จาก URL ที่ระบุ
type: docs
weight: 508
url: /th/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) เมธอด

โหลดเอกสาร XML จาก URL ที่ระบุ

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| filename | [String](../../../system/string/) | URL ของไฟล์ที่มีเอกสาร XML ที่จะโหลด URL นี้อาจเป็นไฟล์ในเครื่องหรือ URL HTTP (ที่อยู่ [Web](../../../system.web/)) |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) เมธอด

โหลดเอกสาร XML จากสตรีมที่ระบุ

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | สตรีมที่มีเอกสาร XML ที่จะโหลด |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) เมธอด

โหลดเอกสาร XML จาก TextReader ที่ระบุ

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | TextReader ที่ใช้ป้อนข้อมูล XML เข้าไปในเอกสาร |

## XmlDocument::Load(SharedPtr\<XmlReader\>) เมธอด

โหลดเอกสาร XML จาก [XmlReader](../../xmlreader/) ที่ระบุ

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | [XmlReader](../../xmlreader/) ที่ใช้ป้อนข้อมูล XML เข้าไปในเอกสาร |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [XmlDocument](../)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [TextReader](../../../system.io/textreader/)
* คลาส [XmlReader](../../xmlreader/)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)