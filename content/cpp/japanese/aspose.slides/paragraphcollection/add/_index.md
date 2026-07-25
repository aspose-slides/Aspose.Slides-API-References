---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: Paragraph をコレクションの末尾に追加します。
type: docs
weight: 40
url: /ja/aspose.slides/paragraphcollection/add/
---
## ParagraphCollection::Add(System::SharedPtr\<IParagraph\>) メソッド

コレクションの末尾に [Paragraph](../../paragraph/) を追加します。

```cpp
void Aspose::Slides::ParagraphCollection::Add(System::SharedPtr<IParagraph> value) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | コレクションの末尾に追加される [Paragraph](../../paragraph/) 。 |

## ParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) メソッド

コレクションの末尾に [ParagraphCollection](../) のコンテンツを追加します。

```cpp
int32_t Aspose::Slides::ParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../../iparagraphcollection/)\> | コレクションの末尾に追加される [ParagraphCollection](../) 。 |

### 戻り値

[Paragraph](../../paragraph/) が追加されたインデックスを返します。追加するものが無い場合は -1 を返します。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IParagraph](../../iparagraph/)
* クラス [ParagraphCollection](../)
* クラス [IParagraphCollection](../../iparagraphcollection/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)