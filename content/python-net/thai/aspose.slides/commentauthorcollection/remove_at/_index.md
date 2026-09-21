---
title: remove_at method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/commentauthorcollection/remove_at/
weight: 60
---
## remove_at(self, index) {#int}
ลบผู้เขียนที่ตำแหน่งดัชนีที่ระบุในคอลเลกชัน.

```python
def remove_at(self, index):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | ดัชนีที่เริ่มจากศูนย์ขององค์ประกอบที่ต้องการลบ |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | ดัชนีน้อยกว่า 0 หรือดัชนีเท่ากับหรือมากกว่ากับ Count |
| [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception) | โยนข้อยกเว้นหาก author ถูกลบแล้ว |

### See Also
* คลาส [`CommentAuthorCollection`](/slides/python-net/th/aspose.slides/commentauthorcollection)
* คลาส [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)