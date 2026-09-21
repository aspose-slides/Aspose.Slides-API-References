---
title: remove_node method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.smartart/ismartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
ลบโหนดหรือโหนดย่อยตามดัชนี

```python
def remove_node(self, index):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีเริ่มจากศูนย์ของโหนด |

### Exceptions

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | index น้อยกว่า 0.  -or- index เท่ากับหรือมากกว่าจำนวนพี่น้อง |

## remove_node(self, node_obj) {#ismartartnode}
ลบโหนดหรือโหนดย่อย

```python
def remove_node(self, node_obj):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| node_obj | [`ISmartArtNode`](/slides/python-net/th/aspose.slides.smartart/ismartartnode) | โหนดที่จะลบ. |

### See Also
* คลาส [`ISmartArtNode`](/slides/python-net/th/aspose.slides.smartart/ismartartnode)
* คลาส [`ISmartArtNodeCollection`](/slides/python-net/th/aspose.slides.smartart/ismartartnodecollection)
* โมดูล [`aspose.slides.smartart`](/slides/python-net/th/aspose.slides.smartart)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)