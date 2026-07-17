---
title: get_AnimateTransitions()
second_title: Aspose.Slides for C++ API 参考
description: 返回过渡动画选项。只读 bool.
type: docs
weight: 1
url: /zh/aspose.slides.export/ihtml5options/get_animatetransitions/
---
## IHtml5Options::get_AnimateTransitions() 方法

返回过渡动画选项。只读 **bool**。

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateTransitions()=0
```

## 备注

示例：
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```

## 另请参见

* 类 [IHtml5Options](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)