---
title: get_AnimateShapes()
second_title: Aspose.Slides for C++ API 参考
description: 返回形状动画选项。读取 bool。
type: docs
weight: 27
url: /zh/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() 方法


返回形状动画选项。读取 **bool**。

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
```

## 备注


示例： 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```



## 另见

* 类 [Html5Options](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)