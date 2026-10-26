---
title: MathBar()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เริ่มต้น MathBar ด้วยเส้นเหนือ (ตำแหน่งบน)
type: docs
weight: 40
url: /th/aspose.slides.mathtext/mathbar/mathbar/
---
## MathBar::MathBar(System::SharedPtr\<IMathElement\>) ตัวสร้าง

เริ่มต้น [MathBar](../) ด้วยเส้นเหนือ (ตำแหน่งบน)

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | องค์ประกอบฐานที่บาร์ถูกนำไปใช้ |
## หมายเหตุ

ตัวอย่าง: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBar::MathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) ตัวสร้าง

เริ่มต้น [MathBar](../) ด้วยตำแหน่งที่ระบุ

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | องค์ประกอบฐานที่บาร์ถูกนำไปใช้ |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | ตำแหน่งของเส้นบาร์ |
## หมายเหตุ

ตัวอย่าง: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"), MathTopBotPositions::Bottom);
```

## ดูเพิ่มเติม

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathBar](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)