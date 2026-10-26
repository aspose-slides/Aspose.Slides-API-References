---
title: GetSubstitutions()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับข้อมูลเกี่ยวกับฟอนต์ที่จะแทนที่ในการแสดงผลของงานนำเสนอ
type: docs
weight: 66
url: /th/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() method

รับข้อมูลเกี่ยวกับฟอนต์ที่จะแทนที่ในการแสดงผลของงานนำเสนอ

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```

### ค่าที่ส่งคืน

คอลเลกชันของการทดแทนฟอนต์ทั้งหมด [FontSubstitutionInfo](../../fontsubstitutioninfo/).

## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) method

รับข้อมูลเกี่ยวกับฟอนต์ที่จะแทนที่ระหว่างการแสดงผลของสไลด์ที่ระบุ

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | อาร์เรย์ของดัชนีสไลด์ที่ต้องการดึงข้อมูลการทดแทนฟอนต์ เริ่มตั้งแต่ 1. |

### ค่าที่ส่งคืน

คอลเลกชันของการทดแทนฟอนต์ทั้งหมด ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) สำหรับสไลด์ที่ระบุ.

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
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)