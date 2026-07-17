---
title: get_TargetSlide()
second_title: Aspose.Slides for C++ API 参考
description: 获取 Slide Zoom 对象链接的幻灯片对象。阅读 ISlide.
type: docs
weight: 1
url: /zh/aspose.slides/zoomframe/get_targetslide/
---
## ZoomFrame::get_TargetSlide() 方法


获取 [Slide](../../slide/) Zoom 对象所链接的幻灯片对象。阅读 [ISlide](../../islide/)。

```cpp
System::SharedPtr<ISlide> Aspose::Slides::ZoomFrame::get_TargetSlide() override
```

## 备注


下面的示例演示了更改目标幻灯片并为 [Slide](../../slide/) Zoom 对象创建新图像： 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISlide](../../islide/)
* 类 [ZoomFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)