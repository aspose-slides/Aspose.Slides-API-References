---
title: Insert()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスに IMathBlock をコレクションへ挿入します。
type: docs
weight: 27
url: /ja/aspose.slides.mathtext/imathblockcollection/insert/
---
## IMathBlockCollection::Insert(int32_t, System::SharedPtr\<IMathBlock\>) メソッド

[IMathBlock](../../imathblock/) を指定されたインデックスにコレクションへ挿入します。

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Insert(int32_t index, System::SharedPtr<IMathBlock> item)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 挿入すべきアイテムのゼロベースインデックス。 |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 挿入する [IMathBlock](../../imathblock/)。 |
## 備考

例: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Insert(0, block);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathBlock](../../imathblock/)
* クラス [IMathBlockCollection](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)