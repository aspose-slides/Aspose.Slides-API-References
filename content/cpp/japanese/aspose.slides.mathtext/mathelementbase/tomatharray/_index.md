---
title: ToMathArray()
second_title: Aspose.Slides for C++ API リファレンス
description: 垂直配列に配置します
type: docs
weight: 170
url: /ja/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() メソッド


垂直配列に配置します

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
```


### 戻り値

型 [IMathArray](../../imatharray/) の新しいインスタンス
## 備考



例:
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathArray](../../imatharray/)
* クラス [MathElementBase](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)