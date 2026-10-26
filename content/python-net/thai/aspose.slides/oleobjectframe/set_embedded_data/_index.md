---
title: set_embedded_data method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/oleobjectframe/set_embedded_data/
weight: 60
---
## set_embedded_data(self, embedded_data) {#ioleembeddeddatainfo}
กำหนดข้อมูลเกี่ยวกับข้อมูลที่ฝังใน OLE.
            
            เมธอดนี้เปลี่ยนแปลงคุณสมบัติของอ็อบเจกต์เพื่อสะท้อนข้อมูลใหม่และตั้งค่าแฟล็ก IsObjectLink เป็น false เพื่อบ่งบอกว่าอ็อบเจกต์ OLE ถูกฝังไว้.


```python
def set_embedded_data(self, embedded_data):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo) | ข้อมูลฝัง [`IOleEmbeddedDataInfo`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo) |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | เมื่อพารามิเตอร์ embeddedData มีค่าเป็น None. |



### ดูเพิ่มเติม
* คลาส [`IOleEmbeddedDataInfo`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo)
* คลาส [`OleObjectFrame`](/slides/python-net/th/aspose.slides/oleobjectframe)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)