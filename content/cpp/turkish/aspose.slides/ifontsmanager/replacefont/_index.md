---
title: ReplaceFont()
second_title: Aspose.Slides for C++ API Referansı
description: Sunumda yazı tipini değiştir
type: docs
weight: 118
url: /tr/aspose.slides/ifontsmanager/replacefont/
---
## IFontsManager::ReplaceFont(System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>) metodu

Sunumda yazı tipini değiştir

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontData> sourceFont, System::SharedPtr<IFontData> destFont)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Kaynak yazı tipi |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Hedef yazı tipi |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRule\>) metodu

Sunumda [IFontSubstRule](../../ifontsubstrule/) içinde sağlanan bilgiler kullanılarak yazı tipini değiştir

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRule> substRule)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRule](../../ifontsubstrule/)\> | Yazı tipi değiştirme bilgisi |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRuleCollection\>) metodu

Sunumda [IFontSubstRule](../../ifontsubstrule/) koleksiyonunda sağlanan bilgiler kullanılarak yazı tipini değiştir

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRuleCollection> substRules)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | Yazı tipi değiştirme bilgi koleksiyonu |

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Class [IFontSubstRule](../../ifontsubstrule/)
* Class [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)