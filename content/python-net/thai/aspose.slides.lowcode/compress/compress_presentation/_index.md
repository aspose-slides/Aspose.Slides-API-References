---
title: compress_presentation method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
ลดขนาดของงานนำเสนอโดยดำเนินการขั้นตอนการบีบอัดที่มีทั้งหมด:

* ลบสไลด์มาสเตอร์ที่ไม่ใช้งาน **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* ลบสไลด์เลย์เอาต์ที่ไม่ใช้งาน **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* เก็บเฉพาะ glyphs ที่ใช้งานจริงในฟอนท์ที่ฝังไว้ **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* ลดความละเอียดของรูปภาพเป็น 150 DPI และลบส่วนที่ถูกตัดของรูปภาพ **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.

```python
@staticmethod
def compress_presentation(presentation):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/th/aspose.slides/presentation) | งานนำเสนอที่จะบีบอัด. |

### หมายเหตุ
หากต้องการปรับแต่งการบีบอัด ตัวอย่างเช่นใช้ความละเอียดของรูปภาพที่แตกต่างหรือข้ามขั้นตอนบางอย่าง ให้เรียกใช้เมธอดที่ระบุด้านบนแยกแต่ละตัวแทนการเรียกเมธอดนี้ ส่วนที่ถูกตัดของรูปภาพจะถูกลบอย่างถาวรและไม่สามารถกู้คืนใน PowerPoint ได้.

### ข้อยกเว้น
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` คือ `None`. |

### ดูเพิ่มเติม
* คลาส [`Compress`](/slides/python-net/th/aspose.slides.lowcode/compress)
* คลาส [`Presentation`](/slides/python-net/th/aspose.slides/presentation)
* โมดูล [`aspose.slides.lowcode`](/slides/python-net/th/aspose.slides.lowcode)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)