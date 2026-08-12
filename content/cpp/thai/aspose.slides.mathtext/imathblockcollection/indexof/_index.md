---
title: IndexOf()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: กำหนดดัชนีของ IMathBlock เฉพาะในคอลเลกชัน.
type: docs
weight: 79
url: /th/aspose.slides.mathtext/imathblockcollection/indexof/
---
## IMathBlockCollection::IndexOf(System::SharedPtr\<IMathBlock\>) เมธอด

กำหนดดัชนีของ [IMathBlock](../../imathblock/) เฉพาะในคอลเลกชัน.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::IndexOf(System::SharedPtr<IMathBlock> item)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | รายการที่ต้องการค้นหาในคอลเลกชัน |

### Return Value

ดัชนีของ *item* หากพบในคอลเลกชัน; หากไม่พบจะคืนค่า -1.
## หมายเหตุ

ตัวอย่าง: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
int32_t index = blockCollection->IndexOf(block);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathBlock](../../imathblock/)
* คลาส [IMathBlockCollection](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)