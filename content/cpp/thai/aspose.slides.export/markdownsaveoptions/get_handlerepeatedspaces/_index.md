---
title: get_HandleRepeatedSpaces()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ระบุว่าควรจัดการกับอักขระช่องว่างปกติที่ซ้ำกันอย่างไรระหว่างการส่งออกเป็น Markdown.
type: docs
weight: 235
url: /th/aspose.slides.export/markdownsaveoptions/get_handlerepeatedspaces/
---
## MarkdownSaveOptions::get_HandleRepeatedSpaces() const เมธอด


ระบุว่าควรจัดการกับอักขระช่องว่างปกติที่ซ้ำกันอย่างไรระหว่างการส่งออกเป็น Markdown.

```cpp
Aspose::Slides::Export::HandleRepeatedSpaces Aspose::Slides::Export::MarkdownSaveOptions::get_HandleRepeatedSpaces() const
```

## หมายเหตุ


สมบัตินี้กำหนดว่าช่องว่างต่อเนื่องจะเป็น:
* เก็บไว้เป็นอักขระช่องว่างปกติ,
* สลับระหว่างช่องว่างปกติและเอนทิตี้ non-breaking space (**&nbsp;**),
* หรือแทนที่ทั้งหมด (หลังจากตัวแรก) ด้วย **&nbsp;** เพื่อรักษาการจัดแนวภาพในผลลัพธ์ Markdown.



ค่าปริยายคือ [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## ดูเพิ่มเติม

* Enum [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* คลาส [MarkdownSaveOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)