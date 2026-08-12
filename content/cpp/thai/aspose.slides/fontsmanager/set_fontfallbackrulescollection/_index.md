---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงคอลเลกชันของผู้ใช้สำหรับกฎ FontFallBack เพื่อจัดการคอลเลกชันของแบบอักษรสำหรับการแทนที่ที่เหมาะสมโดยฟังก์ชัน fallback เขียน IFontFallBackRulesCollection.
type: docs
weight: 40
url: /th/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) เมธอด

แสดงคอลเลกชันของผู้ใช้สำหรับกฎ FontFallBack เพื่อจัดการคอลเลกชันของแบบอักษรสำหรับการแทนที่ที่เหมาะสมโดยฟังก์ชัน fallback เขียน [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
```

## หมายเหตุ

```cpp
auto pres = MakeObject<Presentation>();
// ดึงคอลเลกชันของกฎที่ว่างหรือกำหนดไว้ล่วงหน้าจาก FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// เพิ่มกฎเข้าไปในคอลเลกชัน
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// หรือ
// การเริ่มต้นอินสแตนซ์ใหม่ของคอลเลกชันกฎ
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// เพิ่มกฎเข้าไปในคอลเลกชัน
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// และการแทนที่คอลเลกชันที่มีอยู่ด้วยคอลเลกชันใหม่ใน FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## ดูเพิ่มเติม

* ชนิดนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* คลาส [FontsManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)