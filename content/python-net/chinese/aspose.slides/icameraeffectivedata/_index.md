---
title: ICameraEffectiveData class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/icameraeffectivedata/
---
## ICameraEffectiveData 类

不可变对象，包含有效的相机属性。

ICameraEffectiveData 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`camera_type`](/slides/python-net/zh/aspose.slides/icameraeffectivedata/camera_type/) | 相机类型。<br/>            只读 [`CameraPresetType`](/slides/python-net/zh/aspose.slides/camerapresettype)。 |
| [`field_of_view_angle`](/slides/python-net/zh/aspose.slides/icameraeffectivedata/field_of_view_angle/) | 相机视野 (0-180 度, 视场)。<br/>            只读 **float**。 |
| [`zoom`](/slides/python-net/zh/aspose.slides/icameraeffectivedata/zoom/) | 相机缩放 (正值，百分比)。<br/>            只读 **float**。 |

## 方法

| Method | Description |
| :- | :- |
| [`get_rotation(self)`](/slides/python-net/zh/aspose.slides/icameraeffectivedata/get_rotation/#) | 通过使用纬度<br/>            坐标、经度坐标以及围绕轴的旋转来定义旋转 <br/>            作为纬度和经度坐标。<br/>            返回数组的第一个元素 - 纬度，第二个 - 经度，第三个 - 旋转。<br/>            如果未定义旋转，则返回 None。 |

### 备注

此接口用作 [`IThreeDFormatEffectiveData`](/slides/python-net/zh/aspose.slides/ithreedformateffectivedata) 的一部分。

### 另请参阅
* 类 [`IThreeDFormatEffectiveData`](/slides/python-net/zh/aspose.slides/ithreedformateffectivedata)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)