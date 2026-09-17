---
title: ICamera class
second_title: Aspose.Slides 用于 Python 的 .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/icamera/
---
## ICamera 类

表示相机。

ICamera 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`camera_type`](/slides/python-net/zh/aspose.slides/icamera/camera_type/) | 相机类型<br/>            读/写 [`CameraPresetType`](/slides/python-net/zh/aspose.slides/camerapresettype)。 |
| [`field_of_view_angle`](/slides/python-net/zh/aspose.slides/icamera/field_of_view_angle/) | 相机视野（0-180 度，视场）<br/>            读/写 **float**。 |
| [`zoom`](/slides/python-net/zh/aspose.slides/icamera/zoom/) | 相机缩放（百分比的正值）<br/>            读/写 **float**。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/zh/aspose.slides/icamera/set_rotation/#float-float-float) | 通过使用纬度<br/>            坐标、经度坐标以及围绕轴的旋转来定义旋转<br/>            与纬度和经度坐标相同。<br/>            如果任意坐标值为 float.NaN，则所有旋转未定义。 |
| [`get_rotation(self)`](/slides/python-net/zh/aspose.slides/icamera/get_rotation/#) | 通过使用纬度<br/>            坐标、经度坐标以及围绕轴的旋转来定义旋转<br/>            第一个返回数组元素 - 纬度，第二个 - 经度，第三个 - 旋转。<br/>            如果未定义旋转，则返回 None。 |

### 参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)