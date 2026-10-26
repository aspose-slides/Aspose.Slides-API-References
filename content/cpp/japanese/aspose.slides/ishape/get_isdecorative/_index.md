---
title: get_IsDecorative()
second_title: Aspose.Slides for C++ API リファレンス
description: 「Mark as decorative」オプションを取得し、読み取り/書き込み可能なboolです。
type: docs
weight: 404
url: /ja/aspose.slides/ishape/get_isdecorative/
---
## IShape::get_IsDecorative() メソッド


取得します 'Mark as decorative' オプション 読み取り/書き込み **bool**.

```cpp
virtual bool Aspose::Slides::IShape::get_IsDecorative()=0
```

## 備考



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## 参照

* クラス [IShape](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)