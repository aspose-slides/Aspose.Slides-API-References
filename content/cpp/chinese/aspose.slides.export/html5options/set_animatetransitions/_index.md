---
title: set_AnimateTransitions()
second_title: Aspose.Slides C++ API 参考
description: 设置过渡动画选项。写入 bool.
type: docs
weight: 14
url: /zh/aspose.slides.export/html5options/set_animatetransitions/
---
## Html5Options::set_AnimateTransitions(bool) 方法

设置过渡动画选项。写入 **bool**。

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateTransitions(bool value) override
```

## 备注

示例：
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```

## 另请参阅

* 类 [Html5Options](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)