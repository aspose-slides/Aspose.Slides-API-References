---
title: ICameraEffectiveData class
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/icameraeffectivedata/
---
## ICameraEffectiveData 類別

不可變物件，包含有效的相機屬性。

ICameraEffectiveData 類型公開下列成員：

## 屬性

| Property | Description |
| :- | :- |
| [`camera_type`](/slides/python-net/zh-hant/aspose.slides/icameraeffectivedata/camera_type/) | 相機類型。<br/>            唯讀 [`CameraPresetType`](/slides/python-net/zh-hant/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/zh-hant/aspose.slides/icameraeffectivedata/field_of_view_angle/) | 相機視野角度 (0-180 度, field of View)。<br/>            唯讀 **float**. |
| [`zoom`](/slides/python-net/zh-hant/aspose.slides/icameraeffectivedata/zoom/) | 相機縮放 (正值，以百分比表示)。<br/>            唯讀 **float**. |

## 方法

| Method | Description |
| :- | :- |
| [`get_rotation(self)`](/slides/python-net/zh-hant/aspose.slides/icameraeffectivedata/get_rotation/#) | 旋轉是透過使用緯度<br/>            座標、經度座標以及關於軸的旋轉來定義，<br/>            如同緯度和經度座標。<br/>            回傳陣列的第一個元素為緯度，第二個為經度，第三個為旋轉。<br/>            若未定義旋轉，則回傳 None。 |

### 備註

此介面用於 [`IThreeDFormatEffectiveData`](/slides/python-net/zh-hant/aspose.slides/ithreedformateffectivedata) 的一部分。

### 另見
* 類別 [`IThreeDFormatEffectiveData`](/slides/python-net/zh-hant/aspose.slides/ithreedformateffectivedata)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)