---
title: get_ShowBackground()
second_title: Aspose.Slides for C++ API リファレンス
description: "ズームが宛先スライドの背景を使用するかどうかを指定する値を取得します。bool を読み取ります。デフォルト値: true"
type: docs
weight: 53
url: /ja/aspose.slides/izoomobject/get_showbackground/
---
## IZoomObject::get_ShowBackground() メソッド


ズームが宛先スライドの背景を使用するかどうかを指定する値を取得します。**bool** を読み取ります。デフォルト値: true

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ShowBackground()=0
```

## 備考


この例では、Zoom オブジェクトの画像から背景を削除する方法を示します: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## 参照

* クラス [IZoomObject](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)