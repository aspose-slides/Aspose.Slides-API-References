---
title: Camera class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/camera/
---
## Camera 类

表示 Camera。

**继承:**[`Camera`](/slides/python-net/zh/aspose.slides/camera) → [`PVIObject`](/slides/python-net/zh/aspose.slides/pviobject)

Camera 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`camera_type`](/slides/python-net/zh/aspose.slides/camera/camera_type/) | Camera 类型。<br/>            读/写 [`CameraPresetType`](/slides/python-net/zh/aspose.slides/camerapresettype)。 |
| [`field_of_view_angle`](/slides/python-net/zh/aspose.slides/camera/field_of_view_angle/) | Camera FOV (0-180 度, 视场角)。<br/>            读/写 **float**。 |
| [`zoom`](/slides/python-net/zh/aspose.slides/camera/zoom/) | Camera 缩放（百分比的正值）。<br/>            读/写 **float**。 |
| [`slide`](/slides/python-net/zh/aspose.slides/camera/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/camera/presentation/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/zh/aspose.slides/camera/set_rotation/#float-float-float) | 旋转是通过使用纬度<br/>            坐标、经度坐标以及围绕轴线的旋转来定义的，<br/>            以纬度和经度坐标为准。<br/>            如果任意坐标值为 float.NaN，则所有旋转均未定义。 |
| [`get_rotation(self)`](/slides/python-net/zh/aspose.slides/camera/get_rotation/#) | 旋转是通过使用纬度<br/>            坐标、经度坐标以及围绕轴线的旋转来定义的，<br/>            以纬度和经度坐标为准。<br/>            返回数组的第一个元素 - 纬度，第二个 - 经度，第三个 - 旋转。<br/>            如果未定义旋转，则返回 None。 |

### 另请参见
* 类 [`Camera`](/slides/python-net/zh/aspose.slides/camera)
* 类 [`PVIObject`](/slides/python-net/zh/aspose.slides/pviobject)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)