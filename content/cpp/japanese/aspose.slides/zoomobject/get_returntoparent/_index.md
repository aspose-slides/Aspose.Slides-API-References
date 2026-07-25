---
title: get_ReturnToParent()
second_title: Aspose.Slides for C++ API リファレンス
description: "スライドショーでのナビゲーション動作を取得します。bool を読み取ります。デフォルト値: false"
type: docs
weight: 27
url: /ja/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() メソッド

スライドショーでのナビゲーション動作を取得します。**bool** を読み取ります。デフォルト値: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## 備考

プロパティの true 値は、スライドショーでの親へ戻るナビゲーション動作を指定します。

例:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## 参照

* クラス [ZoomObject](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)