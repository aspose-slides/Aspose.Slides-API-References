---
title: set_OutputPath()
second_title: Aspose.Slides C++ API 参考
description: "确定应将外部资源存储在哪里。写入 System::String."
type: docs
weight: 92
url: /zh/aspose.slides.export/ihtml5options/set_outputpath/
---
## IHtml5Options::set_OutputPath(System::String) 方法


确定应将外部资源存储在哪里。写入 [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_OutputPath(System::String value)=0
```

## 备注


示例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## 另请参见

* 类 [String](../../../system/string/)
* 类 [IHtml5Options](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)