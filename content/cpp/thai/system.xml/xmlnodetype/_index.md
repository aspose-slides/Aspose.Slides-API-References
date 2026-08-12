---
title: XmlNodeType
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ระบุประเภทของโหนด.
type: docs
weight: 833
url: /th/system.xml/xmlnodetype/
---
## XmlNodeType enum

ระบุประเภทของโหนด.

```cpp
enum class XmlNodeType
```

### ค่าต่าง ๆ

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| None | 0 | This is returned by the [XmlReader](../xmlreader/) if a **Read** method has not been called. |
| Element | 1 | องค์ประกอบ (เช่น **<item>**). |
| Attribute | 2 | แอตทริบิวต์ (เช่น **id='123'**). |
| Text | 3 | เนื้อหาข้อความของโหนด. โหนด [XmlNodeType::Text](./) ไม่สามารถมีโหนดลูกได้. มันสามารถปรากฏเป็นโหนดลูกของโหนด [XmlNodeType::Attribute](./), [XmlNodeType::DocumentFragment](./), [XmlNodeType::Element](./) และ [XmlNodeType::EntityReference](./). |
| CDATA | 4 | ส่วน CDATA (เช่น **my escaped text**). |
| EntityReference | 5 | การอ้างอิงถึงเอนทิตี้ (เช่น **&num;**). |
| Entity | 6 | การประกาศเอนทิตี้ (เช่น **<!ENTITY...>**). |
| ProcessingInstruction | 7 | คำสั่งประมวลผล (เช่น **<?pi test?>**). |
| Comment | 8 | คอมเมนต์ (เช่น ****). |
| Document | 9 | ออบเจ็กต์เอกสารที่ทำหน้าที่เป็นรากของต้นไม้เอกสาร, ให้การเข้าถึงเอกสาร XML ทั้งหมด. |
| DocumentType | 10 | การประกาศประเภทเอกสาร, แสดงโดยแท็กต่อไปนี้ (เช่น **<!DOCTYPE...>**). |
| DocumentFragment | 11 | ส่วนของเอกสาร. |
| Notation | 12 | โนเทชันในประกาศประเภทเอกสาร (เช่น **<!NOTATION...>**). |
| Whitespace | 13 | ช่องว่างระหว่างมาร์กอัป. |
| SignificantWhitespace | 14 | ช่องว่างระหว่างมาร์กอัปในโมเดลเนื้อหาผสม หรือช่องว่างภายในขอบเขต **xml:space=\"preserve\"**. |
| EndElement | 15 | แท็กปิดองค์ประกอบ (เช่น ****). |
| EndEntity | 16 | จะถูกส่งคืนเมื่อ [XmlReader](../xmlreader/) ถึงจุดสิ้นสุดของการแทนที่เอนทิตี้เป็นผลจากการเรียก [XmlReader::ResolveEntity](../xmlreader/resolveentity/). |
| XmlDeclaration | 17 | การประกาศ XML (เช่น **<?xml version='1.0'?>**). โหนด [XmlNodeType::XmlDeclaration](./) ต้องเป็นโหนดแรกในเอกสาร. ไม่สามารถมีลูกได้. เป็นลูกของโหนด [XmlNodeType::Document](./). สามารถมีแอตทริบิวต์ที่ให้ข้อมูลเวอร์ชันและการเข้ารหัส. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)