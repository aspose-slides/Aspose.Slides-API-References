---
title: set_IsDecorative()
second_title: Aspose.Slides for C++ API リファレンス
description: 'Mark as decorative' オプションを設定します。読み取り/書き込み **bool**.
type: docs
weight: 417
url: /ja/aspose.slides/ishape/set_isdecorative/
---
## IShape::set_IsDecorative(bool) メソッド


'Mark as decorative' オプションを設定します。読み取り/書き込み **bool**。

```cpp
virtual void Aspose::Slides::IShape::set_IsDecorative(bool value)=0
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