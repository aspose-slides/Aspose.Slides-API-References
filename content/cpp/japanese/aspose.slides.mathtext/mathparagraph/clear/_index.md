---
title: Clear()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションからすべての要素を削除します。
type: docs
weight: 79
url: /ja/aspose.slides.mathtext/mathparagraph/clear/
---
## MathParagraph::Clear() メソッド

コレクションからすべての要素を削除します。

```cpp
void Aspose::Slides::MathText::MathParagraph::Clear() override
```

## 備考

例: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
mathParagraph->Clear();
```

## 参照

* クラス [MathParagraph](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)