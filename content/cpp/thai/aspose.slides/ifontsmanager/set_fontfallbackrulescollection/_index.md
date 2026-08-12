---
title: set_FontFallBackRulesCollection()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงคอลเลกชันของกฎ FontFallBack ของผู้ใช้สำหรับการจัดการคอลเลกชันของฟอนต์เพื่อการแทนที่ที่เหมาะสมโดยฟังก์ชัน fallback Write IFontFallBackRulesCollection.
type: docs
weight: 40
url: /th/aspose.slides/ifontsmanager/set_fontfallbackrulescollection/
---
## IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<IFontFallBackRulesCollection\>) เมธอด


เป็นการแสดงถึงคอลเลกชันของกฎ FontFallBack ของผู้ใช้สำหรับการจัดการคอลเลกชันของฟอนต์เพื่อการแทนที่ที่เหมาะสมโดยฟังก์ชัน fallback Write [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual void Aspose::Slides::IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr<IFontFallBackRulesCollection> value)=0
```

## หมายเหตุ



```cpp
auto pres = MakeObject<Presentation>();
// รับคอลเลกชันของกฎที่ว่างหรือเตรียมไว้ล่วงหน้าจาก FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// เพิ่มกฎเข้าไปในคอลเลกชัน
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// หรือ
// การเริ่มต้นอินสแตนซ์ใหม่ของคอลเลกชันกฎ
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// เพิ่มกฎเข้าไปในคอลเลกชัน
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// และแทนที่คอลเลกชันที่มีอยู่ด้วยคอลเลกชันใหม่ใน FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## ดูเพิ่มเติม

* การกำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* คลาส [IFontsManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)