---
title: set_IsDecorative()
second_title: Aspose.Slides C++ API 参考
description: 设置 'Mark as decorative' 选项，读/写 bool。
type: docs
weight: 417
url: /zh/aspose.slides/ishape/set_isdecorative/
---
## IShape::set_IsDecorative(bool) 方法

设置 'Mark as decorative' 选项，读/写 **bool**。

```cpp
virtual void Aspose::Slides::IShape::set_IsDecorative(bool value)=0
```

## 备注



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## 另请参见

* 类 [IShape](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)