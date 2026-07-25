---
title: set_HideLeft()
second_title: Aspose.Slides for C++ API リファレンス
description: 左端を非表示にします（デフォルトは false） - 境界ボックスの左端が非表示または表示されている状態を指定します。
type: docs
weight: 79
url: /ja/aspose.slides.mathtext/imathborderbox/set_hideleft/
---
## IMathBorderBox::set_HideLeft(bool) メソッド

左端を非表示にする (デフォルトは false) - 境界ボックスの左端が非表示または表示されている状態を指定します。

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_HideLeft(bool value)=0
```

## 備考

例: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideLeft(true);
```

## 参照

* クラス [IMathBorderBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)