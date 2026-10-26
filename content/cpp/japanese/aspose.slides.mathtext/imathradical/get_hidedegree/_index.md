---
title: get_HideDegree()
second_title: Aspose.Slides for C++ API リファレンス
description: Hide degree が true の場合、度は表示されません。例として \\u221A\\uD835\\uDC65
type: docs
weight: 27
url: /ja/aspose.slides.mathtext/imathradical/get_hidedegree/
---
## IMathRadical::get_HideDegree() メソッド

Hide degree が true の場合、度数は表示されません。例として \\u221A\\uD835\\uDC65

```cpp
virtual bool Aspose::Slides::MathText::IMathRadical::get_HideDegree()=0
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