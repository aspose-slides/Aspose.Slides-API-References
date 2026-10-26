---
title: set_EmbedImages()
second_title: Aspose.Slides for C++ API 参考
description: 设置图像嵌入选项。写入 bool.
type: docs
weight: 66
url: /zh/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) 方法

设置图像嵌入选项。写入 **bool**。

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
```

## 备注

示例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## 另见

* 类 [Html5Options](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)