---
title: Insert()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスでコレクションに Paragraph を挿入します。
type: docs
weight: 66
url: /ja/aspose.slides/paragraphcollection/insert/
---
## ParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraph\>) メソッド

指定されたインデックスに、コレクションへ[Paragraph](../../paragraph/)を挿入します。

```cpp
void Aspose::Slides::ParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraph> value) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | [Paragraph](../../paragraph/) を挿入するゼロベースのインデックス。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | 挿入する[Paragraph](../../paragraph/)。 |

## ParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraphCollection\>) メソッド

指定されたインデックスに、コレクションへ[ParagraphCollection](../)のコンテンツを挿入します。

```cpp
void Aspose::Slides::ParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraphCollection> value) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 段落を挿入するゼロベースのインデックス。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../../iparagraphcollection/)\> | 挿入する段落。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IParagraph](../../iparagraph/)
* Class [ParagraphCollection](../)
* Class [IParagraphCollection](../../iparagraphcollection/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)