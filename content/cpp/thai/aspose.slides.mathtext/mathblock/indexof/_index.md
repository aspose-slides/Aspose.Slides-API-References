---
title: IndexOf()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: กำหนดดัชนีขององค์ประกอบคณิตศาสตร์เฉพาะในคอลเลกชัน.
type: docs
weight: 144
url: /th/aspose.slides.mathtext/mathblock/indexof/
---
## MathBlock::IndexOf(System::SharedPtr\<IMathElement\>) เมธอด


กำหนดดัชนีขององค์ประกอบคณิตศาสตร์เฉพาะในคอลเลกชัน.

```cpp
int32_t Aspose::Slides::MathText::MathBlock::IndexOf(System::SharedPtr<IMathElement> item) override
```


### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | องค์ประกอบที่ต้องการค้นหาในคอลเลกชัน. |

### Return Value

ดัชนีของ *item* หากพบในคอลเลกชัน; หากไม่พบจะเป็น -1.
## Remarks



ตัวอย่าง: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
int32_t index = mathBlock->IndexOf(plusElement);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathBlock](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)