---
title: get_GridSpacing()
second_title: Aspose.Slides C++ API 参考
description: 返回用于演示文稿文档底层网格的间距，单位为点。读取 float。
type: docs
weight: 92
url: /zh/aspose.slides/iviewproperties/get_gridspacing/
---
## IViewProperties::get_GridSpacing() 方法


返回演示文稿文档底层网格应使用的间距，单位为点。读取 **float**。

```cpp
virtual float Aspose::Slides::IViewProperties::get_GridSpacing()=0
```

## 备注


网格间距值必须为正数。典型的取值范围是从 1 mm（2.8349607 点）到 2 英寸（144 点）。

以下示例代码展示了如何在 PowerPoint 演示文稿中更改网格间距。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## 另见

* 类 [IViewProperties](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)