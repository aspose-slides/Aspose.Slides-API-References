---
title: remove method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/commentcollection/remove/
weight: 70
---
## remove(self, comment) {#icomment}
ลบการปรากฏครั้งแรกของ comment ที่ระบุใน collection.

```python
def remove(self, comment):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| comment | [`IComment`](/slides/python-net/th/aspose.slides/icomment) | comment ที่จะลบออกจาก collection. |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | หาก comment เป็น `None` |
| [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception) | เกิดขึ้นหาก comment ถูกลบไปแล้ว. |

### ดูเพิ่มเติม
* คลาส [`CommentCollection`](/slides/python-net/th/aspose.slides/commentcollection)
* คลาส [`IComment`](/slides/python-net/th/aspose.slides/icomment)
* คลาส [`PptxEditException`](/slides/python-net/th/aspose.slides/pptxeditexception)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)