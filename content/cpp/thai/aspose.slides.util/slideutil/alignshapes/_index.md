---
title: AlignShapes()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: เปลี่ยนตำแหน่งของรูปทั้งหมดบนสไลด์. จัดรูปให้สอดคล้องกับขอบหรือขอบของสไลด์ หรือจัดเรียงรูปสัมพันธ์กัน.
type: docs
weight: 27
url: /th/aspose.slides.util/slideutil/alignshapes/
---
## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>) เมธอด

เปลี่ยนตำแหน่งของรูปทั้งหมดบนสไลด์ จัดรูปให้สอดคล้องกับขอบหรือขอบของสไลด์ หรือจัดเรียงรูปสัมพันธ์กัน

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | กำหนดว่าประเภทการจัดแนวใดจะถูกนำไปใช้ |
| alignToSlide | **bool** | หากเป็น true รูปจะถูกจัดแนวสัมพันธ์กับขอบของสไลด์ |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | สไลด์แม่ |

## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, true, pres->get_Slides()->idx_get(0));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>, System::ArrayPtr\<int32_t\>) เมธอด

เปลี่ยนตำแหน่งของรูปที่เลือกบนสไลด์ จัดรูปให้สอดคล้องกับขอบหรือขอบของสไลด์ หรือจัดเรียงรูปสัมพันธ์กัน

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide, System::ArrayPtr<int32_t> shapeIndexes)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | กำหนดว่าประเภทการจัดแนวใดจะถูกนำไปใช้ |
| alignToSlide | **bool** | หากเป็น true รูปจะถูกจัดแนวสัมพันธ์กับขอบของสไลด์ |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | สไลด์แม่ |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | ดัชนีของรูปที่จะจัดแนว |

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto slide = pres->get_Slides()->idx_get(0);
auto shape1 = slide->get_Shapes()->idx_get(0);
auto shape2 = slide->get_Shapes()->idx_get(1);
SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, false, pres->get_Slides()->idx_get(0),
    System::MakeArray<int32_t>({
        slide->get_Shapes()->IndexOf(shape1),
        slide->get_Shapes()->IndexOf(shape2)
    }));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>) เมธอด

เปลี่ยนตำแหน่งของรูปทั้งหมดภายในกลุ่มรูป จัดรูปให้สอดคล้องกับขอบหรือขอบของสไลด์ หรือจัดเรียงรูปสัมพันธ์กัน

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | กำหนดว่าประเภทการจัดแนวใดจะถูกนำไปใช้ |
| alignToSlide | **bool** | หากเป็น true รูปจะถูกจัดแนวสัมพันธ์กับขอบของสไลด์ |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | กลุ่มรูปแม่ |

## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>, System::ArrayPtr\<int32_t\>) เมธอด

เปลี่ยนตำแหน่งของรูปที่เลือกภายในกลุ่มรูป จัดรูปให้สอดคล้องกับขอบหรือขอบของสไลด์ หรือจัดเรียงรูปสัมพันธ์กัน

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape, System::ArrayPtr<int32_t> shapeIndexes)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | กำหนดว่าประเภทการจัดแนวใดจะถูกนำไปใช้ |
| alignToSlide | **bool** | หากเป็น true รูปจะถูกจัดแนวสัมพันธ์กับขอบของสไลด์ |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | กลุ่มรูปแม่ |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | ดัชนีของรูปที่จะจัดแนว |

## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)), System::MakeArray<int32_t>({0, 2}));
```

## ดูเพิ่มเติม

* Enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [IBaseSlide](../../../aspose.slides/ibaseslide/)
* คลาส [SlideUtil](../)
* คลาส [IGroupShape](../../../aspose.slides/igroupshape/)
* เนมสเปซ [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)