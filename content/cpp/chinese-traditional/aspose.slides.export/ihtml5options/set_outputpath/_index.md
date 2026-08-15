---
title: set_OutputPath()
second_title: Aspose.Slides for C++ API 參考文件
description: "確定外部資源應儲存的位置。寫入 System::String."
type: docs
weight: 92
url: /zh-hant/aspose.slides.export/ihtml5options/set_outputpath/
---
## IHtml5Options::set_OutputPath(System::String) 方法


確定外部資源應儲存的位置。寫入 [System::String](../../../system/string/)。

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_OutputPath(System::String value)=0
```

## 備註


範例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [IHtml5Options](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)