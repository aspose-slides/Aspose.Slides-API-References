---
title: get_Format()
second_title: Aspose.Slides for C++ API リファレンス
description: テキストの書式設定プロパティ
type: docs
weight: 27
url: /ja/aspose.slides.mathtext/imathematicaltext/get_format/
---
## IMathematicalText::get_Format() メソッド


テキストの書式設定プロパティ

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::MathText::IMathematicalText::get_Format()=0
```

## 備考


例: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
mathText->get_Format()->set_FontHeight(28.0f);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IPortionFormat](../../../aspose.slides/iportionformat/)
* クラス [IMathematicalText](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)