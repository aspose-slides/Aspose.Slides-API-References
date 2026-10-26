---
title: IndexOf()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクション内の特定の IMathBlock のインデックスを決定します。
type: docs
weight: 79
url: /ja/aspose.slides.mathtext/imathblockcollection/indexof/
---
## IMathBlockCollection::IndexOf(System::SharedPtr\<IMathBlock\>) メソッド

コレクション内の特定の [IMathBlock](../../imathblock/) のインデックスを決定します。

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::IndexOf(System::SharedPtr<IMathBlock> item)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | コレクション内で検索する項目。 |

### 戻り値

コレクション内で *item* が見つかった場合のインデックス；それ以外の場合は -1.

## 備考

例: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
int32_t index = blockCollection->IndexOf(block);
```

## 関連項目

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathBlock](../../imathblock/)
* クラス [IMathBlockCollection](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)