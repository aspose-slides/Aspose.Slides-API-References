---
title: set_GridSpacing()
second_title: Aspose.Slides 的 C++ API 参考
description: 设置应在演示文稿文档下使用的网格间距，单位为点。写入 float.
type: docs
weight: 105
url: /zh/aspose.slides/iviewproperties/set_gridspacing/
---
## IViewProperties::set_GridSpacing(float) 方法

设置应在演示文稿文档下使用的网格间距，单位为点。写入 **float**。

```cpp
virtual void Aspose::Slides::IViewProperties::set_GridSpacing(float value)=0
```

## 备注

网格间距值必须为正数。典型的取值范围是 1 mm（2.8349607 点）到 2 英寸（144 点）。

下面的示例代码演示了如何在 PowerPoint 演示文稿中更改网格间距。

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## 另见

* 类 [IViewProperties](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)