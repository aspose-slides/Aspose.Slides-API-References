---
title: MathPortion()
second_title: Aspose.Slides for C++ API リファレンス
description: MathPortion クラスの新しいインスタンスを初期化します。
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() コンストラクタ


新しい [MathPortion](../) クラスのインスタンスを初期化します。

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## 備考


例: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## 参照

* クラス [MathPortion](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)