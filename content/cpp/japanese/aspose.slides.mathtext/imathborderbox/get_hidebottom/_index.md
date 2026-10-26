---
title: get_HideBottom()
second_title: Aspose.Slides for C++ API リファレンス
description: 下端エッジを非表示にする (デフォルトは false) - ボーダーボックスの下端の非表示または表示の状態を指定します。
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/imathborderbox/get_hidebottom/
---
## IMathBorderBox::get_HideBottom() メソッド

下端エッジを非表示にする (デフォルトは false) - 境界ボックスの下端の隠れた状態または表示された状態を指定します。

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideBottom()=0
```

## 備考


例:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideBottom(true);
```

## 参照

* クラス [IMathBorderBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)