---
title: get_OutputPath()
second_title: Aspose.Slides C++ API 参考
description: "确定应将外部资源存储在哪里。阅读 System::String."
type: docs
weight: 79
url: /zh/aspose.slides.export/ihtml5options/get_outputpath/
---
## IHtml5Options::get_OutputPath() 方法


确定应将外部资源存储在哪里。阅读 [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::IHtml5Options::get_OutputPath()=0
```

## 备注


示例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## 参见

* 类 [String](../../../system/string/)
* 类 [IHtml5Options](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)