---
title: Camera class
second_title: Aspose.Slides 用於 Python 通過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/camera/
---
## Camera 類別

Represents Camera.

**Inheritance:**[`Camera`](/slides/python-net/zh-hant/aspose.slides/camera) → [`PVIObject`](/slides/python-net/zh-hant/aspose.slides/pviobject)

The Camera type exposes the following members:

## 屬性

| Property | Description |
| :- | :- |
| [`camera_type`](/slides/python-net/zh-hant/aspose.slides/camera/camera_type/) | Camera 類型。<br/>            可讀寫 [`CameraPresetType`](/slides/python-net/zh-hant/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/zh-hant/aspose.slides/camera/field_of_view_angle/) | Camera FOV (0-180 度, 視野)。<br/>            可讀寫 **float**. |
| [`zoom`](/slides/python-net/zh-hant/aspose.slides/camera/zoom/) | Camera 縮放 (正值，以百分比表示)。<br/>            可讀寫 **float**. |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/camera/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/camera/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/zh-hant/aspose.slides/camera/set_rotation/#float-float-float) | 旋轉是透過使用緯度<br/>            座標、經度座標，及繞軸的旋轉<br/>            如緯度和經度座標。<br/>            如果任何座標值為 float.NaN，則所有旋轉皆未定義. |
| [`get_rotation(self)`](/slides/python-net/zh-hant/aspose.slides/camera/get_rotation/#) | 旋轉是透過使用緯度<br/>            座標、經度座標，及繞軸的旋轉<br/>            如緯度和經度座標。<br/>            回傳陣列的第一個元素 - 緯度，第二個 - 經度，第三個 - 旋轉。<br/>            若未定義旋轉，回傳 None. |

### 參見
* 類別 [`Camera`](/slides/python-net/zh-hant/aspose.slides/camera)
* 類別 [`PVIObject`](/slides/python-net/zh-hant/aspose.slides/pviobject)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)