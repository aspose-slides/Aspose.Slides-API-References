---
title: GetImage()
second_title: Aspose.Slides for C++ API リファレンス
description: "シェイプのサムネイルを返します。デフォルトでは ShapeThumbnailBounds::Shape シェイプサムネイル境界タイプが使用されます。"
type: docs
weight: 547
url: /ja/aspose.slides/ishape/getimage/
---
## IShape::GetImage() メソッド

シェイプのサムネイルを返します。[ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) shape thumbnail bounds type がデフォルトで使用されます。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```

### 戻り値

[Shape](../../shape/) サムネイル。

## IShape::GetImage(ShapeThumbnailBounds, float, float) メソッド

シェイプのサムネイルを返します。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) thumbnail bounds type. |
| scaleX | **float** | X スケール |
| scaleY | **float** | Y スケール |

### 戻り値

[Shape](../../shape/) サムネイル、または [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) が使用され、シェイプに可視要素がない場合は null が返されます。

## 参照

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IImage](../../iimage/)
* クラス [IShape](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)