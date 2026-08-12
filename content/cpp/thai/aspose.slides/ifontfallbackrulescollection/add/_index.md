---
title: Add()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เพิ่มกฎ FallBack ใหม่ที่ส่วนท้ายของคอลเลกชัน.
type: docs
weight: 14
url: /th/aspose.slides/ifontfallbackrulescollection/add/
---
## IFontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) เมธอด

เพิ่มกฎ FallBack ใหม่ที่ส่วนท้ายของคอลเลกชัน.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | กฎที่ระบุสำหรับการเพิ่ม |

## หมายเหตุ

```cpp
auto pres = MakeObject<Presentation>();
// การดึงคอลเลกชันกฎที่ว่างเปล่าหรือกำหนดค่าไว้ล่วงหน้าจาก FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// การเพิ่มกฎใหม่ลงในคอลเลกชัน
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [IFontFallBackRule](../../ifontfallbackrule/)
* คลาส [IFontFallBackRulesCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)