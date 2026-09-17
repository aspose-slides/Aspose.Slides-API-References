---
title: ICamera class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/icamera/
---
## ICamera クラス

カメラを表します。

ICamera 型は次のメンバーを公開します：

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`camera_type`](/slides/python-net/ja/aspose.slides/icamera/camera_type/) | カメラタイプ<br/>            読み取り/書き込み [`CameraPresetType`](/slides/python-net/ja/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/ja/aspose.slides/icamera/field_of_view_angle/) | カメラ FOV (0-180 度、視野)<br/>            読み取り/書き込み **float**. |
| [`zoom`](/slides/python-net/ja/aspose.slides/icamera/zoom/) | カメラズーム (パーセンテージの正の値)<br/>            読み取り/書き込み **float**. |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/ja/aspose.slides/icamera/set_rotation/#float-float-float) | 緯度座標、経度座標、および軸周りの回転を使用して回転が定義されます。<br/>            任意の座標値が float.NaN の場合、すべての回転は未定義です。 |
| [`get_rotation(self)`](/slides/python-net/ja/aspose.slides/icamera/get_rotation/#) | 緯度座標、経度座標、および軸周りの回転を使用して回転が定義されます。<br/>            戻り配列の最初の要素 - 緯度、2 番目 - 経度、3 番目 - 回転。<br/>            回転が定義されていない場合は None を返します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)