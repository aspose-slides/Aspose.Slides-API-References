---
title: set_IsDecorative()
second_title: Aspose.Slides C++ API 参考
description: 设置 'Mark as decorative' 选项 读/写 bool.
type: docs
weight: 534
url: /zh/aspose.slides/shape/set_isdecorative/
---
## Shape::set_IsDecorative(bool) 方法

设置 “Mark as decorative” 选项 读/写 **bool**。

```cpp
void Aspose::Slides::Shape::set_IsDecorative(bool value) override
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