---
title: set_ReturnToParent()
second_title: Aspose.Slides for C++ APIリファレンス
description: "スライドショーでのナビゲーション動作を設定します。bool を書き込みます。デフォルト値: false"
type: docs
weight: 40
url: /ja/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) メソッド


スライドショーでのナビゲーション動作を設定します。**bool** を書き込みます。デフォルト値: false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## 備考


プロパティの true 値は、スライドショーで親に戻るナビゲーション動作を指定します。

例:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## 参考

* クラス [IZoomObject](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)