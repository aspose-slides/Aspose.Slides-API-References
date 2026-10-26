---
title: set_GridSpacing()
second_title: Aspose.Slides for C++ API 参考
description: 设置应在演示文稿底层网格中使用的网格间距，单位为点。写入 float.
type: docs
weight: 105
url: /zh/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) 方法


设置应在演示文稿底层网格中使用的网格间距，单位为点。写入 **float**.

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
```

## 备注


网格间距值必须为正数。典型的取值范围是从 1 mm（2.8349607 点）到 2 英寸（144 点）。

以下示例代码展示了如何在 PowerPoint 演示文稿中更改网格间距。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## 另请参阅

* 类 [ViewProperties](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)