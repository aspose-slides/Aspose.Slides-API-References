---
title: CompressionLevel enumeration
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.export/compressionlevel/
---
## CompressionLevel การระบุค่า

ระบุระดับการบีบอัด ZIP สำหรับไฟล์ OpenXML  
ระดับที่สูงกว่าจะให้การบีบอัดที่ดีกว่าตามด้วยการประมวลผลที่ช้าลง

The CompressionLevel type exposes the following members:

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| :- | :- |
| NONE | ไม่มีการบีบอัดใด ๆ ถูกนำมาใช้ ไฟล์จะถูกเก็บอยู่ตามเดิม |
| LEVEL1 | การบีบอัดที่เร็วที่สุดพร้อมอัตราการบีบอัดที่ต่ำที่สุด |
| LEVEL2 | การบีบอัดที่เร็วขึ้นพร้อมอัตราการบีบอัดที่ดีขึ้นเล็กน้อยเมื่อเทียบกับ [`CompressionLevel.LEVEL1`](/slides/python-net/th/aspose.slides.export/compressionlevel/LEVEL1) |
| LEVEL3 | ให้การบีบอัดที่ดีกว่า [`CompressionLevel.LEVEL2`](/slides/python-net/th/aspose.slides.export/compressionlevel/LEVEL2) พร้อมผลกระทบต่อประสิทธิภาพปานกลาง |
| LEVEL4 | ให้การบีบอัดที่ดีกว่า [`CompressionLevel.LEVEL3`](/slides/python-net/th/aspose.slides.export/compressionlevel/LEVEL3) |
| LEVEL5 | ให้การบีบอัดที่พัฒนาขึ้นเหนือ [`CompressionLevel.LEVEL4`](/slides/python-net/th/aspose.slides.export/compressionlevel/LEVEL4) พร้อมเวลาประมวลผลเพิ่มขึ้น |
| LEVEL6 | การบีบอัดมาตรฐาน ให้ความสมดุลที่ดีระหว่างความเร็วการบีบอัดและขนาดไฟล์<br/>ระดับการบีบอัดเริ่มต้น |
| LEVEL7 | ให้การบีบอัดที่สูงกว่า [`CompressionLevel.LEVEL6`](/slides/python-net/th/aspose.slides.export/compressionlevel/LEVEL6) พร้อมการประมวลผลที่ช้าลง |
| LEVEL8 | ให้การบีบอัดที่สูงกว่า [`CompressionLevel.LEVEL7`](/slides/python-net/th/aspose.slides.export/compressionlevel/LEVEL7) |
| LEVEL9 | การบีบอัดสูงสุด สร้างขนาดไฟล์ที่เล็กที่สุดด้วยความเร็วการประมวลผลที่ช้าที่สุด |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)