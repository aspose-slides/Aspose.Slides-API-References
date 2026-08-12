---
title: SlideUtil
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ให้เมธอดที่ช่วยในการค้นหารูปและข้อความในงานนำเสนอ.
type: docs
weight: 14
url: /th/aspose.slides.util/slideutil/
---
## SlideUtil คลาส

ให้เมธอดที่ช่วยในการค้นหารูปและข้อความในงานนำเสนอ.

```cpp
class SlideUtil
```

## เมธอด

| Method | Description |
| --- | --- |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | เปลี่ยนตำแหน่งการจัดวางของรูปทั้งหมดบนสไลด์. จัดแนวรูปไปยังขอบหรือคำนำของสไลด์หรือจัดแนวสัมพันธ์กันระหว่างรูป. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | เปลี่ยนตำแหน่งการจัดวางของรูปทั้งหมดบนสไลด์. จัดแนวรูปไปยังขอบหรือคำนำของสไลด์หรือจัดแนวสัมพันธ์กันระหว่างรูป. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>) | เปลี่ยนตำแหน่งการจัดวางของรูปทั้งหมดภายในกลุ่มรูป. จัดแนวรูปไปยังขอบหรือคำนำของสไลด์หรือจัดแนวสัมพันธ์กันระหว่างรูป. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | เปลี่ยนตำแหน่งการจัดวางของรูปที่เลือกภายในกลุ่มรูป. จัดแนวรูปไปยังขอบหรือคำนำของสไลด์หรือจัดแนวสัมพันธ์กันระหว่างรูป. |
| static void [FindAndReplaceText](./findandreplacetext/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**, [System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[PortionFormat](../../aspose.slides/portionformat/)\>) | ค้นหาและแทนที่ข้อความในงานนำเสนอด้วยรูปแบบที่กำหนด |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, [System::String](../../system/string/)) | ค้นหารูปโดยข้อความแทนที่ในงานนำเสนอ PPTX. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/)) | ค้นหารูปโดยข้อความแทนที่บนสไลด์ในงานนำเสนอ PPTX. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>\> [FindShapesByPlaceholderType](./findshapesbyplaceholdertype/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [PlaceholderType](../../aspose.slides/placeholdertype/)) | ค้นหารูปทั้งหมดบนสไลด์ที่ระบุซึ่งตรงกับประเภทตัวแทนที่กำหนด. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextBoxes](./getalltextboxes/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | คืนค่าเฟรมข้อความทั้งหมดบนสไลด์ในงานนำเสนอ PPTX. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextFrames](./getalltextframes/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**) | คืนค่าเฟรมข้อความทั้งหมดในงานนำเสนอ PPTX. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetTextBoxesContainsText](./gettextboxescontainstext/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/), **bool**) | คืนค่าเฟรมข้อความทั้งหมดบนสไลด์ที่ระบุซึ่งมีข้อความที่กำหนด. |
|  [SlideUtil](./slideutil/)() |  |
| static [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) [ToSaveFormat](./tosaveformat/)([SourceFormat](../../aspose.slides/sourceformat/)) | แปลงรูปแบบไฟล์ต้นทางเป็น [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) ที่สอดคล้องกัน. |
## ดูเพิ่มเติม

* เนมสเปซ [Aspose::Slides::Util](../)
* ไลบรารี [Aspose.Slides](../../)