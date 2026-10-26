---
title: get_IsDecorative()
second_title: Aspose.Slides for C++ APIリファレンス
description: 「Mark as decorative」オプションを取得し、読み取り/書き込み可能な bool を返します。
type: docs
weight: 521
url: /ja/aspose.slides/shape/get_isdecorative/
---
## Shape::get_IsDecorative() メソッド

「Mark as decorative」オプションを取得し、読み取り/書き込みが可能な **bool** を返します。

```cpp
bool Aspose::Slides::Shape::get_IsDecorative() override
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