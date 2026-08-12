---
title: GetSubstitutions()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: รับข้อมูลเกี่ยวกับฟอนต์ที่จะแทนที่ในการเรนเดอร์ของงานนำเสนอ
type: docs
weight: 66
url: /th/aspose.slides/fontsmanager/getsubstitutions/
---
## FontsManager::GetSubstitutions() เมธอด


รับข้อมูลเกี่ยวกับฟอนต์ที่จะแทนที่ในการเรนเดอร์ของงานนำเสนอ

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions() override
```


### ค่าที่ส่งกลับ

คอลเลกชันของการแทนที่ฟอนต์ทั้งหมด [FontSubstitutionInfo](../../fontsubstitutioninfo/).
## หมายเหตุ




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## FontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) เมธอด


รับข้อมูลเกี่ยวกับฟอนต์ที่จะแทนที่ระหว่างการเรนเดอร์ของสไลด์ที่ระบุ

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | อาร์เรย์ของดัชนีสไลด์ที่ต้องการดึงข้อมูลการแทนที่ฟอนต์ เริ่มต้นจาก 1. |

### ค่าที่ส่งกลับ

คอลเลกชันของการแทนที่ฟอนต์ทั้งหมด ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) สำหรับสไลด์ที่ระบุ.
## หมายเหตุ




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [IEnumerable](../../../system.collections.generic/ienumerable/)
* คลาส [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* คลาส [FontsManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)