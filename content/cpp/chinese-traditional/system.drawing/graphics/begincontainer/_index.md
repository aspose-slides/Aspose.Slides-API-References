---
title: BeginContainer()
second_title: Aspose.Slides for C++ API 參考
description: 將此物件的當前狀態保存到容器中，開啟並使用新的容器，並返回已保存的容器。
type: docs
weight: 976
url: /zh-hant/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() 方法


保存當前物件狀態的容器，開啟並使用新容器，並返回已保存的容器。

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) 方法


保存當前物件狀態的容器，開啟並使用新容器，並返回已保存的容器。

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | 指定新容器縮放變換的矩形。與 **srcrect** 一起使用 |
| srcrect | [Rectangle](../../rectangle/) | 指定新容器縮放變換的矩形。與 **dstrect** 一起使用 |
| unit | [GraphicsUnit](../../graphicsunit/) | 指定新容器度量單位的值 |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) 方法


保存當前物件狀態的容器，開啟並使用新容器，並返回已保存的容器。

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | 指定新容器縮放變換的矩形。與 **srcrect** 一起使用 |
| srcrect | [RectangleF](../../rectanglef/) | 指定新容器縮放變換的矩形。與 **dstrect** 一起使用 |
| unit | [GraphicsUnit](../../graphicsunit/) | 指定新容器度量單位的值 |

## 參見

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)