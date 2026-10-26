---
title: get_IsDecorative()
second_title: Aspose.Slides for C++ API 参考
description: 获取 'Mark as decorative' 选项 读/写 bool.
type: docs
weight: 521
url: /zh/aspose.slides/shape/get_isdecorative/
---
## Shape::get_IsDecorative() 方法

获取 'Mark as decorative' 选项 读/写 **bool**.

```cpp
bool Aspose::Slides::Shape::get_IsDecorative() override
```

## 备注


```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## 另见

* 类 [Shape](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)