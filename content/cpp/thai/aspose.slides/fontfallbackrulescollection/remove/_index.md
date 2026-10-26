---
title: Remove()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ลบการเกิดขึ้นครั้งแรกของกฎ FallBack เฉพาะจากคอลเลกชัน
type: docs
weight: 53
url: /th/aspose.slides/fontfallbackrulescollection/remove/
---
## FontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) เมธอด


ลบการเกิดขึ้นครั้งแรกของกฎ FallBack เฉพาะจากคอลเลกชัน

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | กฎที่ต้องลบออกจากคอลเลกชัน |
## หมายเหตุ



```cpp
auto pres = MakeObject<Presentation>();
//รับคอลเลกชันกฎที่ว่างหรือกำหนดค่าไว้ล่วงหน้าจาก FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//เพิ่มกฎหลายรายการเข้าสู่คอลเลกชัน
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//ดึงอ็อบเจกต์ของกฎแรกในคอลเลกชัน
auto firstRule = rulesList->idx_get(0);
//ลบ
rulesList->Remove(firstRule);
```


## ดูเพิ่มเติม

* ชนิดกำหนด [SharedPtr](../../../system/sharedptr/)
* คลาส [IFontFallBackRule](../../ifontfallbackrule/)
* คลาส [FontFallBackRulesCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)