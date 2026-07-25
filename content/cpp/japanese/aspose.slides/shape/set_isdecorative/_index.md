---
title: set_IsDecorative()
second_title: Aspose.Slides for C++ API リファレンス
description: 「Mark as decorative」オプションを設定します（読み取り/書き込み）bool.
type: docs
weight: 534
url: /ja/aspose.slides/shape/set_isdecorative/
---
## Shape::set_IsDecorative(bool) メソッド


「Mark as decorative」オプションを設定します（読み取り/書き込み）**bool**.

```cpp
void Aspose::Slides::Shape::set_IsDecorative(bool value) override
```

## 備考



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## 参照

* クラス [Shape](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)