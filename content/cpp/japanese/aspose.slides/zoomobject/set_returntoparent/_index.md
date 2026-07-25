---
title: set_ReturnToParent()
second_title: Aspose.Slides for C++ API リファレンス
description: "スライドショーでのナビゲーション動作を設定します。boolを書き込みます。デフォルト値: false"
type: docs
weight: 40
url: /ja/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) メソッド

スライドショーでのナビゲーション動作を設定します。**bool**を書き込みます。デフォルト値: false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## 備考


プロパティの true 値は、スライドショーでの親への戻りナビゲーション動作を指定します。

例:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## 参照

* クラス [ZoomObject](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)