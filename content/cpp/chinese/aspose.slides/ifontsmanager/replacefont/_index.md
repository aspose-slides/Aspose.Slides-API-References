---
title: ReplaceFont()
second_title: Aspose.Slides C++ API 参考
description: 在演示文稿中替换字体
type: docs
weight: 118
url: /zh/aspose.slides/ifontsmanager/replacefont/
---
## IFontsManager::ReplaceFont(System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>) 方法

在演示文稿中替换字体

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontData> sourceFont, System::SharedPtr<IFontData> destFont)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | 源字体 |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | 目标字体 |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRule\>) 方法

使用 [IFontSubstRule](../../ifontsubstrule/) 中提供的信息在演示文稿中替换字体

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRule> substRule)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRule](../../ifontsubstrule/)\> | 字体替换信息 |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRuleCollection\>) 方法

使用 [IFontSubstRule](../../ifontsubstrule/) 提供的集合信息在演示文稿中替换字体

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRuleCollection> substRules)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | 字体替换信息集合 |

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IFontData](../../ifontdata/)
* 类 [IFontsManager](../)
* 类 [IFontSubstRule](../../ifontsubstrule/)
* 类 [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)