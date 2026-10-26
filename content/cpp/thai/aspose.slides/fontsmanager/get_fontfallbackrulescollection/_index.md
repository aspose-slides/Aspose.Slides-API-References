---
title: get_FontFallBackRulesCollection()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงคอลเลกชันของกฎ FontFallBack ของผู้ใช้สำหรับการจัดการคอลเลกชันของฟอนต์เพื่อการแทนที่ที่เหมาะสมโดยฟังก์ชัน fallback อ่าน IFontFallBackRulesCollection.
type: docs
weight: 27
url: /th/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() เมธอด

แสดงถึงคอลเลกชันของกฎ FontFallBack ของผู้ใช้สำหรับการจัดการคอลเลกชันของฟอนต์เพื่อการแทนที่ที่เหมาะสมโดยฟังก์ชัน fallback อ่าน [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
```

## หมายเหตุ



```cpp
auto pres = MakeObject<Presentation>();
// รับคอลเลกชันของกฎที่ว่างเปล่าหรือที่กำหนดล่วงหน้าจาก FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// เพิ่มกฎเข้าสู่คอลเลกชัน
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// หรือ
// การเริ่มต้นอินสแตนซ์ใหม่ของคอลเลกชันกฎ
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// เพิ่มกฎเข้าสู่คอลเลกชัน
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// และการแทนที่คอลเลกชันที่มีอยู่ด้วยคอลเลกชันใหม่ใน FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Class [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)