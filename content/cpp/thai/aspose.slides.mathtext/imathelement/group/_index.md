---
title: Group()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาล่าง
type: docs
weight: 248
url: /th/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() เมธอด

วางองค์ประกอบนี้ในกลุ่มโดยใช้วงเล็บปีกกาล่าง

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```

### ค่าที่ส่งคืน

อินสแตนซ์ใหม่ของประเภท [IMathGroupingCharacter](../../imathgroupingcharacter/)
## หมายเหตุ



```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) เมธอด

วางองค์ประกอบนี้ในกลุ่มโดยใช้ตัวอักษรกลุ่มเช่นวงเล็บปีกกาล่างหรืออักขระอื่น

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| character | char16_t | อักขระการจัดกลุ่มเช่น BOTTOM CURLY BRACKET (U+23DF) หรืออื่นใด |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | ตำแหน่งของอักขระการจัดกลุ่ม |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | การจัดตำแหน่งแนวตั้งของอักขระกลุ่ม. ระบุการจัดแนวของอ็อบเจ็กต์สัมพันธ์กับ baseline. ตัวอย่างเช่น เมื่ออักขระกลุ่มอยู่ด้านบนของอ็อบเจ็กต์, VerticalJustification ของ Top แสดงว่าด้านบนของอ็อบเจ็กต์อยู่บน baseline; เมื่อ VerticalJustification ถูกตั้งค่าเป็น Bottom, ด้านล่างของอ็อบเจ็กต์อยู่บน baseline |

### ค่าที่ส่งคืน

อินสแตนซ์ใหม่ของประเภท [IMathGroupingCharacter](../../imathgroupingcharacter/)
## หมายเหตุ



```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## ดูเพิ่มเติม

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)