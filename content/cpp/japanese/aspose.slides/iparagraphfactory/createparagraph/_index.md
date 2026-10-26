---
title: CreateParagraph()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しい空の段落を作成します。
type: docs
weight: 1
url: /ja/aspose.slides/iparagraphfactory/createparagraph/
---
## IParagraphFactory::CreateParagraph() メソッド


新しい空の段落を作成します。

```cpp
virtual System::SharedPtr<IParagraph> Aspose::Slides::IParagraphFactory::CreateParagraph()=0
```


### 戻り値

[Paragraph](../../paragraph/)。

## IParagraphFactory::CreateParagraph(System::SharedPtr\<IParagraph\>) メソッド


指定された段落データを使用して新しい段落を作成します。

```cpp
virtual System::SharedPtr<IParagraph> Aspose::Slides::IParagraphFactory::CreateParagraph(System::SharedPtr<IParagraph> paragraph)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | データを使用する段落です。 |

### 戻り値

[Paragraph](../../paragraph/)。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IParagraph](../../iparagraph/)
* クラス [IParagraphFactory](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)