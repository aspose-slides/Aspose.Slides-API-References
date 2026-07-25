---
title: ToMathArray()
second_title: Aspose.Slides for C++ API リファレンス
description: 子要素を縦方向の配列に配置します
type: docs
weight: 235
url: /ja/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() メソッド

Puts child elements in a vertical array

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
```

### 戻り値

New instance of type [IMathArray](../../imatharray/)
## 備考



例：
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathArray](../../imatharray/)
* クラス [MathBlock](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)