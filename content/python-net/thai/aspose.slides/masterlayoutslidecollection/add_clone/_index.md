---
title: add_clone method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/masterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
เพิ่มสำเนาของสไลด์เค้าโครงที่ระบุไปยังส่วนท้ายของคอลเลกชัน

### Returns

สไลด์ที่เพิ่ม

```python
def add_clone(self, source_layout):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide) | สไลด์ที่จะทำสำเนา |

### Remarks

1) New layout will be linked with parent master slide for this layout slides collection. So this is analogue of copy/paste with "Use Destination Theme" option in PowerPoint.  
2) Analogue of this method is method **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** accessed with [`IPresentation.layout_slides`](/slides/python-net/th/aspose.slides/ipresentation/layout_slides) property.

### See Also
* คลาส [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide)
* คลาส [`MasterLayoutSlideCollection`](/slides/python-net/th/aspose.slides/masterlayoutslidecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)