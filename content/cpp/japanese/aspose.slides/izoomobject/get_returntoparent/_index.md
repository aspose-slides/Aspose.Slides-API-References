---
title: get_ReturnToParent()
second_title: Aspose.Slides for C++ API リファレンス
description: "スライドショーでのナビゲーション動作を取得します。bool を読み取ります。デフォルト値: false"
type: docs
weight: 27
url: /ja/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() メソッド

スライドショーでのナビゲーション動作を取得します。**bool** を読み取ります。デフォルト値: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## 備考

プロパティの true 値は、スライドショーでの親への戻りナビゲーション動作を指定します。

例: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## 参照

* クラス [IZoomObject](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)