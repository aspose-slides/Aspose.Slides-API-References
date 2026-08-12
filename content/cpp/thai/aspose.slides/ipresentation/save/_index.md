---
title: Save()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นไฟล์ในรูปแบบที่ระบุ.
type: docs
weight: 404
url: /th/aspose.slides/ipresentation/save/
---
## IPresentation::Save(System::String, Export::SaveFormat) method

บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นไฟล์ในรูปแบบที่ระบุ

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | เส้นทางไปยังไฟล์ที่สร้าง |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | รูปแบบของข้อมูลที่ส่งออก |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) method

บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุ

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมผลลัพธ์ |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | รูปแบบของข้อมูลที่ส่งออก |

## IPresentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method

บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นไฟล์ในรูปแบบที่ระบุและด้วยตัวเลือกเพิ่มเติม

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | เส้นทางไปยังไฟล์ที่สร้าง |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | รูปแบบของข้อมูลที่ส่งออก |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | ตัวเลือกรูปแบบเพิ่มเติม |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method

บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุและด้วยตัวเลือกเพิ่มเติม

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมผลลัพธ์ |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | รูปแบบของข้อมูลที่ส่งออก |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | ตัวเลือกรูปแบบเพิ่มเติม |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat) method

บันทึกสไลด์ที่ระบุของการนำเสนอเป็นไฟล์ในรูปแบบที่ระบุ

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | เส้นทางไปยังไฟล์ที่สร้าง |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | อาร์เรย์ที่มีตำแหน่งของสไลด์ เริ่มจาก 1 |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | รูปแบบของข้อมูลที่ส่งออก |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method

บันทึกสไลด์ที่ระบุของการนำเสนอเป็นไฟล์ในรูปแบบที่ระบุ

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | เส้นทางไปยังไฟล์ที่สร้าง |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | อาร์เรย์ที่มีตำแหน่งของสไลด์ เริ่มจาก 1 |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | รูปแบบของข้อมูลที่ส่งออก |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | ตัวเลือกรูปแบบเพิ่มเติม |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat) method

บันทึกสไลด์ที่ระบุของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุ

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมผลลัพธ์ |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | อาร์เรย์ที่มีตำแหน่งของสไลด์ เริ่มจาก 1 |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | รูปแบบของข้อมูลที่ส่งออก |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method

บันทึกสไลด์ที่ระบุของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุ

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมผลลัพธ์ |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | อาร์เรย์ที่มีตำแหน่งของสไลด์ เริ่มจาก 1 |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | รูปแบบของข้อมูลที่ส่งออก |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | ตัวเลือกรูปแบบเพิ่มเติม |

## IPresentation::Save(System::SharedPtr\<Export::Xaml::IXamlOptions\>) method

บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นชุดไฟล์ที่เป็นมาร์กอัป XAML

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<Export::Xaml::IXamlOptions> options)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\> | ตัวเลือกรูปแบบ XAML |

## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```

## ดูเพิ่มเติม

* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [String](../../../system/string/)
* คลาส [IPresentation](../)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* คลาส [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)