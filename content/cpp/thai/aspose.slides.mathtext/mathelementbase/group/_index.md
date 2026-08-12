---
title: Group()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++ 
description: วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บโค้งล่าง
type: docs
weight: 235
url: /th/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() เมธอด

วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บโค้งล่าง

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```

### ค่าที่ส่งกลับ

อินสแตนส์ใหม่ของประเภท [IMathGroupingCharacter](../../imathgroupingcharacter/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) เมธอด


วางองค์ประกอบนี้ในกลุ่มโดยใช้ตัวอักขระการจัดกลุ่ม เช่น วงเล็บโค้งล่างหรืออื่นใด

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| character | char16_t | อักขระการจัดกลุ่ม เช่น BOTTOM CURLY BRACKET (U+23DF) หรืออื่นใด |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | ตำแหน่งของอักขระการจัดกลุ่ม |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | การจัดแนวแนวตั้งของอักขระกลุ่ม ระบุการจัดตำแหน่งของอ็อบเจ็กต์ตามเส้นฐาน ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่เหนืออ็อบเจ็กต์ การกำหนด VerticalJustification เป็น Top หมายถึงส่วนบนของอ็อบเจ็กต์อยู่บนเส้นฐาน; เมื่อกำหนด VerticalJustification เป็น Bottom ส่วนล่างของอ็อบเจ็กต์อยู่บนเส้นฐาน |

### ค่าที่ส่งกลับ

อินสแตนส์ใหม่ของประเภท [IMathGroupingCharacter](../../imathgroupingcharacter/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## ดูเพิ่มเติม

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)