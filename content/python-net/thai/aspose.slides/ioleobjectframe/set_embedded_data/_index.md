---
title: set_embedded_data method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/ioleobjectframe/set_embedded_data/
weight: 50
---
## set_embedded_data(self, embedded_data) {#ioleembeddeddatainfo}
กำหนดข้อมูลเกี่ยวกับข้อมูลที่ฝังใน OLE.

```python
def set_embedded_data(self, embedded_data):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo) | ข้อมูลฝัง [`IOleEmbeddedDataInfo`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo) |

### หมายเหตุ

เมธอดนี้เปลี่ยนแปลงคุณสมบัติของอ็อบเจ็กต์เพื่อสะท้อนข้อมูลใหม่และตั้งค่าแฟล็ก IsObjectLink เป็น false ซึ่งบ่งบอกว่าอ็อบเจ็กต์ OLE ถูกฝังไว้

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | เมื่อพารามิเตอร์ embeddedData เป็น None. |

### ดูเพิ่มเติม
* คลาส [`IOleEmbeddedDataInfo`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo)
* คลาส [`IOleObjectFrame`](/slides/python-net/th/aspose.slides/ioleobjectframe)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)