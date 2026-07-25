---
title: get_StrikethroughBottomLeftToTopRight()
second_title: Aspose.Slides for C++ API リファレンス
description: ボトム左からトップ右への取り消し線（デフォルトは false）。ボーダーボックスの左下隅から右上隅へ向かう斜めの取り消し線の表示/非表示状態を指定します。
type: docs
weight: 170
url: /ja/aspose.slides.mathtext/mathborderbox/get_strikethroughbottomlefttotopright/
---
## MathBorderBox::get_StrikethroughBottomLeftToTopRight() メソッド

Strikethrough Bottom-Left to Top-Right (default is false). Specifies the hidden or shown state of a strikethrough diagonal line from the bottom-left corner to the top-right corner of border box.

```cpp
bool Aspose::Slides::MathText::MathBorderBox::get_StrikethroughBottomLeftToTopRight() override
```

## 備考

例: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
borderBox->set_StrikethroughBottomLeftToTopRight(true);
```

## 参照

* クラス [MathBorderBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)