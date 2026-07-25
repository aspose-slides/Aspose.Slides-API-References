---
title: get_HideDegree()
second_title: Aspose.Slides for C++ API リファレンス
description: Hide degree が true の場合、次数は表示されません。例: \\u221A\\uD835\\uDC65
type: docs
weight: 27
url: /ja/aspose.slides.mathtext/mathradical/get_hidedegree/
---
## MathRadical::get_HideDegree() メソッド

Hide degree が true の場合、次数は表示されません（例: \\u221A\\uD835\\uDC65）。

```cpp
bool Aspose::Slides::MathText::MathRadical::get_HideDegree() override
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