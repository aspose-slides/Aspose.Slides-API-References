---
title: set_AnimateShapes()
second_title: Aspose.Slides for C++ API 参考
description: 设置形状动画选项。写入 bool.
type: docs
weight: 40
url: /zh/aspose.slides.export/html5options/set_animateshapes/
---
## Html5Options::set_AnimateShapes(bool) 方法


设置形状动画选项。写入 **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateShapes(bool value) override
```

## 备注


示例:
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## 参见

* 类 [Html5Options](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)