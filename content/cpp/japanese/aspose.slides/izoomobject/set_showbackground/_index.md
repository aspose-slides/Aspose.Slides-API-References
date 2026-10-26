---
title: set_ShowBackground()
second_title: Aspose.Slides for C++ API リファレンス
description: "Zoom が宛先スライドの背景を使用するかどうかを指定する値を設定します。boolを書き込みます。デフォルト値: true"
type: docs
weight: 66
url: /ja/aspose.slides/izoomobject/set_showbackground/
---
## IZoomObject::set_ShowBackground(bool) メソッド


Zoom が宛先スライドの背景を使用するかどうかを指定する値を設定します。**bool**を書き込みます。デフォルト値: true

```cpp
virtual void Aspose::Slides::IZoomObject::set_ShowBackground(bool value)=0
```

## 備考


この例は、Zoom オブジェクトの画像の背景を削除する方法を示しています: 
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