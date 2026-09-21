---
title: reorder method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API อ้างอิง
description: 
type: docs
url: /th/aspose.slides/ishapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
ย้ายรูปทรงที่ระบุไปยังตำแหน่งใหม่ภายในคอลเลกชันของรูปทรง.

```python
def reorder(self, index, shape):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีเป้าหมายที่เริ่มจากศูนย์ซึ่งรูปทรงจะถูกวาง. |
| shape | [`IShape`](/slides/python-net/th/aspose.slides/ishape) | [`IShape`](/slides/python-net/th/aspose.slides/ishape) ที่จะย้ายภายในคอลเลกชัน. |

## reorder(self, index, shapes) {#int-listishape}
ย้ายรูปทรงที่ระบุหลายรูปภายในคอลเลกชันของรูปทรง โดยวางเริ่มจากดัชนีที่กำหนด.

```python
def reorder(self, index, shapes):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีเป้าหมายที่เริ่มจากศูนย์ซึ่งรูปทรงแรกที่ระบุจะถูกวาง; <br/><br/>            รูปทรงต่อมาจะตามลำดับตามที่ให้ไว้. |
| shapes | **List[IShape]** | หนึ่งหรือหลายอินสแตนซ์ของ [`IShape`](/slides/python-net/th/aspose.slides/ishape) เพื่อย้ายภายในคอลเลกชัน. |

### ดูเพิ่มเติม
* คลาส [`IShape`](/slides/python-net/th/aspose.slides/ishape)
* คลาส [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)