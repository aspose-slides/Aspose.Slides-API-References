---
title: IntersectClip()
second_title: Aspose.Slides C++ API 参考
description: 将此对象的剪裁区域更新为当前剪裁区域与指定剪裁区域的交集。
type: docs
weight: 950
url: /zh/system.drawing/graphics/intersectclip/
---
## Graphics::IntersectClip(const System::SharedPtr\<Region\>\&) 方法

将此对象的剪裁区域更新为当前剪裁区域与指定剪裁区域的交集。

```cpp
void System::Drawing::Graphics::IntersectClip(const System::SharedPtr<Region> &region)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | const [System::SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | 要相交的区域 |


## Graphics::IntersectClip(System::Drawing::RectangleF) 方法

将此对象的剪裁区域更新为当前剪裁区域与指定剪裁区域的交集。

```cpp
void System::Drawing::Graphics::IntersectClip(System::Drawing::RectangleF rect)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [System::Drawing::RectangleF](../../rectanglef/) | 要相交的矩形 |


## Graphics::IntersectClip(System::Drawing::Rectangle) 方法

将此对象的剪裁区域更新为当前剪裁区域与指定剪裁区域的交集。

```cpp
void System::Drawing::Graphics::IntersectClip(System::Drawing::Rectangle rect)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [System::Drawing::Rectangle](../../rectangle/) | 要相交的矩形 |


## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Region](../../region/)
* 类 [Graphics](../)
* 类 [RectangleF](../../rectanglef/)
* 类 [Rectangle](../../rectangle/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)