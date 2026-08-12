---
title: idx_get()
second_title: Aspose.Slides สำหรับ C++ API เอกสารอ้างอิง
description: รับกฎที่ตำแหน่งที่ระบุ อ่านได้เท่านั้น IFontFallBackRule.
type: docs
weight: 66
url: /th/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) เมธอด


รับกฎที่ตำแหน่งที่ระบุ อ่านได้เท่านั้น [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
```

## หมายเหตุ



```cpp
auto pres = MakeObject<Presentation>();
//การดึงคอลเลกชันของกฎที่ว่างหรือถูกกำหนดค่าล่วงหน้าจาก FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//การเพิ่มกฎหลายรายการลงในคอลเลกชัน
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//การเรียกคืนอ็อบเจกต์ของกฎแรกในคอลเลกชัน
auto firstRule = rulesList->idx_get(0);
```

## ดูเพิ่มเติม

* นิยามชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [IFontFallBackRule](../../ifontfallbackrule/)
* คลาส [FontFallBackRulesCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)