---
title: GetImage()
second_title: Aspose.Slides for C++ API リファレンス
description: "シェイプのサムネイルを返します。デフォルトで ShapeThumbnailBounds::Shape のシェイプサムネイル境界タイプが使用されます。"
type: docs
weight: 651
url: /ja/aspose.slides/shape/getimage/
---
## Shape::GetImage() メソッド

シェイプのサムネイルを返します。[ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) シェイプのサムネイル境界タイプがデフォルトで使用されます。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```

### 戻り値

[Shape](../) サムネイル。

## Shape::GetImage(ShapeThumbnailBounds, float, float) メソッド

シェイプのサムネイルを返します。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) サムネイル境界タイプ。 |
| scaleX | **float** | X スケール |
| scaleY | **float** | Y スケール |

### 戻り値

[Shape](../) サムネイルまたは、[ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) が使用され、シェイプに表示可能な要素がない場合は null。

## 参照

* 列挙体 [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IImage](../../iimage/)
* クラス [Shape](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)