---
title: Remove()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ลบการเกิดขึ้นครั้งแรกของกฎ FallBack ที่ระบุจากคอลเลกชัน.
type: docs
weight: 27
url: /th/aspose.slides/ifontfallbackrulescollection/remove/
---
## IFontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) method


ลบการเกิดขึ้นครั้งแรกของกฎ FallBack ที่ระบุจากคอลเลกชัน

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | กฎที่จะลบออกจากคอลเลกชัน |
## Remarks



```cpp
auto pres = MakeObject<Presentation>();
//ดึงคอลเลกชันกฎที่ว่างหรือกำหนดล่วงหน้าจาก FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//เพิ่มกฎหลายรายการลงในคอลเลกชัน
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//ดึงอ็อบเจ็กต์ของกฎแรกในคอลเลกชัน
auto firstRule = rulesList->idx_get(0);
//กำลังลบ
rulesList->Remove(firstRule);
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IFontFallBackRule](../../ifontfallbackrule/)
* คลาส [IFontFallBackRulesCollection](../)
* เนมส페ซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)