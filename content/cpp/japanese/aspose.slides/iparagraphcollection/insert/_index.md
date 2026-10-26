---
title: Insert()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: 指定されたインデックスに Paragraph をコレクションに挿入します。
type: docs
weight: 40
url: /ja/aspose.slides/iparagraphcollection/insert/
---
## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraph\>) メソッド

指定されたインデックスに [Paragraph](../../paragraph/) をコレクションに挿入します。

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraph> value)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | [Paragraph](../../paragraph/) を挿入すべきゼロベースのインデックス。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | 挿入する[Paragraph](../../paragraph/)。 |

## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraphCollection\>) メソッド

指定されたインデックスに [ParagraphCollection](../../paragraphcollection/) のコンテンツをコレクションに挿入します。

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraphCollection> value)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 段落を挿入すべきゼロベースのインデックス。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | 挿入する段落。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IParagraph](../../iparagraph/)
* クラス [IParagraphCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)