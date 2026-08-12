---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides สำหรับ C++ API เอกสารอ้างอิง
description: แสดงคอลเลกชันของผู้ใช้สำหรับกฎ FontFallBack เพื่อจัดการคอลเลกชันของฟอนต์เพื่อการแทนที่ที่เหมาะสมโดยฟังก์ชัน fallback อ่าน IFontFallBackRulesCollection.
type: docs
weight: 27
url: /th/aspose.slides/ifontsmanager/get_fontfallbackrulescollection/
---
## IFontsManager::get_FontFallBackRulesCollection() เมธอด

แสดงคอลเลกชันของผู้ใช้ของกฎ FontFallBack สำหรับการจัดการคอลเลกชันของฟอนต์เพื่อการแทนที่ที่เหมาะสมโดยฟังก์ชัน fallback อ่าน [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual System::SharedPtr<IFontFallBackRulesCollection> Aspose::Slides::IFontsManager::get_FontFallBackRulesCollection()=0
```

## หมายเหตุ



```cpp
auto pres = MakeObject<Presentation>();
// ดึงคอลเลกชันของกฎที่ว่างหรือที่กำหนดล่วงหน้าจาก FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// เพิ่มกฎลงในคอลเลกชัน
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// หรือ
// การเริ่มต้นอินสแตนซ์ใหม่ของคอลเลกชันกฎ
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// เพิ่มกฎลงในคอลเลกชัน
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// และแทนที่คอลเลกชันที่มีอยู่ด้วยคอลเลกชันใหม่ใน FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* คลาส [IFontsManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)