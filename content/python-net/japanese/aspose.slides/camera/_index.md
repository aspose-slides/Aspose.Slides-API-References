---
title: Camera class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/camera/
---
## Camera クラス

Camera を表します。

**継承:**[`Camera`](/slides/python-net/ja/aspose.slides/camera) → [`PVIObject`](/slides/python-net/ja/aspose.slides/pviobject)

Camera 型は次のメンバーを公開します:

## プロパティ

| Property | Description |
| :- | :- |
| [`camera_type`](/slides/python-net/ja/aspose.slides/camera/camera_type/) | Camera タイプ。<br/>            読み書き [`CameraPresetType`](/slides/python-net/ja/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/ja/aspose.slides/camera/field_of_view_angle/) | Camera FOV (0-180 度, 視野角)。<br/>            読み書き **float**. |
| [`zoom`](/slides/python-net/ja/aspose.slides/camera/zoom/) | Camera ズーム (パーセンテージでの正の値)。<br/>            読み書き **float**. |
| [`slide`](/slides/python-net/ja/aspose.slides/camera/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/camera/presentation/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/ja/aspose.slides/camera/set_rotation/#float-float-float) | 緯度座標、経度座標、および軸周りの回転を使用して回転が定義されます。<br/>            緯度座標と経度座標として軸周りの回転です。<br/>            任意の座標値が float.NaN の場合、すべての回転は未定義となります。 |
| [`get_rotation(self)`](/slides/python-net/ja/aspose.slides/camera/get_rotation/#) | 緯度座標、経度座標、および軸周りの回転を使用して回転が定義されます。<br/>            戻り配列の最初の要素 - 緯度、2 番目 - 経度、3 番目 - 回転。<br/>            回転が定義されていない場合は None を返します。 |


### 参照
* クラス [`Camera`](/slides/python-net/ja/aspose.slides/camera)
* クラス [`PVIObject`](/slides/python-net/ja/aspose.slides/pviobject)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)