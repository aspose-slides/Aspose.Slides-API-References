---
title: remove_node method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.smartart/smartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
ลบโหนดหรือโหนดย่อยโดยใช้ดัชนี

```python
def remove_node(self, index):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | ดัชนีที่เริ่มจากศูนย์ของโหนด |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | ดัชนีมีค่าน้อยกว่า 0.  -or- ดัชนีเท่ากับหรือมากกว่าจำนวนพี่น้อง |

## remove_node(self, node) {#ismartartnode}
ลบโหนดหรือโหนดย่อย

```python
def remove_node(self, node):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| node | [`ISmartArtNode`](/slides/python-net/th/aspose.slides.smartart/ismartartnode) | โหนดที่ต้องการลบ |

### See Also
* คลาส [`ISmartArtNode`](/slides/python-net/th/aspose.slides.smartart/ismartartnode)
* คลาส [`SmartArtNodeCollection`](/slides/python-net/th/aspose.slides.smartart/smartartnodecollection)
* โมดูล [`aspose.slides.smartart`](/slides/python-net/th/aspose.slides.smartart)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)