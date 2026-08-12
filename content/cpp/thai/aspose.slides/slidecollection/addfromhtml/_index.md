---
title: AddFromHtml()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างสไลด์จากข้อความ HTML และเพิ่มลงในส่วนท้ายของคอลเลกชัน
type: docs
weight: 196
url: /th/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

สร้างสไลด์จากข้อความ HTML และเพิ่มลงในส่วนท้ายของคอลเลกชัน

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML ที่จะเพิ่ม |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | อ็อบเจ็กต์ callback ที่ใช้ดึงวัตถุภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น |
| uri | [System::String](../../../system/string/) | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ลิงก์สัมพัทธ์ |

### Return Value

สไลด์ที่เพิ่ม

## SlideCollection::AddFromHtml(System::String) method

สร้างสไลด์จากข้อความ HTML และเพิ่มลงในส่วนท้ายของคอลเลกชัน

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML ที่จะเพิ่ม |

### Return Value

สไลด์ที่เพิ่ม

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

สร้างสไลด์จากข้อความ HTML และเพิ่มลงในส่วนท้ายของคอลเลกชัน

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | อ็อบเจ็กต์ TextReader ที่จะใช้เป็นแหล่งของไฟล์ HTML |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | อ็อบเจ็กต์ callback ที่ใช้ดึงวัตถุภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น |
| uri | [System::String](../../../system/string/) | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ลิงก์สัมพัทธ์ |

### Return Value

สไลด์ที่เพิ่ม

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) method

สร้างสไลด์จากข้อความ HTMLและเพิ่มลงในส่วนท้ายของคอลเลกชัน

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | อ็อบเจ็กต์ TextReader ที่จะใช้เป็นแหล่งของไฟล์ HTML |

### Return Value

สไลด์ที่เพิ่ม

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

สร้างสไลด์จากข้อความ HTMLและเพิ่มลงในส่วนท้ายของคอลเลกชัน

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | อ็อบเจ็กต์ Stream ที่จะใช้เป็นแหล่งของไฟล์ HTML |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | อ็อบเจ็กต์ callback ที่ใช้ดึงวัตถุภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น |
| uri | [System::String](../../../system/string/) | URI ของ HTML ที่ระบุ ใช้เพื่อแก้ลิงก์สัมพัทธ์ |

### Return Value

สไลด์ที่เพิ่ม

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) method

สร้างสไลด์จากข้อความ HTMLและเพิ่มลงในส่วนท้ายของคอลเลกชัน

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | อ็อบเจ็กต์ Stream ที่จะใช้เป็นแหล่งของไฟล์ HTML |

### Return Value

สไลด์ที่เพิ่ม

## Remarks

```cpp
// สร้างอินสแตนซ์ของคลาส Presentation.
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // เรียกใช้เมธอด AddFromHtml และส่งไฟล์ HTML.
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// ใช้เมธอด Save เพื่อบันทึกไฟล์เป็นเอกสาร PowerPoint.
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

## See Also

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