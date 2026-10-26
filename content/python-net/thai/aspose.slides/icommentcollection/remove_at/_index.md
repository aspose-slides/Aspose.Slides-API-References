---
title: remove_at method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/icommentcollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน

```python
def remove_at(self, index):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | ดัชนีที่เป็นศูนย์ฐานขององค์ประกอบที่ต้องการลบ |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Index is less than 0 or index is equal or greater than Count |
| [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception) | Thrown if comment is already removed. |

### See Also
* class [`ICommentCollection`](/slides/python-net/th/aspose.slides/icommentcollection)
* class [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)