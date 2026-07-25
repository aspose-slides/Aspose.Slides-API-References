---
title: idx_get()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスの項目を取得します。読み取り専用 IMathBlockです。
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/mathparagraph/idx_get/
---
## MathParagraph::idx_get(int32_t) メソッド


指定されたインデックスの項目を取得します。読み取り専用 [IMathBlock](../../imathblock/)。

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathParagraph::idx_get(int32_t index) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 取得する項目のゼロベースインデックス |

### 戻り値

数式テキストのブロックです。

## 備考



例: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = mathParagraph->idx_get(1);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathBlock](../../imathblock/)
* クラス [MathParagraph](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)