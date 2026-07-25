---
title: set_HideDegree()
second_title: Aspose.Slides for C++ APIリファレンス
description: Hide degree が true の場合、次数は表示されません。例として \\u221A\\uD835\\uDC65
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/mathradical/set_hidedegree/
---
## MathRadical::set_HideDegree(bool) メソッド

Hide degree が true の場合、次数は表示されません。例として \\u221A\\uD835\\uDC65

```cpp
void Aspose::Slides::MathText::MathRadical::set_HideDegree(bool value) override
```

## 備考

例:
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
radical->set_HideDegree(true);
```

## 参照

* クラス [MathRadical](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)