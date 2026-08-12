---
title: ReplaceFont()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: แทนที่แบบอักษรในงานนำเสนอ
type: docs
weight: 118
url: /th/aspose.slides/ifontsmanager/replacefont/
---
## IFontsManager::ReplaceFont(System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>) method


แทนที่แบบอักษรในงานนำเสนอ

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontData> sourceFont, System::SharedPtr<IFontData> destFont)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | แบบอักษรต้นทาง |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | แบบอักษรปลายทาง |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRule\>) method


แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ไว้ใน [IFontSubstRule](../../ifontsubstrule/)

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRule> substRule)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRule](../../ifontsubstrule/)\> | ข้อมูลการแทนที่แบบอักษร |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRuleCollection\>) method


แทนที่แบบอักษรในงานนำเสนอโดยใช้ข้อมูลที่ให้ไว้ในคอลเลกชันของ [IFontSubstRule](../../ifontsubstrule/)

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRuleCollection> substRules)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | คอลเลกชันข้อมูลการแทนที่แบบอักษร |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IFontData](../../ifontdata/)
* คลาส [IFontsManager](../)
* คลาส [IFontSubstRule](../../ifontsubstrule/)
* คลาส [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)