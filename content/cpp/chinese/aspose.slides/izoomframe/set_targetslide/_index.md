---
title: set_TargetSlide()
second_title: Aspose.Slides for C++ API 参考
description: 设置 Slide Zoom 对象链接的幻灯片对象。写入 ISlide。
type: docs
weight: 14
url: /zh/aspose.slides/izoomframe/set_targetslide/
---
## IZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) 方法

设置 [Slide](../../slide/) Zoom 对象所链接的幻灯片对象。写入 [ISlide](../../islide/)。

```cpp
virtual void Aspose::Slides::IZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value)=0
```

## 备注

下一个示例演示更改目标幻灯片并为 [Slide](../../slide/) Zoom 对象创建新图像：

```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISlide](../../islide/)
* 类 [IZoomFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)