---
title: InsertFromHtml()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ
type: docs
weight: 209
url: /th/aspose.slides/slidecollection/insertfromhtml/
---
## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งเพื่อแทรก |
| htmlText | [System::String](../../../system/string/) | HTML ที่จะเพิ่ม |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | วัตถุ callback ที่ใช้ดึงวัตถุภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น |
| uri | [System::String](../../../system/string/) | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบ relative |

### ค่าที่คืนกลับ

สไลด์ที่เพิ่ม

## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งเพื่อแทรก |
| htmlText | [System::String](../../../system/string/) | HTML ที่จะเพิ่ม |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | วัตถุ callback ที่ใช้ดึงวัตถุภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น |
| uri | [System::String](../../../system/string/) | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบ relative |
| useSlideWithIndexAsStart | **bool** | ค่าสถานะนี้กำหนดวิธีการเริ่มต้นการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ หาก **true** การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่มีดัชนีที่ระบุ หาก **false** ข้อมูลจะถูกเพิ่มลงในสไลด์ที่สร้างขึ้น |

### ค่าที่คืนกลับ

สไลด์ที่เพิ่ม

## SlideCollection::InsertFromHtml(int32_t, System::String) method

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งเพื่อแทรก |
| htmlText | [System::String](../../../system/string/) | HTML ที่จะเพิ่ม |

### ค่าที่คืนกลับ

สไลด์ที่เพิ่ม

## SlideCollection::InsertFromHtml(int32_t, System::String, bool) method

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งเพื่อแทรก |
| htmlText | [System::String](../../../system/string/) | HTML ที่จะเพิ่ม |
| useSlideWithIndexAsStart | **bool** | ค่าสถานะนี้กำหนดวิธีการเริ่มต้นการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ หาก **true** การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่มีดัชนีที่ระบุ หาก **false** ข้อมูลจะถูกเพิ่มลงในสไลด์ที่สร้างขึ้น |

### ค่าที่คืนกลับ

สไลด์ที่เพิ่ม

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งเพื่อแทรก |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | วัตถุ TextReader ที่จะใช้เป็นแหล่งข้อมูลของไฟล์ HTML |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | วัตถุ callback ที่ใช้ดึงวัตถุภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น |
| uri | [System::String](../../../system/string/) | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบ relative |

### ค่าที่คืนกลับ

สไลด์ที่เพิ่ม

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) method

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งเพื่อแทรก |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | วัตถุ TextReader ที่จะใช้เป็นแหล่งข้อมูลของไฟล์ HTML |

### ค่าที่คืนกลับ

สไลด์ที่เพิ่ม

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งเพื่อแทรก |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | วัตถุ Stream ที่จะใช้เป็นแหล่งข้อมูลของไฟล์ HTML |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | วัตถุ callback ที่ใช้ดึงวัตถุภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น |
| uri | [System::String](../../../system/string/) | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบ relative |

### ค่าที่คืนกลับ

สไลด์ที่เพิ่ม

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งเพื่อแทรก |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | วัตถุ Stream ที่จะใช้เป็นแหล่งข้อมูลของไฟล์ HTML |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | วัตถุ callback ที่ใช้ดึงวัตถุภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น |
| uri | [System::String](../../../system/string/) | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบ relative |
| useSlideWithIndexAsStart | **bool** | ค่าสถานะนี้กำหนดวิธีการเริ่มต้นการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ หาก **true** การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่มีดัชนีที่ระบุ หาก **false** ข้อมูลจะถูกเพิ่มลงในสไลด์ที่สร้างขึ้น |

### ค่าที่คืนกลับ

สไลด์ที่เพิ่ม

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) method

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งเพื่อแทรก |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | วัตถุ Stream ที่จะใช้เป็นแหล่งข้อมูลของไฟล์ HTML |

### ค่าที่คืนกลับ

สไลด์ที่เพิ่ม

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) method

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งเพื่อแทรก |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | วัตถุ Stream ที่จะใช้เป็นแหล่งข้อมูลของไฟล์ HTML |
| useSlideWithIndexAsStart | **bool** | ค่าสถานะนี้กำหนดวิธีการเริ่มต้นการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ หาก **true** การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่มีดัชนีที่ระบุ หาก **false** ข้อมูลจะถูกเพิ่มลงในสไลด์ที่สร้างขึ้น |

### ค่าที่คืนกลับ

สไลด์ที่เพิ่ม

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Class [SlideCollection](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)