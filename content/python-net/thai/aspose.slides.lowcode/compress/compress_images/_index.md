---
title: compress_images method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API
description: 
type: docs
url: /th/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
ลดความละเอียดของรูปภาพในงานนำเสนอและลบพื้นที่ที่ถูกตัดออก,
            คล้ายกับ “Compress Pictures” ของ PowerPoint ที่ใช้กับรูปภาพทั้งหมด.
            รูปภาพบนสไลด์, สไลด์เค้าโครงและสไลด์มาสเตอร์จะถูกประมวลผล รวมถึงรูปภาพภายในกลุ่มรูปร่าง
            และการเติมรูปภาพของรูปร่าง.

```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation) | งานนำเสนอที่จะประมวลผล. |
| resolution | [`PicturesCompression`](/slides/python-net/th/aspose.slides.export/picturescompression) | ความละเอียดเป้าหมายที่สัมพันธ์กับขนาดที่แต่ละรูปภาพถูกแสดง.<br/><br/>            [`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/th/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) ทำให้รูปภาพคงเดิม. |

### หมายเหตุ

รูปภาพที่มีความละเอียดเท่ากับหรือต่ำกว่าเป้าหมายจะไม่ถูกเปลี่ยนแปลง; รูปภาพจะไม่มีการขยายขึ้น.

ไม่ประมวลผล: พื้นหลังสไลด์, การเติมเซลล์ตาราง, แผนภูมิ, SmartArt, รูปภาพ GIF (เพื่อรักษาการเคลื่อนไหว),
            รูปภาพ SVG และเมต้าไฟล์ (EMF/WMF).

พื้นที่ที่ถูกตัดออกจะถูกลบอย่างถาวรและไม่สามารถกู้คืนใน PowerPoint.

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` คือ `None`. |

### ดูเพิ่มเติม
* class [`Compress`](/slides/python-net/th/aspose.slides.lowcode/compress)
* class [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation)
* enumeration [`PicturesCompression`](/slides/python-net/th/aspose.slides.export/picturescompression)
* module [`aspose.slides.lowcode`](/slides/python-net/th/aspose.slides.lowcode)
* library [`Aspose.Slides`](/slides/python-net)