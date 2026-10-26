---
title: AddImage()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: เพิ่มรูปภาพลงในงานนำเสนอ.
type: docs
weight: 14
url: /th/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) method

เพิ่มรูปภาพลงในงานนำเสนอ.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | รูปภาพที่จะเพิ่ม. |

### Return Value

เพิ่มรูปภาพ.

## Remarks

เมธอดนี้แปลงไฟล์เมตาไฟล์ WMF/EMF เป็นภาพ PNG แบบแรสเตอร์ก่อนแทรกลงในงานนำเสนอ.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) method

เพิ่มรูปภาพจากสตรีมหน่วยความจำ.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | สตรีมหน่วยความจำ. |

### Return Value

เพิ่มรูปภาพ.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) method

เพิ่มรูปภาพลงในงานนำเสนอจากสตรีม.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมสำหรับเพิ่มรูปภาพ. |

### Return Value

เพิ่มรูปภาพ.

## Remarks

เมธอดนี้สามารถเพิ่มไฟล์เมตาไฟล์ WMF/EMF ลงในงานนำเสนอได้โดยไม่ต้องแปลงเป็นภาพ PNG แบบแรสเตอร์.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) method

สร้างและเพิ่มรูปภาพลงในงานนำเสนอจากสตรีม.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมสำหรับเพิ่มไฟล์รูปภาพ. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | พฤติกรรมที่จะนำไปใช้กับสตรีม. |

### Return Value

เพิ่ม [IPPImage](../../ippimage/).

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) method

เพิ่มรูปภาพลงในงานนำเสนอจากบัฟเฟอร์ที่ระบุ.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์. |

### Return Value

เพิ่มรูปภาพ.

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) method

เพิ่มสำเนาของรูปภาพจากงานนำเสนออื่น.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | รูปภาพต้นฉบับ. |

### Return Value

เพิ่มรูปภาพ.

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) method

เพิ่มรูปภาพลงในงานนำเสนอจากอ็อบเจ็กต์ SVG.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | อ็อบเจ็กต์ภาพ SVG [ISvgImage](../../isvgimage/) |

### Return Value

เพิ่มรูปภาพ.

## See Also

* ประเภท Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* การกำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* การกำหนดชนิด [ArrayPtr](../../../system/arrayptr/)
* คลาส [IPPImage](../../ippimage/)
* คลาส [IImage](../../iimage/)
* คลาส [IImageCollection](../)
* คลาส [MemoryStream](../../../system.io/memorystream/)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [ISvgImage](../../isvgimage/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)