---
title: Add()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เพิ่มกฎ FallBack ที่ระบุไปยังส่วนท้ายของคอลเลกชัน.
type: docs
weight: 40
url: /th/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) เมธอด

เพิ่มกฎ FallBack ที่ระบุไปยังส่วนท้ายของคอลเลกชัน

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | กฎที่ระบุสำหรับการเพิ่ม |
## หมายเหตุ



```cpp
auto pres = MakeObject<Presentation>();
//การดึงคอลเลกชันกฎที่ว่างหรือที่กำหนดล่วงหน้าจาก FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//การเพิ่มกฎใหม่เข้าสู่คอลเลกชัน
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```


## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [IFontFallBackRule](../../ifontfallbackrule/)
* คลาส [FontFallBackRulesCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)