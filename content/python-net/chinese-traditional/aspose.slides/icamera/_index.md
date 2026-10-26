---
title: ICamera class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/icamera/
---
## ICamera 類別

代表相機。

ICamera 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`camera_type`](/slides/python-net/zh-hant/aspose.slides/icamera/camera_type/) | 相機類型<br/>            讀寫 [`CameraPresetType`](/slides/python-net/zh-hant/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/zh-hant/aspose.slides/icamera/field_of_view_angle/) | 相機視野 (0-180 度, field of View)<br/>            讀寫 **float**. |
| [`zoom`](/slides/python-net/zh-hant/aspose.slides/icamera/zoom/) | 相機縮放 (正值百分比)<br/>            讀寫 **float**. |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/zh-hant/aspose.slides/icamera/set_rotation/#float-float-float) | 透過緯度座標、經度座標以及繞該軸的旋轉來定義旋轉<br/>            若任何座標值為 float.NaN，則旋轉未定義。 |
| [`get_rotation(self)`](/slides/python-net/zh-hant/aspose.slides/icamera/get_rotation/#) | 透過緯度座標、經度座標以及繞該軸的旋轉來定義旋轉<br/>            回傳陣列的第一個元素 - 緯度，第二個 - 經度，第三個 - 旋轉次數。<br/>            若未定義旋轉，回傳 None。 |


### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)