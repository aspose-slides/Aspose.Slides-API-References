---
title: Insert()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定したインデックスにコレクションへ IMathBlock を挿入します。
type: docs
weight: 144
url: /ja/aspose.slides.mathtext/mathparagraph/insert/
---
## MathParagraph::Insert(int32_t, System::SharedPtr\<IMathBlock\>) メソッド


Inserts [IMathBlock](../../imathblock/) into the collection at the specified index.

```cpp
void Aspose::Slides::MathText::MathParagraph::Insert(int32_t index, System::SharedPtr<IMathBlock> mathBlock) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 挿入すべき項目のゼロベースインデックス。 |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 挿入する[IMathBlock](../../imathblock/)。 |
## 備考



例:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Insert(0, block);
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathBlock](../../imathblock/)
* クラス [MathParagraph](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)