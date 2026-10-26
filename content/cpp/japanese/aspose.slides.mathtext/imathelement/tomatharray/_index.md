---
title: ToMathArray()
second_title: Aspose.Slides for C++ API リファレンス
description: 垂直配列に入れます
type: docs
weight: 183
url: /ja/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() メソッド


垂直配列に入れます

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
```


### 戻り値

型[IMathArray](../../imatharray/)の新しいインスタンス
## 備考



例: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathArray](../../imatharray/)
* クラス [IMathElement](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)