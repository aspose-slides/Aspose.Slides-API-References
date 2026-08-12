---
title: InsertFromHtml()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ
type: docs
weight: 157
url: /th/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งที่จะใส่ |
| htmlText | [System::String](../../../system/string/) | HTML ที่จะเพิ่ม |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | อ็อบเจ็กต์ callback ที่ใช้ในการดึงอ็อบเจ็กต์ภายนอก หากพารามิเตอร์นี้เป็นค่า null จะละเว้นอ็อบเจ็กต์ภายนอกทั้งหมด |
| uri | [System::String](../../../system/string/) | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์ที่เป็นแบบสัมพันธ์ |

### ค่าที่ส่งกลับ

สไลด์ที่เพิ่ม

## ISlideCollection::InsertFromHtml(int32_t, System::String) method

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งที่จะใส่ |
| htmlText | [System::String](../../../system/string/) | HTML ที่จะเพิ่ม |

### ค่าที่ส่งกลับ

สไลด์ที่เพิ่ม

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งที่จะใส่ |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | อ็อบเจ็กต์ TextReader ซึ่งจะถูกใช้เป็นแหล่งข้อมูลของไฟล์ HTML |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | อ็อบเจ็กต์ callback ที่ใช้ในการดึงอ็อบเจ็กต์ภายนอก หากพารามิเตอร์นี้เป็นค่า null จะละเว้นอ็อบเจ็กต์ภายนอกทั้งหมด |
| uri | [System::String](../../../system/string/) | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์ที่เป็นแบบสัมพันธ์ |

### ค่าที่ส่งกลับ

สไลด์ที่เพิ่ม

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) method

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งที่จะใส่ |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | อ็อบเจ็กต์ TextReader ซึ่งจะถูกใช้เป็นแหล่งข้อมูลของไฟล์ HTML |

### ค่าที่ส่งกลับ

สไลด์ที่เพิ่ม

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งที่จะใส่ |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | อ็อบเจ็กต์ Stream ที่จะใช้เป็นแหล่งข้อมูลของไฟล์ HTML |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | อ็อบเจ็กต์ callback ที่ใช้ในการดึงอ็อบเจ็กต์ภายนอก หากพารามิเตอร์นี้เป็นค่า null จะละเว้นอ็อบเจ็กต์ภายนอกทั้งหมด |
| uri | [System::String](../../../system/string/) | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์ที่เป็นแบบสัมพันธ์ |

### ค่าที่ส่งกลับ

สไลด์ที่เพิ่ม

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) method

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งที่จะใส่ |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | อ็อบเจ็กต์ Stream ที่จะใช้เป็นแหล่งข้อมูลของไฟล์ HTML |

### ค่าที่ส่งกลับ

สไลด์ที่เพิ่ม

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) method

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งที่จะใส่ |
| htmlText | [System::String](../../../system/string/) | HTML ที่จะเพิ่ม |
| useSlideWithIndexAsStart | **bool** | แฟล็กนี้กำหนดวิธีเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ หาก **true** การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่มีดัชนีนั้น หาก **false** ข้อมูลจะถูกเพิ่มไปยังสไลด์ที่สร้างขึ้น |

### ค่าที่ส่งกลับ

สไลด์ที่เพิ่ม

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งที่จะใส่ |
| htmlText | [System::String](../../../system/string/) | HTML ที่จะเพิ่ม |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | อ็อบเจ็กต์ callback ที่ใช้ในการดึงอ็อบเจ็กต์ภายนอก หากพารามิเตอร์นี้เป็นค่า null จะละเว้นอ็อบเจ็กต์ภายนอกทั้งหมด |
| uri | [System::String](../../../system/string/) | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์ที่เป็นแบบสัมพันธ์ |
| useSlideWithIndexAsStart | **bool** | แฟล็กนี้กำหนดวิธีเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ หาก **true** การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่มีดัชนีนั้น หาก **false** ข้อมูลจะถูกเพิ่มไปยังสไลด์ที่สร้างขึ้น |

### ค่าที่ส่งกลับ

สไลด์ที่เพิ่ม

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) method

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งที่จะใส่ |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | อ็อบเจ็กต์ Stream ที่จะใช้เป็นแหล่งข้อมูลของไฟล์ HTML |
| useSlideWithIndexAsStart | **bool** | แฟล็กนี้กำหนดวิธีเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ หาก **true** การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่มีดัชนีนั้น หาก **false** ข้อมูลจะถูกเพิ่มไปยังสไลด์ที่สร้างขึ้น |

### ค่าที่ส่งกลับ

สไลด์ที่เพิ่ม

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งที่จะใส่ |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | อ็อบเจ็กต์ Stream ที่จะใช้เป็นแหล่งข้อมูลของไฟล์ HTML |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | อ็อบเจ็กต์ callback ที่ใช้ในการดึงอ็อบเจ็กต์ภายนอก หากพารามิเตอร์นี้เป็นค่า null จะละเว้นอ็อบเจ็กต์ภายนอกทั้งหมด |
| uri | [System::String](../../../system/string/) | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ไขลิงก์ที่เป็นแบบสัมพันธ์ |
| useSlideWithIndexAsStart | **bool** | แฟล็กนี้กำหนดวิธีเริ่มการแทรก: จากสไลด์ใหม่หรือจากสไลด์ที่มีดัชนีที่ระบุ หาก **true** การแทรกข้อมูลจะเริ่มจากพื้นที่ว่างบนสไลด์ที่มีดัชนีนั้น หาก **false** ข้อมูลจะถูกเพิ่มไปยังสไลด์ที่สร้างขึ้น |

### ค่าที่ส่งกลับ

สไลด์ที่เพิ่ม

## See Also

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