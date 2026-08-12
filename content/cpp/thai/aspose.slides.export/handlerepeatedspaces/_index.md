---
title: HandleRepeatedSpaces
second_title: Aspose.Slides สำหรับเอกสารอ้างอิง API ของ C++
description: ระบุวิธีการจัดการกับอักขระช่องว่างปกติที่ซ้ำกันระหว่างการส่งออกเป็น Markdown.
type: docs
weight: 937
url: /th/aspose.slides.export/handlerepeatedspaces/
---
## HandleRepeatedSpaces enum

กำหนดวิธีการจัดการกับอักขระช่องว่างปกติที่ซ้ำกันระหว่างการส่งออก Markdown.

```cpp
enum class HandleRepeatedSpaces
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| None | 0 | ช่องว่างทั้งหมดจะถูกเก็บไว้เป็นอักขระช่องว่างปกติโดยไม่มีการเปลี่ยนแปลงใด ๆ ไม่ได้ทำการแปลงใด ๆ และช่องว่างต่อเนื่องหลายช่องจะถูกส่งออกตามเดิม |
| AlternateSpacesToNbsp | 1 | แปลงลำดับของช่องว่างปกติสองช่องหรือมากกว่าโดยสลับระหว่างอักขระช่องว่างปกติและเอนทิตี non-breaking space (**&nbsp;**). ช่องว่างแรกจะถูกเก็บไว้เป็นช่องว่างปกติเสมอ |
| MultipleSpacesToNbsp | 2 | แปลงลำดับของช่องว่างปกติสองช่องหรือมากกว่าโดยเก็บช่องว่างแรกเป็นอักขระช่องว่างปกติและแทนที่ช่องว่างที่เหลือทั้งหมดด้วยเอนทิตี non-breaking space (**&nbsp;**). |

## ดูเพิ่มเติม

* เนมสเปซ [Aspose::Slides::Export](../)
* ไลบรารี [Aspose.Slides](../../)