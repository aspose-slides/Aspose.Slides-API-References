---
title: ReplaceFont()
second_title: Aspose.Slides C++ API 参考
description: 在演示文稿中替换字体
type: docs
weight: 118
url: /zh/aspose.slides/fontsmanager/replacefont/
---
## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontData\>, System::SharedPtr\<Aspose::Slides::IFontData\>) 方法

在演示文稿中替换字体

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontData> sourceFont, System::SharedPtr<Aspose::Slides::IFontData> destFont) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | 源字体 |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | 目标字体 |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRule\>) 方法

使用 [FontSubstRule](../../fontsubstrule/) 中提供的信息在演示文稿中替换字体

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRule> substRule) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../../ifontsubstrule/)\> | 字体替换信息 |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRuleCollection\>) 方法

使用 [FontSubstRule](../../fontsubstrule/) 集合中提供的信息在演示文稿中替换字体

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRuleCollection> substRules) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | 字体替换规则集合 |

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IFontData](../../ifontdata/)
* 类 [FontsManager](../)
* 类 [IFontSubstRule](../../ifontsubstrule/)
* 类 [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)