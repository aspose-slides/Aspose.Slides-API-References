---
title: set_HideDegree()
second_title: Aspose.Slides for C++ API リファレンス
description: Hide degree が true のとき、次数は表示されません。例として \\u221A\\uD835\\uDC65
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/imathradical/set_hidedegree/
---
## IMathRadical::set_HideDegree(bool) メソッド

Hide degree が true の場合、次数は表示されません。例として \\u221A\\uD835\\uDC65

```cpp
virtual void Aspose::Slides::MathText::IMathRadical::set_HideDegree(bool value)=0
```

## 備考

例:
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // 立方根
radical->set_HideDegree(true);
```

## 参照

* クラス [IMathRadical](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)