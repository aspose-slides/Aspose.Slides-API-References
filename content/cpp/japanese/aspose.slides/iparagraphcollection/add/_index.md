---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションの末尾に Paragraph を追加します。
type: docs
weight: 27
url: /ja/aspose.slides/iparagraphcollection/add/
---
## IParagraphCollection::Add(System::SharedPtr\<IParagraph\>) メソッド

コレクションの末尾に [Paragraph](../../paragraph/) を追加します。

```cpp
virtual void Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraph> value)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | コレクションの末尾に追加される [Paragraph](../../paragraph/)。 |

## IParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) メソッド

コレクションの末尾に [ParagraphCollection](../../paragraphcollection/) の内容を追加します。

```cpp
virtual int32_t Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | コレクションの末尾に追加される [ParagraphCollection](../../paragraphcollection/)。 |

### 戻り値

[Paragraph](../../paragraph/) が追加されたインデックス、または追加するものが何もない場合は -1。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IParagraph](../../iparagraph/)
* クラス [IParagraphCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)