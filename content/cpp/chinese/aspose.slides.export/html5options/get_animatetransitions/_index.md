---
title: get_AnimateTransitions()
second_title: Aspose.Slides 用于 C++ 的 API 参考
description: 返回过渡动画选项。读取 bool.
type: docs
weight: 1
url: /zh/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() 方法


返回过渡动画选项。读取 **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
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