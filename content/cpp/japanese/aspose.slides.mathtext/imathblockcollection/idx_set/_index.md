---
title: idx_set()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスの項目を取得します。読み取り専用 IMathBlock.
type: docs
weight: 105
url: /ja/aspose.slides.mathtext/imathblockcollection/idx_set/
---
## IMathBlockCollection::idx_set(int32_t, System::SharedPtr\<IMathBlock\>) method


指定されたインデックスの項目を取得します。読み取り専用 [IMathBlock](../../imathblock/).

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::idx_set(int32_t index, System::SharedPtr<IMathBlock> value)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 取得する項目のゼロベースインデックス |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 数式テキストのブロック |
## 備考



例: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = blockCollection->idx_get(1);
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathBlock](../../imathblock/)
* クラス [IMathBlockCollection](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)