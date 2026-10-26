---
title: set_ShowBackground()
second_title: Aspose.Slides for C++ API リファレンス
description: "Zoom が対象スライドの背景を使用するかどうかを指定する値を設定します。bool を記述します。デフォルト値: true"
type: docs
weight: 66
url: /ja/aspose.slides/zoomobject/set_showbackground/
---
## ZoomObject::set_ShowBackground(bool) メソッド


Zoomが対象スライドの背景を使用するかどうかを指定する値を設定します。**bool** 型で記述します。デフォルト値: true

```cpp
void Aspose::Slides::ZoomObject::set_ShowBackground(bool value) override
```

## 備考


この例は、Zoom オブジェクトの画像から背景を削除する方法を示しています:
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