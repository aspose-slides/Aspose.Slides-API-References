---
title: Camera
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/camera/
---
## Camera 类

 表示 Camera。
 
### getCameraType {#getCameraType}

| Name | Description |
| --- | --- |
| getCameraType () | 相机类型。读取/写入 CameraPresetType。 |

 **返回：**
int


---


### getFieldOfViewAngle {#getFieldOfViewAngle}

| Name | Description |
| --- | --- |
| getFieldOfViewAngle () | 相机视场 (0-180 度，视野)。读取/写入 float。 |

 **返回：**
float


---


### getRotation {#getRotation}

| Name | Description |
| --- | --- |
| getRotation () | 通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义旋转。返回数组的第一个元素-纬度，第二个-经度，第三个-旋转。如果未定义旋转，则返回 null。 |

 **返回：**
float


---


### getVersion {#getVersion}

| Name | Description |
| --- | --- |
| getVersion () |  |

 **返回：**
long


---


### getZoom {#getZoom}

| Name | Description |
| --- | --- |
| getZoom () | 相机缩放（百分比的正值）。读取/写入 float。 |

 **返回：**
float


---


### setCameraType {#setCameraType}

| Name | Description |
| --- | --- |
| setCameraType (int) | 相机类型。读取/写入 CameraPresetType。 |

 **返回：**
void


---


### setFieldOfViewAngle {#setFieldOfViewAngle}

| Name | Description |
| --- | --- |
| setFieldOfViewAngle (float) | 相机视场 (0-180 度，视野)。读取/写入 float。 |

 **返回：**
void


---


### setRotation {#setRotation}

| Name | Description |
| --- | --- |
| setRotation (float, float, float) | 通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义旋转。如果任一坐标值为 Float.NaN，则全部旋转未定义。 |

 **返回：**
void


---


### setZoom {#setZoom}

| Name | Description |
| --- | --- |
| setZoom (float) | 相机缩放（百分比的正值）。读取/写入 float。 |

 **返回：**
void


---