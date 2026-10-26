---
title: align_shapes method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
เปลี่ยนตำแหน่งของรูปทรงทั้งหมดบนสไลด์. จัดตำแหน่งรูปทรงให้ตรงกับขอบหรือขอบของสไลด์
            หรือจัดตำแหน่งสัมพันธ์กับกันและกัน.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/th/aspose.slides/shapesalignmenttype) | กำหนดประเภทของการจัดตำแหน่งที่จะนำไปใช้. |
| align_to_slide | **bool** | ถ้าเป็นจริง รูปทรงจะถูกจัดตำแหน่งสัมพันธ์กับขอบของสไลด์. |
| slide | [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide) | สไลด์แม่. |

## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
เปลี่ยนตำแหน่งของรูปทรงทั้งหมดภายในกลุ่มรูปทรง. จัดตำแหน่งรูปทรงให้ตรงกับขอบหรือขอบของสไลด์
            หรือจัดตำแหน่งสัมพันธ์กับกันและกัน.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/th/aspose.slides/shapesalignmenttype) | กำหนดประเภทของการจัดตำแหน่งที่จะนำไปใช้. |
| align_to_slide | **bool** | ถ้าเป็นจริง รูปทรงจะถูกจัดตำแหน่งสัมพันธ์กับขอบของสไลด์. |
| group_shape | [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape) | กลุ่มรูปทรงแม่. |

## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
เปลี่ยนตำแหน่งของรูปทรงที่เลือกบนสไลด์. จัดตำแหน่งรูปทรงให้ตรงกับขอบหรือขอบของสไลด์
             หรือจัดตำแหน่งสัมพันธ์กับกันและกัน.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/th/aspose.slides/shapesalignmenttype) | กำหนดประเภทของการจัดตำแหน่งที่จะนำไปใช้. |
| align_to_slide | **bool** | ถ้าเป็นจริง รูปทรงจะถูกจัดตำแหน่งสัมพันธ์กับขอบของสไลด์. |
| slide | [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide) | สไลด์แม่. |
| shape_indexes | **List[int]** | ดัชนีของรูปทรงที่จะจัดตำแหน่ง. |

## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
เปลี่ยนตำแหน่งของรูปทรงที่เลือกภายในกลุ่มรูปทรง. จัดตำแหน่งรูปทรงให้ตรงกับขอบหรือขอบของสไลด์
            หรือจัดตำแหน่งสัมพันธ์กับกันและกัน.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/th/aspose.slides/shapesalignmenttype) | กำหนดประเภทของการจัดตำแหน่งที่จะนำไปใช้. |
| align_to_slide | **bool** | ถ้าเป็นจริง รูปทรงจะถูกจัดตำแหน่งสัมพันธ์กับขอบของสไลด์. |
| group_shape | [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape) | กลุ่มรูปทรงแม่. |
| shape_indexes | **List[int]** | ดัชนีของรูปทรงที่จะจัดตำแหน่ง. |

### ดูเพิ่มเติม
* คลาส [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide)
* คลาส [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape)
* enumeration [`ShapesAlignmentType`](/slides/python-net/th/aspose.slides/shapesalignmenttype)
* คลาส [`SlideUtil`](/slides/python-net/th/aspose.slides.util/slideutil)
* โมดูล [`aspose.slides.util`](/slides/python-net/th/aspose.slides.util)
* library [`Aspose.Slides`](/slides/python-net)