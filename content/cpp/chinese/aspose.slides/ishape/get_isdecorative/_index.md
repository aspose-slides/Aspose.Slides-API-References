---
title: get_IsDecorative()
second_title: Aspose.Slides C++ API 参考
description: 获取 'Mark as decorative' 选项 读/写 **bool**.
type: docs
weight: 404
url: /zh/aspose.slides/ishape/get_isdecorative/
---
## IShape::get_IsDecorative() 方法


获取 'Mark as decorative' 选项 读/写 **bool**.

```cpp
virtual bool Aspose::Slides::IShape::get_IsDecorative()=0
```

## 备注



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## 另见

* 类 [IShape](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)