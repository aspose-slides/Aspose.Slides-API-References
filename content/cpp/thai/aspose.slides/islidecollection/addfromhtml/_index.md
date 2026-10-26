---
title: AddFromHtml()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังส่วนท้ายของคอลเลกชัน
type: docs
weight: 144
url: /th/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) เมธอด


สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังส่วนท้ายของคอลเลกชัน

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML ที่จะเพิ่ม |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | อ็อบเจ็กต์ callback ที่ใช้ในการดึงวัตถุภายนอก หากพารามิเตอร์นี้เป็นค่า null วัตถุภายนอกทั้งหมดจะถูกละเว้น |
| uri | [System::String](../../../system/string/) | URI ของ HTML ที่ระบุ ใช้ในการแก้ไขลิงก์แบบสัมพันธ์ |

### ค่าที่ส่งกลับ

สไลด์ที่เพิ่ม

## ISlideCollection::AddFromHtml(System::String) เมธอด


สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังส่วนท้ายของคอลเลกชัน

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML ที่จะเพิ่ม |

### ค่าที่ส่งกลับ

สไลด์ที่เพิ่ม

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) เมธอด


สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังส่วนท้ายของคอลเลกชัน

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | อ็อบเจ็กต์ TextReader ซึ่งจะใช้เป็นแหล่งของไฟล์ HTML |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | อ็อบเจ็กต์ callback ที่ใช้ในการดึงวัตถุภายนอก หากพารามิเตอร์นี้เป็นค่า null วัตถุภายนอกทั้งหมดจะถูกละเว้น |
| uri | [System::String](../../../system/string/) | URI ของ HTML ที่ระบุ ใช้ในการแก้ไขลิงก์แบบสัมพันธ์ |

### ค่าที่ส่งกลับ

สไลด์ที่เพิ่ม

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) เมธอด


สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังส่วนท้ายของคอลเลกชัน

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | อ็อบเจ็กต์ TextReader ซึ่งจะใช้เป็นแหล่งของไฟล์ HTML |

### ค่าที่ส่งกลับ

สไลด์ที่เพิ่ม

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) เมธอด


สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังส่วนท้ายของคอลเลกชัน

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | อ็อบเจ็กต์ Stream ซึ่งจะใช้เป็นแหล่งของไฟล์ HTML |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | อ็อบเจ็กต์ callback ที่ใช้ในการดึงวัตถุภายนอก หากพารามิเตอร์นี้เป็นค่า null วัตถุภายนอกจากจะถูกละเว้น |
| uri | [System::String](../../../system/string/) | URI ของ HTML ที่ระบุ ใช้ในการแก้ไขลิงก์แบบสัมพันธ์ |

### ค่าที่ส่งกลับ

สไลด์ที่เพิ่ม

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) เมธอด


สร้างสไลด์จากข้อความ HTML และเพิ่มไปยังส่วนท้ายของคอลเลกชัน

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | อ็อบเจ็กต์ Stream ซึ่งจะใช้เป็นแหล่งของไฟล์ HTML |

### ค่าที่ส่งกลับ

สไลด์ที่เพิ่ม

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISlide](../../islide/)
* คลาส [String](../../../system/string/)
* คลาส [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* คลาส [ISlideCollection](../)
* คลาส [TextReader](../../../system.io/textreader/)
* คลาส [Stream](../../../system.io/stream/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)