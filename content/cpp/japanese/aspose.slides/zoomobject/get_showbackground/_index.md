---
title: get_ShowBackground()
second_title: Aspose.Slides for C++ API リファレンス
description: "Zoom が対象スライドの背景を使用するかどうかを指定する値を取得します。bool 型です。デフォルト値: true"
type: docs
weight: 53
url: /ja/aspose.slides/zoomobject/get_showbackground/
---
## ZoomObject::get_ShowBackground() メソッド


Zoom が対象スライドの背景を使用するかどうかを指定する値を取得します。取得 **bool**。デフォルト値: true

```cpp
bool Aspose::Slides::ZoomObject::get_ShowBackground() override
```

## 備考


この例は Zoom オブジェクトの画像から背景を削除することを示しています：

```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## 参照

* クラス [ZoomObject](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)