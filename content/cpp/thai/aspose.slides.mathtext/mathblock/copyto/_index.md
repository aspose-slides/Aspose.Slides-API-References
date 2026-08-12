---
title: CopyTo()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คัดลอกไปยังอาร์เรย์ที่ระบุ.
type: docs
weight: 118
url: /th/aspose.slides.mathtext/mathblock/copyto/
---
## MathBlock::CopyTo(System::ArrayPtr\<System::SharedPtr\<IMathElement\>\>, int32_t) เมธอด

คัดลอกไปยังอาร์เรย์ที่ระบุ.

```cpp
void Aspose::Slides::MathText::MathBlock::CopyTo(System::ArrayPtr<System::SharedPtr<IMathElement>> array, int32_t arrayIndex) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\> | อาร์เรย์ที่จะคัดลอกไป |
| arrayIndex | **int32_t** | ดัชนีที่เริ่มคัดลอก |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
auto destinationArray = System::MakeArray<System::SharedPtr<IMathElement>>(mathBlock->get_Count());
mathBlock->CopyTo(destinationArray, 0);
```

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathBlock](../)
* เนมส페ซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)