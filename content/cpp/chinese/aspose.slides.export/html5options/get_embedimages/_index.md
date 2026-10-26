---
title: get_EmbedImages()
second_title: Aspose.Slides for C++ API 参考
description: 返回图像嵌入选项。读取 bool.
type: docs
weight: 53
url: /zh/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() 方法


返回图像嵌入选项。读取 **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
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