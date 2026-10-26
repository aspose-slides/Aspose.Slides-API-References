---
title: idx_get()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ดึงกฎที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว IFontFallBackRule.
type: docs
weight: 1
url: /th/aspose.slides/ifontfallbackrulescollection/idx_get/
---
## IFontFallBackRulesCollection::idx_get(int32_t) เมธอด


ดึงกฎที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
virtual System::SharedPtr<IFontFallBackRule> Aspose::Slides::IFontFallBackRulesCollection::idx_get(int32_t index)=0
```

## หมายเหตุ



```cpp
auto pres = MakeObject<Presentation>();
//ดึงคอลเลกชันของกฎที่ว่างเปล่าหรือกำหนดล่วงหน้าจาก FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//เพิ่มกฎหลายรายการเข้าในคอลเล็กชัน
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//ดึงอ็อบเจกต์ของกฎแรกในคอลเล็กชัน
auto firstRule = rulesList->idx_get(0);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IFontFallBackRule](../../ifontfallbackrule/)
* คลาส [IFontFallBackRulesCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)