---
title: ReplaceFont()
second_title: Aspose.Slides for C++ API 參考文件
description: 在簡報中取代字型
type: docs
weight: 118
url: /zh-hant/aspose.slides/ifontsmanager/replacefont/
---
## IFontsManager::ReplaceFont(System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>) method

在簡報中取代字型

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontData> sourceFont, System::SharedPtr<IFontData> destFont)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | 來源字型 |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | 目標字型 |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRule\>) method

使用 [IFontSubstRule](../../ifontsubstrule/) 中提供的資訊在簡報中取代字型

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRule> substRule)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRule](../../ifontsubstrule/)\> | 字型替換資訊 |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRuleCollection\>) method

使用 [IFontSubstRule](../../ifontsubstrule/) 集合中提供的資訊在簡報中取代字型

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRuleCollection> substRules)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | 字型替換資訊集合 |

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IFontData](../../ifontdata/)
* 類別 [IFontsManager](../)
* 類別 [IFontSubstRule](../../ifontsubstrule/)
* 類別 [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)