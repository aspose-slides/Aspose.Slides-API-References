---
title: ReplaceFont()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: แทนที่แบบอักษรในงานนำเสนอ
type: docs
weight: 118
url: /th/aspose.slides/fontsmanager/replacefont/
---
## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontData\>, System::SharedPtr\<Aspose::Slides::IFontData\>) method

แทนที่แบบอักษรในงานนำเสนอ

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontData> sourceFont, System::SharedPtr<Aspose::Slides::IFontData> destFont) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | แบบอักษรต้นฉบับ |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | แบบอักษรปลายทาง |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRule\>) method

แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ไว้ใน [FontSubstRule](../../fontsubstrule/)

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRule> substRule) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../../ifontsubstrule/)\> | ข้อมูลการทดแทนแบบอักษร |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRuleCollection\>) method

แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ไว้ในคอลเลกชันของ [FontSubstRule](../../fontsubstrule/)

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRuleCollection> substRules) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | คอลเลกชันของกฎการทดแทนแบบอักษร |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [FontsManager](../)
* Class [IFontSubstRule](../../ifontsubstrule/)
* Class [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)