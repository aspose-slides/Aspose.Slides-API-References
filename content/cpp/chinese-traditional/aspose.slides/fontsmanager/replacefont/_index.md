---
title: ReplaceFont()
second_title: Aspose.Slides for C++ API 參考文件
description: 在簡報中替換字型
type: docs
weight: 118
url: /zh-hant/aspose.slides/fontsmanager/replacefont/
---
## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontData\>, System::SharedPtr\<Aspose::Slides::IFontData\>) 方法


在簡報中替換字型

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontData> sourceFont, System::SharedPtr<Aspose::Slides::IFontData> destFont) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | 來源字型 |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | 目標字型 |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRule\>) 方法


使用 [FontSubstRule](../../fontsubstrule/) 中提供的資訊在簡報中替換字型

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRule> substRule) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../../ifontsubstrule/)\> | 字型替代資訊 |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRuleCollection\>) 方法


使用 [FontSubstRule](../../fontsubstrule/) 集合中提供的資訊在簡報中替換字型

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRuleCollection> substRules) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | 字型替代規則集合 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [FontsManager](../)
* Class [IFontSubstRule](../../ifontsubstrule/)
* Class [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)