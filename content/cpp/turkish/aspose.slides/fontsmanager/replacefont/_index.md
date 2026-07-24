---
title: ReplaceFont()
second_title: Aspose.Slides for C++ API Referansı
description: Sunumda yazı tipini değiştir
type: docs
weight: 118
url: /tr/aspose.slides/fontsmanager/replacefont/
---
## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontData\>, System::SharedPtr\<Aspose::Slides::IFontData\>) metodu


Sunumdaki yazı tipini değiştir

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontData> sourceFont, System::SharedPtr<Aspose::Slides::IFontData> destFont) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | Kaynak yazı tipi |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | Hedef yazı tipi |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRule\>) metodu


[FontSubstRule](../../fontsubstrule/) içinde sağlanan bilgiler kullanılarak sunumdaki yazı tipini değiştir

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRule> substRule) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../../ifontsubstrule/)\> | Yazı tipi ikame bilgisi |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRuleCollection\>) metodu


[FontSubstRule](../../fontsubstrule/) koleksiyonunda sağlanan bilgiler kullanılarak sunumdaki yazı tipini değiştir

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRuleCollection> substRules) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | Yazı tipi ikame kuralları koleksiyonu |

## İlgili Bilgiler

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IFontData](../../ifontdata/)
* Sınıf [FontsManager](../)
* Sınıf [IFontSubstRule](../../ifontsubstrule/)
* Sınıf [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)